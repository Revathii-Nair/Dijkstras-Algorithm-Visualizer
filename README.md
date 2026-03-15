# Dijkstra’s Algorithm Visualizer

An interactive, web-based tool to visualize **Dijkstra’s Shortest Path Algorithm**. This project features a real-time pathfinding animations, and live distance table updates.

🔗 **[Live Demo](https://revathii-nair.github.io/Dijkstras-Algorithm-Visualizer/)**


## Features

- **Real-time Visualization:** Watch the algorithm traverse the graph with customizable speeds (Slow to Faster).
- **Dynamic Graph Input:** Add your own nodes and edges using a simple coordinate-based format: `(A,B,5),(B,C,3)`.
- **Live Distance Map:** A real-time updating table showing the shortest known distance to every vertex.
- **Interactive Controls:** Pause, Resume, and Theme switching on the fly.


## Tech Stack

- **Frontend:** HTML5, CSS3 (Grid & Flexbox)
- **Graphics:** HTML5 Canvas API
- **Library:** jQuery 3.7.1


## Algorithm Overview

Dijkstra's algorithm finds the shortest path from a starting node to all other nodes in a weighted graph.

**Time Complexity:** $$O((V + E) \log V)$$
_(When implemented with a Priority Queue)_

**Space Complexity:** $$O(V + E)$$
