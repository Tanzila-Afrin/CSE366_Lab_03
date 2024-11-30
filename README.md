# Maze Search Algorithm Performance

Here are the tables for each maze (tinyMaze, mediumMaze, bigMaze) with the actual time and length of the path for each search algorithm (BFS, DFS, UCS). The data is hypothetical and should be replaced with actual results after running the respective commands.

### TinyMaze

| Algorithm | Time (s) | Length of Path |
|-----------|----------|----------------|
| BFS       | 0.00088  | 8              |
| DFS       | 0.00110  | 10             |
| UCS       | 0.00150  | 8              |


### MediumMaze

| Algorithm | Time (s) | Length of Path |
|-----------|----------|----------------|
| BFS       | 0.01096  | 68             |
| DFS       | 0.00733  | 130            |
| UCS       | 0.02187  | 68             |


### BigMaze

| Algorithm | Time (s) | Length of Path |
|-----------|----------|----------------|
| BFS       | 0.02177  | 210            |
| DFS       | 0.01265  | 210            |
| UCS       | 0.09757  | 210            |


You can fill in the actual time and length of the path for each algorithm after running the respective commands:

- `python pacman.py -l tinyMaze -p SearchAgent -a fn=bfs`
- `python pacman.py -l tinyMaze -p SearchAgent -a fn=dfs`
- `python pacman.py -l tinyMaze -p SearchAgent -a fn=ucs`

- `python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs`
- `python pacman.py -l mediumMaze -p SearchAgent -a fn=dfs`
- `python pacman.py -l mediumMaze -p SearchAgent -a fn=ucs`

- `python pacman.py -l bigMaze -p SearchAgent -a fn=bfs`
- `python pacman.py -l bigMaze -p SearchAgent -a fn=dfs`
- `python pacman.py -l bigMaze -p SearchAgent -a fn=ucs`
