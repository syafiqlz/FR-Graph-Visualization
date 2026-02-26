# FR-Graph-Visualization
Datasets, Gephi layouts, and image generation scripts for the paper: Enhanced Fruchterman-Reingold

# Enhanced Fruchterman-Reingold: Scalable Visualization and Optimization Techniques for Complex Networks
This repository contains the layout configuration files to the manuscript submitted to *The Visual Computer*.

## Repository Contents

### 1. Original Data (`Raw Data.gexf`)
The empirical demonstrations in this repository utilize the standard Les Misérables character co-appearance network (74 nodes, 248 edges), originally compiled by Donald Knuth (1993). The specific .gexf file format used in this project was sourced from the Gephi open-source tutorial by Clement Levallois:

Levallois, C. (2017). Simple network visualization from A to Z. Available at: (https://seinecle.github.io/gephi-tutorials/generated-html/simple-project-from-a-to-z-en.html)

### 2. Gephi Project Files (`.gephi`)
These files contain the force-directed graph layouts discussed in Section 3.0 of the paper. They demonstrate the structural clarity of the network using the following parameters:
* Area Sizes: 100, 1000, 10000
* Gravity Sizes: 1.0, 5.0, 10.0
