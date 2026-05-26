# AI-Based Network Pathfinding & Attack Simulation System

## Project Overview
This project simulates a cybersecurity threat actor navigating a computer network to reach a target asset. The network is modeled as a mathematical graph, and various Artificial Intelligence search algorithms are utilized to determine attack paths, evaluate network vulnerabilities, and analyze algorithmic efficiency.

## Implemented Algorithms
1. Breadth-First Search (BFS)
2. Depth-First Search (DFS)
3. Uniform Cost Search (UCS)
4. A* Search (using a custom topological vulnerability heuristic)
5. Hill Climbing (featuring a specifically engineered local maximum trap)
6. Minimax with Alpha-Beta Pruning (Adversarial Attacker vs. Defender simulation)

## Prerequisites and Dependencies
The source code is written in Python and is designed to run seamlessly in Google Colab or any local Jupyter Notebook environment. 

The following Python libraries are required:
* `time` (Standard Library)
* `heapq` (Standard Library)
* `pandas` (Data manipulation and table generation)
* `networkx` (Graph data structure and topology generation)
* `matplotlib` (Visual rendering of the network graph)

If running locally, you can install the required external dependencies via pip:
`pip install pandas networkx matplotlib`

## Execution Instructions
1. **Google Colab (Recommended):**
   * Upload the `LAB_MID.ipynb` file to Google Colab (colab.research.google.com).
   * Go to the top menu and select **Runtime > Run all** (or press `Ctrl + F9`).
   * Scroll down to view the generated Comparative Analysis Table and the visual representation of the network topology.

2. **Local Jupyter Environment:**
   * Open the `.ipynb` file in your local Jupyter instance.
   * Select **Cell > Run All**.
   * The terminal output will display the pathfinding metrics, and the UI graph will render inline.
