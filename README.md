# FR-Graph-Visualization
Datasets, Gephi layouts, and image generation scripts for the paper: Enhanced Fruchterman-Reingold

# Enhanced Fruchterman-Reingold: Scalable Visualization and Optimization Techniques for Complex Networks
This repository contains the layout configuration files to the manuscript submitted to *The Visual Computer*.

### How to Replicate the Gephi Visualizations

To reproduce the graph layouts presented in Section 3.0 (Tables 2, 3, and 4) of the manuscript, follow these step-by-step instructions using the provided `.gephi` project files.

**Prerequisites:**
* Download and install [Gephi](https://gephi.org/) (version 0.9.2 or later).

**Replication Steps:**
1. **Open the Project:** Launch Gephi and go to `File > Open`. Select one of the provided `.gephi` project files from this repository.
2. **Navigate to the Layout Panel:** In the "Overview" workspace, locate the **Layout** module (typically on the bottom-left of the screen).
3. **Select the Algorithm:** From the layout drop-down menu, select **Fruchterman Reingold**.
4. **Configure Parameters:** To replicate the specific structural distributions shown in the paper's empirical tables, input the following combinations into the layout properties:
   * **Area Size:** Set to `100.0`, `1000.0`, or `10000.0` (Controls overall scale and density).
   * **Gravity:** Set to `1.0`, `5.0`, or `10.0` (Controls graph compactness).
   * **Speed:** Keep at default.
5. **Run the Simulation:** Click the **Run** button. The graph will begin moving. Allow the simulation to run until the nodes settle into a stable state (equilibrium), then click **Stop**.
6. **Export (Optional):** To save the result as an image, navigate to the **Preview** workspace, adjust any final aesthetic rendering settings (node size, edge thickness), and click `Export: SVG/PDF/PNG` at the bottom left.

## Repository Contents

### 1. Original Data (`Raw Data.gexf`)
The empirical demonstrations in this repository utilize the standard Les Misérables character co-appearance network (74 nodes, 248 edges), originally compiled by Donald Knuth (1993). The specific .gexf file format used in this project was sourced from the Gephi open-source tutorial by Clement Levallois:

Levallois, C. (2017). Simple network visualization from A to Z. Available at: (https://seinecle.github.io/gephi-tutorials/generated-html/simple-project-from-a-to-z-en.html)

### 2. Gephi Project Files (`.gephi`)
These files contain the force-directed graph layouts discussed in Section 3.0 of the paper. They demonstrate the structural clarity of the network using the following parameters:
* Area Sizes: 100, 1000, 10000
* Gravity Sizes: 1.0, 5.0, 10.0
