# A* Path Planning Project

## Overview

This project focuses on A* Path Planning, a popular pathfinding algorithm used in robotics and artificial intelligence. A* is known for its efficiency and optimality in finding the shortest path from a start point to a goal point on a grid or graph.

The project includes an implementation of the A* algorithm and visualization of its performance on various maps, making it a valuable resource for understanding path planning in a simulated environment.

## A* Algorithm

The A* algorithm is a search algorithm used to find the optimal path from a start node to a goal node in a weighted graph. It combines two essential components:

- **G-Cost (Actual Cost):** The cost to reach the current node from the start node.
- **H-Cost (Heuristic Cost):** An estimation of the cost from the current node to the goal node.

A* selects nodes to expand based on their total cost, which is the sum of G-Cost and H-Cost. By exploring nodes with lower total cost first, A* efficiently finds the shortest path while considering a heuristic to guide its search.

## Flowchart

![Algorithm Flowchart](https://user-images.githubusercontent.com/106331831/236201740-8626b4d5-e1f8-4ea8-aebe-7ddca2a3137e.png)

The flowchart above illustrates the key steps of the A* algorithm:

1. Start at the initial node.
2. Expand the node with the lowest total cost (G-Cost + H-Cost).
3. Add neighboring nodes to the open list.
4. Calculate G-Cost and H-Cost for each neighbor.
5. Repeat steps 2-4 until the goal node is reached or no more nodes are available.

## Different Maps

<table>
    <tr>
    <td>map.png</td>
    <td>map1.png</td>
    <td>map2.png</td>
  </tr>
  <tr>
    <td><img src="https://github.com/MostafaELFEEL/2D-A-star-path-planning-using-only-NumPy/assets/106331831/6528af7e-245a-4097-8539-69953a413a3b" width="300" height="300"></td>
    <td><img src="https://github.com/MostafaELFEEL/2D-A-star-path-planning-using-only-NumPy/assets/106331831/7c15f4f8-df73-4ed6-ab9a-0b5f1b3eef58" width="300" height="300"></td>
    <td><img src="https://github.com/MostafaELFEEL/2D-A-star-path-planning-using-only-NumPy/assets/106331831/796bf18a-5e15-4415-aa44-727254420184" width="300" height="300"></td>
  </tr>

</table>


## Results

A* algorithm has been evaluated on each map, demonstrating its ability to find optimal paths in various scenarios. The results are visualized in the following images:



<table>
    <tr>
    <td>map.png</td>
    <td>map1.png</td>
    <td>map2.png</td>
  </tr>
  <tr>
    <td><img src="https://github.com/MostafaELFEEL/2D-A-star-path-planning-using-only-NumPy/assets/106331831/ce830c66-780a-480f-9838-fb1298d168bf" width="300" height="300"></td>
    <td><img src="https://github.com/MostafaELFEEL/2D-A-star-path-planning-using-only-NumPy/assets/106331831/8660fe93-0f6f-450c-893e-9c2feca14657" width="300" height="300"></td>
    <td><"GOAL IS UNREACHABLE"></td>
  </tr>

</table>


## Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/MostafaELFEEL/A-star-path-planning.git





