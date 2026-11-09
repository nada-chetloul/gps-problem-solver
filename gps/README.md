# GPS Problem Solver (C)

This project implements a **Plan Generator (GPS)** in C.  
From an initial state (facts), goals, and a set of rules (preconditions / add / delete), the program automatically generates a **sequence of actions** that achieves the goals, if a solution exists.

Two solving methods are provided:
- **simple forward chaining**,
- **forward chaining with backtracking**.

## Contents
- `main.c`: implementation of the GPS engine
- `school.txt`: example problem

## Compilation

### Linux / macOS
````bash
gcc main.c -o main
./main
````

