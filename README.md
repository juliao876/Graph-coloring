# Graph Coloring
> A C++ application designed to solve graph coloring problems using a recursive traversal approach.

[![Language](https://img.shields.io/badge/Language-C++-blue.svg)](https://isocpp.org/)
[![Documentation](https://img.shields.io/badge/Docs-Doxygen-brightgreen.svg)](refman.pdf)

---

## 📋 Description
This project provides a robust implementation for assigning "colors" to the vertices of a graph such that no two adjacent vertices share the same color. It utilizes a recursive algorithm to traverse the graph's neighborhood and determine a valid coloring configuration.

## Main Features
* **Recursive Coloring**: Implements a neighborhood-based recursive strategy to ensure all vertices are processed.
* **Input/Output Flexibility**: Supports reading graph data from external files and exporting results to a specific output file.
* **Validation Logic**: Includes a verification system for command-line parameters to ensure program stability.
* **Color Optimization**: Automatically calculates the total number of unique colors utilized in the final graph state.
* **Neighborhood Verification**: Built-in functions to verify if adjacent vertices are already colored before proceeding.

## Project Resources & Operating
The system operates by processing a graph represented as an adjacency list or matrix. Key components include:
* **Core Logic**: `model.h` and `model.cpp` contain the functions for coloring, file handling, and validation.
* **Entry Point**: `main.cpp` manages the application lifecycle and user input.
* **Documentation**: Detailed technical info is available in **refman.pdf**.
* **Operating Logic**: The program verifies input parameters, loads the graph into a nested vector structure, and executes the `pokolorujGraf` function to begin the recursive assignment.

## Prerequisites
To build and run this project, you need:
* **Compiler**: A C++ compiler supporting C++11 or later (e.g., GCC, Clang, or MSVC).
* **Standard Libraries**: `<iostream>`, `<vector>`, `<string>`, `<fstream>`, and `<sstream>`.
* **Documentation Tool**: [Doxygen](https://www.doxygen.nl/) (optional, if you wish to regenerate the `refman.pdf` file).

## Installation & Usage

### 1. Clone the Repository
```bash
git clone [https://github.com/juliao876/graph-coloring.git](https://github.com/juliao876/graph-coloring.git)
cd graph-coloring
