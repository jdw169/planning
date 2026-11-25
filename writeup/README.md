# Project 4: Planning [![tests](../../../badges/submit-proj4/pipeline.svg)](../../../pipelines/submit-proj4/latest)

Replace this with your own writeup! Please place all figures in this directory.

2.1

r = 61:
python3 scripts/run_search -m test/share/map2.txt -n 600 -r 61 r2 -s 252 115 -g 350 350
Lazy: False
Vertices: 602
Edges: 8797
Running A*
Path length: 363.068415217045
Planning time: 0.23038983345031738
Edges evaluated: 9231

r = 200
python3 scripts/run_search -m test/share/map2.txt -n 600 -r 200 r2 -s 252 115 -g 350 350
Lazy: False
Vertices: 602
Edges: 51183
Running A*
Path length: 362.88669499958723
Planning time: 2.573544979095459
Edges evaluated: 73204

n=541
python3 scripts/run_search -m test/share/map2.txt -n 541 -r 100 r2 -s 252 115 -g 350 350
Lazy: False
Vertices: 543
Edges: 16098
Running A*
Path length: 362.88692665140957
Planning time: 0.5077550411224365
Edges evaluated: 18559

n=1200
python3 scripts/run_search -m test/share/map2.txt -n 1200 -r 100 r2 -s 252 115 -g 350 350
Lazy: False
Vertices: 1202
Edges: 80280
Running A*
Path length: 356.3329847638013
Planning time: 2.503153085708618
Edges evaluated: 92124

2.2

Lazy A*
python3 scripts/run_search -m test/share/map2.txt -n 600 -r 100 --lazy r2 -s 252 115 -g 350 350
Lazy: True
Vertices: 602
Edges: 23016
Running A*
Path length: 362.88692665140957
Planning time: 0.12430000305175781
Edges evaluated: 833

A*
python3 scripts/run_search -m test/share/map2.txt -n 600 -r 100 r2 -s 252 115 -g 350 350
Lazy: False
Vertices: 602
Edges: 19972
Running A*
Path length: 362.88692665140957
Planning time: 0.6553897857666016
Edges evaluated: 23016

