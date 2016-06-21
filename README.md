# Overview
Built general search algorithms and apply them to Pacman maze world.

# Running
* Depth First Search
```
$ python pacman.py -l mediumMaze -p SearchAgent
```

* Breadth First Search
```
$ python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs
```

* Uniform Cost Search
```
python pacman.py -l mediumScaryMaze -p StayWestSearchAgent
```

* A* Search
```
python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic
```