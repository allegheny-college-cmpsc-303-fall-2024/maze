# Search Examples

This code includes code that can solve a maze using either DFS (depth first search) or BFS (breadth first search). It outputs solutions on the command line and as a png (the most recent out put is saved in the repo directory as `maze.png`). Three mazes are included in the repo. 

## How to Use

Set up a virtual environment with `pillow`, the image-procesing library used to output solution images. 

```
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
```

You can also use `poetry` or the package manager of your choice. 

The implementation format from the command line is: 

`python maze.py <maze-reference>.txt`

There are three mazes you can use in the above in this repo (`maze1.txt`, `maze2.txt`, `maze3.txt`).  You can also try makign a text document of a maze with your own design!

Change the search algorithm used by changing the `Frontier` class assigned in the code. 

**Acknowledgments**: This code is borrowed from [CS50 Artificial Intelligence](https://cs50.harvard.edu/ai/2024/license/)
