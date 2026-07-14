# Dijkstra's-Based Optimized Packet Routing

A Python implementation of Dijkstra's shortest path algorithm to simulate optimized packet routing across a computer network.

The project models routers, switches, and servers as a weighted graph and computes the minimum-cost route between two devices.

---

## Features

- Implements Dijkstra's shortest path algorithm
- Models a computer network using weighted graphs
- Calculates the optimal packet route
- Displays the total routing cost
- Visualizes the network topology using NetworkX
- Highlights the optimal routing path in red

---

## Technologies Used

- Python
- NetworkX
- Matplotlib
- Heapq

---

## Example Network

<img width="825" height="640" alt="Screenshot 2026-07-14 at 20 02 20" src="https://github.com/user-attachments/assets/d9d42bd2-ba84-479c-89df-0687be856f60" />

---

## Example Output

```
Optimal Path:
HQ_Router → Switch_A → Switch_B → Hub_East → Server_Farm

Total Cost:
8
```

---

## Network Visualization

<img width="1640" height="1318" alt="3936B7FB-8E21-4FED-9AB2-66F7F5380ED6" src="https://github.com/user-attachments/assets/67d5f79a-0b01-4776-93cd-085057174e4b" />

---

## Project Structure

```
wilken_group/
│
├── Network.ipynb
├── README.md
└── requirements.txt (optional)
```

---

## How It Works

Each network device is represented as a node.

Each connection between devices is represented as a weighted edge where the weight corresponds to network congestion or routing cost.

Dijkstra's algorithm explores all possible routes while maintaining the minimum cumulative cost until the destination server is reached.

The resulting shortest path is highlighted in the visualization.

---

## Future Improvements

- Interactive routing interface using Streamlit
- Dynamic user-defined network topology
- Larger simulated enterprise networks
- Performance comparison with other routing algorithms

---

## Author

Johnson Nyabicha

First Year BSc Computer Science  
University of Exeter
