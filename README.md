# ndmazes

Python tool for generating mazes of 2 to n dimensions!

To make a 7x7x7 3-dimensional maze with a randomized Prim's algorithm:
```ndmazes make -e -i prim 7 7 7```

## Supported probabalistic maze algorithms
• Prim
```
###################	######S#########F##
F...#...........#.#	#........#...#.#..#
#.###.#.#.###.#.#.#	######.#####.#.#.##
#...#.#.#.#...#.#.S	#....#.....#.#....#
#.###.#########.#.#	##.###.#####.#.####
#.............#...#	#........#.....#..#
#.#.###########.#.#	##.###.###.#####.##
#.#...........#.#.#	#..#..............#
###################	###################
```

• Kruskal

• Density islands
```
###################	###################
S.#.#.............#	#.................#
#.#.#.#######.###.#	#.###.#######.###.#
#.#...#.......#.#.#	#.#...#.......#.#.#
#.###.#####.###.#.#	#.###.#.#.#####.#.#
#...#.....#.#.....F	#...#.#.#.#...#...F
#.###.#####.#####.#	#.#.###.###.#######
#.................#	#.................S
###################	###################
```
