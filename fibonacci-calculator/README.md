<h1>
  <span class="headline">Recursion in Java Lab</span>
  <span class="subhead">Fibonacci Calculator</span>
</h1>

## Objective
Write a recursive function to calculate the n-th Fibonacci number.

## Requirements
The **Fibonacci sequence** is a series of numbers where the next number is the sum of the previous two numbers. The sequence starts with:
- \( F(0) = 0 \)
- \( F(1) = 1 \)

From there:
- \( F(n) = F(n-1) + F(n-2) \) for \( n > 1 \)

Your task is to write a **recursive function** that calculates the **n-th Fibonacci number** in the sequence.
- Use the `FibonacciCalculator` class in the starter code.
- Implement a method `calculateFibonacci(int n)` in a class called `FibonacciCalculator`.
- The function should take a non-negative integer as input and return the corresponding Fibonacci number using **recursion**.
- Ensure that your implementation correctly handles base cases \( n = 0 \) and \( n = 1 \).
- The starter code includes a set of tests to help you verify your work. To run the tests, right-click on the `FibonacciCalculatorTest` class in the `src/test/java` directory and select **Run 'All Tests'**.

### Example inputs and expected outputs
| Input (n) | Expected Output |
|-----------|-----------------|
| 0         | 0               |
| 1         | 1               |
| 2         | 1               |
| 3         | 2               |
| 5         | 5               |
| 7         | 13              |
| 10        | 55              |


## Practical relevance
- This exercise will help you understand how recursion works with overlapping sub problems, a common real-world scenario.
