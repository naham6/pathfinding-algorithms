# Graph Search Algorithms Visualizer

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)
![NetworkX](https://img.shields.io/badge/NetworkX-005C94.svg?style=for-the-badge&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

An interactive, visual educational tool demonstrating how different graph search algorithms navigate a weighted network. Allowing users to dynamically select start and goal nodes, comparing the final paths, total computational costs, and explored nodes (the "thought process") across five classic algorithms.

## Algorithms Compared

* **Breadth-First Search (BFS) & Depth-First Search (DFS):** "Uninformed" or blind searches. They guarantee finding a path based on the fewest geometric hops, but completely ignore edge weights (travel costs), often resulting in an expensive route.
* **Uniform Cost Search (UCS):** Evaluates the actual edge weights ($g$-cost) between nodes. It guarantees finding the mathematically cheapest path, but can be slow as it explores equally in all directions.
* **Greedy Best-First Search:** An "informed" search that relies entirely on a Heuristic ($h$-cost) estimating the remaining distance to the goal. It is very fast, but easily falls into traps and rarely finds the optimal cost path.
* **A* (A-Star) Search:** The optimal standard. It combines the actual cost traveled so far ($g$) with the heuristic estimate to the goal ($h$). It guarantees the absolute cheapest path while exploring significantly fewer nodes than UCS.

## Real-World Applications

* **GPS & Navigation** 
* **Network Routing** 
* **AI Decision Trees** 
