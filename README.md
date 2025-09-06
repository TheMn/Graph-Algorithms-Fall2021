# Graph Algorithms Course - Fall 2021

This repository contains homework assignments for the "Graph Algorithms and Networks" course at the University of Tehran, completed in the fall of 2021. The assignments are written in Persian and compiled using LaTeX.

## Repository Contents

This repository includes the following files and directories:

- **`HW1.tex`**: The LaTeX source file for the first homework assignment.
- **`HW2.tex`**: The LaTeX source file for the second homework assignment.
- **`Photos/`**: A directory containing images used in the homework assignments.
- **`neurips.sty`, `kbordermatrix.sty`**: LaTeX style files used for formatting the documents.
- **`XB Yas*.ttf`**: The Persian font files required to compile the documents.
- **`LICENSE`**: The license for this repository.
- **`.gitignore`**: A file specifying which files and directories to ignore in Git.

## Homework Topics

### Homework 1 (`HW1.tex`)

This assignment covers fundamental concepts of graph theory, including:

- **Graph Properties**: Calculating in-degrees and out-degrees of vertices.
- **Graph Representation**: Creating adjacency lists for given graphs.
- **Paths and Cycles**: Finding paths and identifying cycles in graphs.
- **Graph-level Properties**: Determining if graphs are acyclic, bipartite, or strongly connected.
- **Minimum Spanning Trees**: Finding the Minimum Spanning Tree (MST) of a graph using Kruskal's algorithm.

### Homework 2 (`HW2.tex`)

This assignment delves into more advanced graph algorithms:

- **Matrix Representations**: Creating node-arc incidence and node-node adjacency matrices.
- **Network Flow**: Modifying graphs to handle negative costs, arc capacities, and non-zero lower bounds.
- **Graph Traversal**: Performing Breadth-First Search (BFS) and Depth-First Search (DFS) and generating the corresponding trees.
- **Topological Sorting**: Finding a topological sort of a directed acyclic graph.
- **Shortest Path**: Applying Dijkstra's algorithm to find the shortest paths from a single source.

## How to Compile

To compile the `.tex` files and generate PDFs of the homework assignments, you will need a working LaTeX distribution that supports `XeLaTeX`. TeX Live is recommended.

### Dependencies

- **LaTeX Distribution**: TeX Live, MiKTeX, or MacTeX.
- **`xepersian` package**: This package is essential for compiling LaTeX documents with Persian text. It is included in most modern TeX distributions.
- **`XB Yas` font**: The font files are included in this repository. Ensure they are accessible to your LaTeX distribution, either by placing them in the same directory as the `.tex` files or by installing them on your system.

### Compilation Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/Graph-Algorithms-Fall2021.git
   cd Graph-Algorithms-Fall2021
   ```
2. **Compile with `xelatex`**:
   To compile the homework files, use the `xelatex` command. For example, to compile `HW1.tex`:
   ```bash
   xelatex HW1.tex
   ```
   You may need to run the command twice to ensure all cross-references are correctly updated.

This will produce a `HW1.pdf` file in the same directory. Repeat the process for `HW2.tex`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
