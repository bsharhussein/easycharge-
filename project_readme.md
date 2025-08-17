# Project Overview

This project is a **C program** that demonstrates the use of fundamental data structures such as **binary search trees (BST)**, **linked lists**, and **queues**. The system manages data stored in external text files (e.g., cars, stations, ports) and provides a menu-driven interface for interaction.

The program is modular, with each data structure implemented in separate source/header files, and a central menu system for user interaction.

---

## Features

- **Binary Search Tree (BST):** Efficient storage and retrieval of structured data.
- **Linked List:** Sequential data management for dynamic collections.
- **Queue:** FIFO (First In, First Out) structure for ordered processing.
- **Menu System:** Interactive user interface to navigate program functionality.
- **External Data Files:** Predefined data sets (`Cars.txt`, `Ports.txt`, `Stations.txt`, `LineOfCars.txt`) loaded into the system.

---

## Project Structure

```
Final_324220326_215733601_214078982/
│── main.c             # Program entry point
│── menu.c / menu.h    # Menu and user interaction logic
│── BST.c / BST.h      # Binary Search Tree implementation
│── List.c / List.h    # Linked List implementation
│── Queue.c / Queue.h  # Queue implementation
│── struct.c / struct.h# Data structures and utilities
│── Cars.txt           # Example data file (cars)
│── LineOfCars.txt     # Example data file (car sequences)
│── Ports.txt          # Example data file (ports)
│── Stations.txt       # Example data file (stations)
```

---

## Requirements

- **C Compiler** (e.g., GCC or Clang)
- Standard C libraries (stdio, stdlib, etc.)

---

## How to Compile and Run

1. Navigate to the project folder:
   ```bash
   cd Final_324220326_215733601_214078982
   ```
2. Compile the program:
   ```bash
   gcc main.c menu.c BST.c List.c Queue.c struct.c -o program
   ```
3. Run the program:
   ```bash
   ./program
   ```

---

## Notes

- The program expects the data files (`Cars.txt`, `Ports.txt`, `Stations.txt`, `LineOfCars.txt`) to be in the same directory.
- Modify or replace these text files to work with different datasets.

---

## Authors

This project was developed as part of an academic assignment in C programming, focusing on data structures and file handling.

