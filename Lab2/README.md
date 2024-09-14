<div align="center">
  
![image](https://github.com/user-attachments/assets/eb3535c2-35e2-40de-af0c-3dc39996e10b)




### Artificial Intelligence (Lab)

### Lab 02: Introduction to search in AI: Problem spaces, states, and goals

### Syed Muhammad Naqi Raza

### 2022574

### Cyber Security

</div>


### A* Algorithm

The A* algorithm, pronounced "A-star," is a widely used graph traversal and pathfinding algorithm that efficiently finds the shortest path between a starting node and a goal node in a weighted graph. It is particularly notable for its completeness, optimality, and efficiency, making it applicable in various fields, including computer science, robotics, and video game development.

<div align="center">

![image](https://github.com/user-attachments/assets/2d13b0d9-18e5-446d-bf11-05f8d3eb6501)

</div>


### Key Components

The A* algorithm operates based on a cost function $$ f(n) $$, which is the sum of two other functions:

- **g(n)**: The actual cost from the start node to node $$ n $$.
- **h(n)**: The heuristic estimated cost from node $$ n $$ to the goal node. This heuristic must be admissible, meaning it should never overestimate the actual cost.

Thus, the formula is:

$$
f(n) = g(n) + h(n)
$$

### How It Works

1. **Initialization**: The algorithm starts with an open list (nodes to be evaluated) and a closed list (nodes already evaluated).
  
2. **Node Selection**: At each step, A* selects the node with the lowest $$ f $$-value from the open list for exploration.

3. **Path Expansion**: The algorithm expands the selected node by evaluating its neighbors, updating their $$ g $$ and $$ h $$ values, and adding them to the open list if they are not already present.

4. **Goal Check**: If the selected node is the goal node, the algorithm reconstructs the path from the start to the goal.

5. **Termination**: The process continues until the goal is reached or the open list is empty, indicating that no path exists.

### Applications

A* is commonly used in various applications, such as:

- **Navigation Systems**: For calculating the shortest route on maps.
- **Robotics**: For path planning in environments with obstacles.
- **Video Games**: For character movement and AI navigation.

### Conclusion

The A* algorithm is a powerful tool for pathfinding and graph traversal, leveraging heuristics to optimize the search process and ensure efficient pathfinding in complex environments[1][2][4][6].

Citations:

[1] https://www.simplilearn.com/tutorials/artificial-intelligence-tutorial/a-star-algorithm

[2] https://www.educative.io/answers/what-is-the-a-star-algorithm

[3] https://www.scribbr.com/ai-tools/what-is-an-algorithm/

[4] https://en.wikipedia.org/wiki/A-star

[5] https://www.simplilearn.com/tutorials/data-structure-tutorial/what-is-an-algorithm

[6] https://www.geeksforgeeks.org/a-search-algorithm/
[7] https://www.techtarget.com/whatis/definition/algorithm
[8] https://www.merriam-webster.com/dictionary/algorithm




