# Optimized Packet Routing using Dijkstra's Algorithm

## Overview

This project demonstrates how Dijkstra's Algorithm can be used to optimize packet routing in a computer network by finding the lowest-cost path between routers.

## Features

- Dijkstra's shortest path algorithm
- Weighted network graph
- Network topology visualization using NetworkX
- Congestion score calculation
- Path reconstruction

## Technologies

- Python
- NetworkX
- Matplotlib
- heapq

## Example Output

Optimal Path:

HQ_Router → Switch_A → Switch_B → Hub_East → Server_Farm

Total Score: 8

## Network Topology
<img width="825" height="640" alt="Screenshot 2026-07-14 at 20 02 20" src="https://github.com/user-attachments/assets/d9d42bd2-ba84-479c-89df-0687be856f60" />

## How to Run

```bash
pip install networkx matplotlib
```

Then run the notebook:

```bash
jupyter notebook Network.ipynb
```
