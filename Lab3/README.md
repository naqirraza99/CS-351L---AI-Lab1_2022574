**Neighboring Countries Graph Coloring Problem**

*Overview:*

This project demonstrates the application of graph coloring to a map coloring problem using a Constraint Satisfaction Problem (CSP) approach. The specific scenario involves assigning colors to neighboring countries such that no two adjacent countries share the same color. This is a real-world example of CSP, where countries are represented as nodes and borders between them as edges in a graph.

The graph coloring algorithm is implemented using backtracking with the Minimum Remaining Values (MRV) heuristic, which ensures that the most constrained nodes (countries with the fewest available legal colors) are assigned colors first. The program visualizes the coloring process step by step, helping to understand how the algorithm works dynamically.

**Project Structure**

. Graph Representation: Countries are represented as nodes, and the borders between them as edges.

. Colors: Three colors (Red, Green, Blue) are available, and the task is to assign them in such a way that             no two neighboring countries share the same color.

. Heuristics: The MRV heuristic is used to select the next country to color, minimizing conflicts by       
          choosing the most constrained countries first.

** Features:**

**Real-World Scenario:** The project models a map coloring problem using real countries and their borders.

**MRV Heuristic:** Efficiently assigns colors by focusing on the most constrained countries first.

**Backtracking:** Ensures that all constraints are satisfied, and backtracks if conflicts arise.

**Visualization:** The graph coloring process is visualized step by step using the matplotlib and networkx libraries.

**Installation:**

To run this project, you will need to have Python installed along with the required libraries. You can install the dependencies using pip.

# Install necessary libraries
pip install networkx matplotlib

**How to Run**

Clone this repository to your local machine or download the Python file.

Run the Python script:

python graph_coloring_mrv.py

The program will display the step-by-step process of coloring the countries' graph using the MRV heuristic.
