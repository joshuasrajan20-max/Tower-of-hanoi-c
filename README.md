# Tower of Hanoi (C)

This project implements the Tower of Hanoi problem using recursion in C.

# Description
The Tower of Hanoi is a classic problem where disks must be moved from one rod to another while following specific rules. The program recursively solves the problem by breaking it into smaller subproblems.

To move n disks:
- Move n-1 disks from source to helper
- Move the largest disk to destination
- Move n-1 disks from helper to destination

# Rules
- Only one disk can be moved at a time
- A larger disk cannot be placed on a smaller disk
- Only the top disk of a rod can be moved

# Features
- Displays step-by-step movement of disks
- Uses recursion to solve the problem efficiently
- Simple and easy-to-understand implementation

# Concepts Used
- Recursion
- Functions
- Problem-solving

# Example
Input: n = 3  

Output:
A ---> C  
A ---> B  
C ---> B  
A ---> C  
B ---> A  
B ---> C  
A ---> C
