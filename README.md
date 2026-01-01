📌 Project Title

Shortest Path Finder using A* Search Algorithm

🎯 Objective

To implement the A* search algorithm to find the optimal shortest path between a start node and a goal node in a grid environment containing obstacles.

🧠 Description

A* search is an informed search algorithm that uses both:

Actual cost (g(n)) from the start node

Heuristic cost (h(n)) to estimate distance to the goal

The total cost is calculated using:

f(n) = g(n) + h(n)


The algorithm always expands the node with the lowest f(n) value, ensuring an optimal solution.

📐 Heuristic Used

Manhattan Distance

h(n) = |x1 − x2| + |y1 − y2|


This heuristic is:

Admissible

Consistent

Guarantees optimal path

🗺️ Problem Representation

Grid-based environment

0 → Free cell

1 → Obstacle

Movement allowed: Up, Down, Left, Right

Each move has a cost of 1

⚙️ Algorithm Steps

Initialize OPEN list with start node

Set g(start) = 0

Compute f(n) = g(n) + h(n)

Select node with minimum f(n)

Expand node and generate successors

Update costs and parent nodes

Repeat until goal is reached

🧪 Output

Shortest path from start to goal

Path cost

Nodes expanded using A* search

✅ Advantages

Finds optimal solution

Efficient compared to BFS and DFS

Widely used in AI and pathfinding

⚠️ Limitations

Requires more memory

Performance depends on heuristic accuracy

🧾 Conclusion

This project demonstrates the working of the A* search algorithm using a simple grid model. It clearly shows how heuristics improve search efficiency and help in finding optimal paths.
