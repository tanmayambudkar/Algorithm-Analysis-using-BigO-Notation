# Aim:

To study Algorithm Analysis using Big O Notation.

# Theory:

Big O Notation is a mathematical concept used in computer science to describe the time complexity or space complexity of algorithms.
It expresses the upper bound of an algorithm’s growth rate, indicating how its performance (time or space) increases with the size of the input.

It describes the asymptotic behavior (the order of growth of time or space with respect to input size), not the exact execution time.
Big O helps to compare the efficiency of different algorithms and data structures.
It focuses mainly on the worst-case scenario to determine how efficiently an algorithm performs.

It is denoted as O(f(n)), where f(n) represents the number of operations (steps) an algorithm takes to solve a problem of size n.

<img width="850" height="250" alt="image" src="https://github.com/user-attachments/assets/1a25e40b-81c5-4dc5-a95a-a37f5b622563" />

<ins>Importance of Big O Notation</ins>:

Big O Notation is a mathematical tool used to determine the upper bound on the time or space taken by an algorithm.
It allows us to compare algorithm performance, understand scalability, and predict how algorithms behave as input size grows.

Big O Notation is important because:

+ It helps analyze the efficiency of algorithms.

+ It describes how runtime or space changes as input increases.

+ It allows programmers to compare and choose the most efficient algorithm for a problem.

+ It aids in understanding the scalability and performance of algorithms for large inputs.

+ It enables developers to optimize code and improve overall performance.

Properties of Big O Notation

Below are the key properties of Big O Notation:

1. Reflexivity
For any function f(n), f(n) = O(f(n)).
Example:
If f(n) = n², then f(n) = O(n²).

2. Transitivity
If f(n) = O(g(n)) and g(n) = O(h(n)), then f(n) = O(h(n)).
Example:
If f(n) = n², g(n) = n³, and h(n) = n⁴, then f(n) = O(h(n)).

3. Constant Factor
For any constant c > 0, if f(n) = O(g(n)), then c·f(n) = O(g(n)).
Example:
If f(n) = n and g(n) = n², then 2f(n) = O(g(n)).

4. Sum Rule
If f(n) = O(g(n)) and h(n) = O(k(n)), then f(n) + h(n) = O(max(g(n), k(n))).
When combining complexities, the largest term dominates.
Example:
If f(n) = n² and h(n) = n³, then f(n) + h(n) = O(n³).

5. Product Rule
If f(n) = O(g(n)) and h(n) = O(k(n)), then f(n) * h(n) = O(g(n) * k(n)).
Example:
If f(n) = n, g(n) = n², h(n) = n³, and k(n) = n⁴, then f(n) * h(n) = O(n⁶).

6. Composition Rule
If f(n) = O(g(n)), then f(h(n)) = O(g(h(n))).

<ins>Common Big-O Notations</ins>

Big O notation measures the time or space complexity of algorithms in the worst-case scenario.
Below are some common types of time complexities:

+ Constant Time Complexity: O(1)
Execution time remains constant regardless of input size.

+ Logarithmic Time Complexity: O(log n)
Execution time increases logarithmically with input size (e.g., Binary Search).

+ Linear Time Complexity: O(n)
Execution time increases linearly with input size (e.g., Traversing a list).

+ Quadratic Time Complexity: O(n²)
Execution time increases proportionally to the square of the input size (e.g., Nested loops).

+ Cubic Time Complexity: O(n³)
Execution time increases with the cube of the input size.

+ Polynomial Time Complexity: O(nᵏ)
Time complexity expressed as a polynomial function of n, where k is a constant.
Algorithms with polynomial complexity are generally efficient, such as O(n), O(n²), or O(n³).

+ Exponential Time Complexity: O(2ⁿ)
Execution time doubles with each additional input element (e.g., recursive brute force).

+ Factorial Time Complexity: O(n!)
Execution time grows factorially with input size, often seen in permutation-based algorithms.

<img width="850" height="250" alt="image" src="https://github.com/user-attachments/assets/aed3424c-9f88-483c-ba6e-750bc2f79e2e" />
# Conclusion:

Big O Notation is a fundamental concept in algorithm analysis that describes how an algorithm’s performance scales with the input size.
It provides a mathematical framework to measure time and space complexity, focusing on the worst-case scenario.

By expressing growth rates such as O(n), O(log n), or O(n²), developers can:

+ Compare algorithms and choose the most efficient one.

+ Predict scalability and optimize performance.

+ Select suitable data structures for better system design.

Understanding Big O helps developers write efficient, scalable, and reliable code, ensuring that systems perform well as data and input sizes increase.
Its properties like reflexivity, transitivity, and composition make it a powerful analytical tool for evaluating and optimizing algorithm performance.
