---
title:  Coding interview prep
date: 2025-03-04
tags: []
mathjax: true
---

I’m needing to study for coding interviews, and am not feeling a whole lot of motivation for doing so. I thought it might help to write down notes as I do so; I sure find it a lot more motivating!

# BFS
As I learned from a friend who has an interview-prep startup, BFS is the most important topic in coding interviews these days. It is just everywhere! BFS stands for breadth-first search, which is a very useful search algorithm. The name is pretty self-explanatory. It has a cousin named depth-first search (DFS) that is also pretty useful.

A center piece of the algorithm is the data structure called _queue_. Like an actual queue, a queue is first-in-first out. This matches our intuition of how to conduct a breadth-first search: at every depth, we search all the nodes at this depth, before going to the next level.

Here is how it usually goes, in not-quite-coherent code:
 ```
from collections import deque
queue = deque()
visited = set()
# add the starting point of search
queue.append(start)
while queue:
    current = queue.popleft()
    # skip this visit if we have already been here
    # only needed when there are multiple ways of reaching a node
    if current in visited:
        continue
    # do computation
    for neighbor in get_neighbors(current):
        queue.append(neighbor)
```

## Trees

## Graphs

## Flood fill

## Bellman-Ford (shortest path)

# Concurrency

Bitwise AND always results in a number no greater than the smaller of the arguments.

# Individual Problems
787. Cheapest Flights Within K Stops

Instead tracking visited, track best price to a given city found so far

100. Same Tree
1609. Even Odd Tree
977. Squares of a Sorted Array
