# Edmonds-Karp Algorithm: Max-Flow Min-Cut Implementation in Python & C++

![Edmonds-Karp Algorithm](https://img.shields.io/badge/Algorithm-Visualization-blue?style=flat-square) ![Python](https://img.shields.io/badge/Python-3.8%2B-yellowgreen?style=flat-square) ![C++](https://img.shields.io/badge/C%2B%2B-11%2B-orange?style=flat-square)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Visualizations](#visualizations)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Releases](#releases)

## Overview

The **Edmonds-Karp Algorithm** is a specific implementation of the Ford-Fulkerson method for computing the maximum flow in a flow network. This repository provides a clear and efficient implementation in both Python and C++. The Python version enhances understanding through interactive visualizations using the `networkx` library.

## Features

- **Two Implementations**: Explore the algorithm in both Python and C++.
- **Interactive Visualizations**: Visualize augmenting paths and flow updates.
- **Graph Theory**: Understand concepts of max-flow and min-cut.
- **Data Structures**: Learn how graphs are represented and manipulated.
- **Comprehensive Examples**: Gain insights through practical examples.

## Installation

To get started, clone the repository using the following command:

```bash
git clone https://github.com/unter927/Edmonds-Karp-Algorithm.git
```

### Python Dependencies

For the Python implementation, ensure you have the following packages installed:

```bash
pip install networkx matplotlib
```

### C++ Dependencies

For the C++ implementation, make sure you have a compatible compiler, such as g++.

## Usage

### Python

To run the Python implementation, navigate to the `python` directory and execute:

```bash
python edmonds_karp.py
```

### C++

To compile and run the C++ implementation, navigate to the `cpp` directory and execute:

```bash
g++ edmonds_karp.cpp -o edmonds_karp
./edmonds_karp
```

## Visualizations

The interactive visualizations in the Python version allow users to see how the algorithm processes the flow network. 

- **Augmenting Paths**: Users can visualize how the algorithm finds paths with available capacity.
- **Flow Updates**: Observe how the flow changes as the algorithm progresses.

### Screenshot

![Visualization Example](https://example.com/visualization_example.png)

## Examples

### Example 1: Simple Flow Network

This example demonstrates a basic flow network with three nodes. The following graph represents the network:

```
A --(10)--> B
A --(5)--> C
B --(15)--> C
```

To run this example, modify the input in the `edmonds_karp.py` file as follows:

```python
# Define the graph here
```

### Example 2: Complex Flow Network

In this example, we create a more complex flow network with multiple paths and capacities. The following graph illustrates this:

```
A --(20)--> B --(10)--> C
A --(5)--> D --(15)--> C
```

### Running the Examples

To run the examples, simply execute the script in the respective directories.

## Contributing

We welcome contributions to enhance this project. Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Push your branch and create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, please reach out via GitHub issues or directly at [your_email@example.com](mailto:your_email@example.com).

## Releases

For the latest releases, visit the [Releases section](https://github.com/unter927/Edmonds-Karp-Algorithm/releases). Download the files and execute them as needed.

### Important Links

- [View Releases](https://github.com/unter927/Edmonds-Karp-Algorithm/releases)

Explore the project and discover how the Edmonds-Karp algorithm works through both coding and visualization. Enjoy your journey into the world of algorithms!

![Flow Network](https://example.com/flow_network.png)