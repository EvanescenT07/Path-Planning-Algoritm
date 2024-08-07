# Path Planning Algorithms for Intelligent Robotics

This project demonstrates path planning algorithms for intelligent robotics, specifically using the Breadth-First Search (BFS) and Dijkstra's algorithms. The implementation is designed to run on Google Colab.

## Prerequisites

To run this notebook, you need to install the following libraries:

```python
!pip install numpy matplotlib
!apt-get install ffmpeg
```

## Libraries Used

NumPy: For numerical operations.
Matplotlib: For plotting and visualization.
heapq: For priority queue operations (used in Dijkstra's algorithm).

# Algorithms

## Breadth-First Search (BFS)

Breadth-First Search is an algorithm for traversing or searching tree or graph data structures. It starts at the root (or an arbitrary node in the case of a graph) and explores the neighbor nodes at the present depth prior to moving on to nodes at the next depth level.

## Dijkstra's Algorithm

Dijkstra's algorithm finds the shortest path between nodes in a graph, which may represent, for example, road networks. It is widely used in routing and as a subroutine in other algorithms.

## Running the Project

Open Google Colab and create a new notebook.
Copy and paste the code cells from this repository into your notebook.
Run the cells sequentially to see the path planning algorithms in action.

## Usage

Breadth-First Search:
Implement and visualize the BFS algorithm in the context of path planning.

Dijkstra's Algorithm:
Implement and visualize Dijkstra's algorithm for finding the shortest path.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

Google Colab for providing the environment to run this notebook.
NumPy and Matplotlib for their powerful libraries.
