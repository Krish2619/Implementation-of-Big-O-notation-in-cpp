Aim:

To demonstrate and understand different time complexities in algorithms:  
- Constant time O(1)  
- Linear time O(n)  
- Quadratic time O(n²)

Apparatus:

- C++ Programming Language  
- Standard C++ compiler (GCC, g++, etc.)  
- Concepts involved:  
  - Vectors  
  - Loops (single and nested)  
  - Functions  
  - Time Complexity analysis basics

Program Explanation:

- The program uses a vector of integers as sample data.  
- It defines three functions to illustrate different time complexities:  
  1. `getFirstElement` retrieves the first element (O(1)).  
  2. `printElements` prints all elements sequentially (O(n)).  
  3. `printPairs` prints all possible pairs using nested loops (O(n²)).  
- The main function calls each and displays the results.

Algorithm:

1. O(1) Example:  
   - Directly access and return the first element of the vector.

2. O(n) Example:  
   - Loop through the vector once, printing each element.

3. O(n²) Example:  
   - Use two nested loops to iterate over all pairs of elements.  
   - Print each pair in the format `(element1, element2)`.

Key Concepts:

- Time Complexity: A way to express how the runtime of an algorithm changes with input size.  
- O(1): Constant time, independent of input size (direct access).  
- O(n): Linear time, runtime scales directly with input size (single loop).  
- O(n²): Quadratic time, runtime scales with the square of input size (nested loops).  
- Vectors: Dynamic array structure used for storing elements.  
- Nested Loops: Key contributor to higher time complexity.

Conclusion:

This program effectively illustrates how different algorithms behave as input size grows, demonstrating constant, linear, and quadratic time complexities.  
Understanding these helps in designing efficient algorithms and predicting their performance on larger datasets.
