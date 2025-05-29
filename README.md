# Interactive Binary Search Tree (BST) Program in C

## Overview

This project implements a Binary Search Tree (BST) in C with a text-based interface. Users can insert values, search for specific nodes, and view the tree contents using an in-order traversal.

## Features

- Insert integers into a BST
- Search for specific integers
- Display the tree using in-order traversal
- Interactive console menu
- Dynamic memory management
- Clean modular design (separated into `bst` and `io` components)

## File Structure

- `main.c` — Entry point; handles menu logic and user interaction.
- `io.c` / `io.h` — Contains input/output helper functions.
- `bst.c` / `bst.h` — Implements BST structure and functions (Insert, Search, Traverse).
