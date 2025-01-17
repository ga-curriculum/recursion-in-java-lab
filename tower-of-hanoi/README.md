<h1>
  <span class="headline">Recursion in Java Lab</span>
  <span class="subhead">Tower of Hanoi</span>
</h1>

## Objective
Write a function to provide the quickest way to complete Tower of Hanoi game with any number of disks using recursion technique.

## Requirements
The **Tower of Hanoi** is a classic problem in computer science. You are given three rods (A, B, and C) and \( n \) disks of different sizes, initially stacked on rod A in decreasing order of size (smallest on top). The task is to move all \( n \) disks to rod C, using rod B as an auxiliary rod, while following these rules:

1. Only one disk can be moved at a time.
2. A disk can only be placed on top of another disk only if it is smaller than the disk below it.

Your task is to must implement a **recursive solution** to print the sequence of moves needed to solve the Tower of Hanoi for a given number of disks.

- Use the `TowerOfHanoi` class in the starter code.
- Create a recursive method `solveHanoi(int n, char source, char target, char auxiliary)` in a class `TowerOfHanoi`.
- \( n \) is the number of disks.
- `source`, `target`, and `auxiliary` represent the rods (A, B, and C, respectively).
- Print the moves in the format: `"Move disk X from Y to Z"`.
- The starter code includes a set of tests to help you verify your work. To run the tests, right-click on the `TowerOfHanoiTest` class in the `src/test/java` directory and select **Run 'All Tests'**.

### Example inputs and expected outputs
Input: \( n = 2 \)  
Expected Output:
```
Move disk 1 from A to B
Move disk 2 from A to C
Move disk 1 from B to C
```

Input: \( n = 3 \)  
Expected Output:
```
Move disk 1 from A to C
Move disk 2 from A to B
Move disk 1 from C to B
Move disk 3 from A to C
Move disk 1 from B to A
Move disk 2 from B to C
Move disk 1 from A to C
```


## Practical relevance
This exercise will help you understand recursive problem-solving strategies and managing state across function calls.
