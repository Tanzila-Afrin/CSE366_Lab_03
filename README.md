# Maze Search Algorithm Performance

Here are the tables for each maze (tinyMaze, mediumMaze, bigMaze) with the actual time and length of the path for each search algorithm (BFS, DFS, UCS). The data is hypothetical and should be replaced with actual results after running the respective commands.

### tinyMaze

| Algorithm | Time (s) | Length of Path |
|-----------|----------|----------------|
| BFS       | 0.000935     | 8              |
| DFS       | 0.000374     | 10              |
| UCS       | 0.000876     | 8              |

### mediumMaze

| Algorithm | Time (s) | Length of Path |
|-----------|----------|----------------|
| BFS       | 0.004183     | 68             |
| DFS       | 0.002209     | 130            |
| UCS       | 0.010518     | 68             |

### bigMaze

| Algorithm | Time (s) | Length of Path |
|-----------|----------|----------------|
| BFS       | 0.007281  | 210            |
| DFS       | 0.005235   | 210            |
| UCS       | 0.042992    | 210            |

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
