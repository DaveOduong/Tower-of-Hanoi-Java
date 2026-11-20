# Tower of Hanoi – Java

A Java implementation of the Tower of Hanoi puzzle using recursion. The program demonstrates how disks can be moved from one rod to another while following the rules of the puzzle.

## Description

The Tower of Hanoi is a mathematical puzzle consisting of three rods and a number of disks of different sizes. The objective is to move all disks from the source rod to the destination rod using the auxiliary rod.

The program uses a recursive method to print the sequence of moves required to solve the puzzle.

## Rules

- Only one disk can be moved at a time.
- Only the top disk of a rod can be moved.
- A larger disk cannot be placed on top of a smaller disk.

## How It Works

The recursive method follows three steps:

1. Move `n - 1` disks from the source rod to the auxiliary rod.
2. Move the largest disk from the source rod to the destination rod.
3. Move `n - 1` disks from the auxiliary rod to the destination rod.

## How to Run

1. Ensure Java (JDK) is installed.
2. Save the code in a file named `TowerOfHanoi.java`.
3. Open a terminal in the directory where the file is saved.
4. Compile the program:

   ```bash
   javac TowerOfHanoi.java
   ```

5. Run the program:

   ```bash
   java TowerOfHanoi
   ```

## Sample Output

```text
Move disk 1 from A to C
Move disk 2 from A to B
Move disk 1 from C to B
Move disk 3 from A to C
Move disk 1 from B to A
Move disk 2 from B to C
Move disk 1 from A to C
```

## Time Complexity

- **O(2^n)** – The number of moves grows exponentially with the number of disks.

## Space Complexity

- **O(n)** – Due to the recursive call stack.

## Technologies Used

- Java
- Recursion

## Author

Created as a Java programming exercise demonstrating recursion and problem-solving.
