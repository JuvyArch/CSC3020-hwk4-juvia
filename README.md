# graphs_juvia

`graphs_juvia` is a Python library containing graph-related algorithms. The library includes an implementation of Dijkstra's shortest path algorithm for finding the shortest paths from a source vertex to other vertices in a weighted graph.

## Installation

The package can be installed using pip:

```bash
pip install .
```

## Usage

```python

from graphs_juvia import sp

graph = {
    0: {1: 4, 2: 8},
    1: {2: 3},
    2: {}
}

dist, path = sp.dijkstra(graph, 0)

print(dist)
print(path)
```