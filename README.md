# Red-Black Tree Implementation in C++

## Overview

This project provides an implementation of a Red-Black Tree in C++. Red-Black Trees are a kind of self-balancing binary search tree, where each node contains an extra bit for denoting the color of the node, either red or black. This structure ensures that the tree remains approximately balanced, with operations such as insertion, deletion, and searching being efficient.

## Key Features

- Node Insertion: Allows for the addition of nodes while maintaining the red-black properties.
- Node Deletion: Supports the removal of nodes with adjustments to preserve tree balance.
- Search Functionality: Enables searching for a node with a specific key.
- Inorder Traversal: Provides a method to display the tree's contents in a sorted manner.
- Tree Visualization: Implements a way to visually represent the tree structure.
- Minimum and Maximum Node Retrieval: Functions to find the smallest and largest nodes in the tree.
- Successor and Predecessor Calculation: Determines a node's successor or predecessor.
- Black-Height and Tree Depth: Calculates the black-height and the overall depth of the tree.

## Implementation

### `RBNode` Structure

Defines the structure of a tree node, including its key, color, and pointers to its parent, left child, and right child.

### `RBTree` Class

Implements the Red-Black Tree with methods for insertion, deletion, left and right rotations, and other utility functions.

### I/O Handling

The `IODialog` namespace is designed for input/output operations, providing a user interface for tree operations such as adding and deleting nodes.

## Getting Started

To use this implementation:

1. Include `RBNode.h` and `IODialog.h` in your project directory.
2. Compile the project ensuring your compiler supports C++11 or later.
3. Execute the binary and follow the prompts to interact with the tree.