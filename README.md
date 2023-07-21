# Time Complexity Algorithm Implementations in Python

[![GitHub repo size](https://img.shields.io/github/repo-size/AbrarAmiya/time-complexity-algorithm-implementations?color=green&style=flat-square)](https://github.com/AbrarAmiya/time-complexity-algorithm-implementations)

This repository contains Python implementations of various algorithms along with explanations of their time complexities. The goal is to provide a handy reference for different types of algorithms and their behaviors.

## Algorithms Included

### 1. Constant Time Algorithm (O(1))
This algorithm performs a simple operation that takes a constant amount of time regardless of the input size.

Function: `constant_time_algo()`

#### Example Graph:

![Constant Time Graph](./images/constant_time_graph.png)

#### Application:
The constant time algorithm is often used for simple arithmetic calculations, such as adding or subtracting two numbers.

### 2. Logarithmic Time Algorithm (O(log N))
This algorithm performs a binary search on a sorted list of size N.

Function: `logarithmic_time_algo(n)`

#### Example Graph:

![Logarithmic Time Graph](./images/logarithmic_time_graph.png)

#### Application:
The logarithmic time algorithm is commonly used in various search operations, such as finding elements in a sorted list or binary tree.

### 3. Linear Time Algorithm (O(N))
This algorithm performs a simple operation on each element of the input array.

Function: `linear_time_algo(arr)`

#### Example Graph:

![Linear Time Graph](./images/linear_time_graph.png)

#### Application:
The linear time algorithm is applied in tasks like traversing a list or array, computing the sum of elements, or finding the maximum/minimum value.

### 4. N Log N Time Algorithm (O(N log N))
This algorithm sorts the input array using a sorting algorithm with O(N log N) complexity.

Function: `nlogn_time_algo(arr)`

#### Example Graph:

![N Log N Time Graph](./images/nlogn_time_graph.png)

#### Application:
Sorting algorithms with N log N complexity, such as Merge Sort and Quick Sort, are widely used for efficient data organization.

### 5. Quadratic Time Algorithm (O(N^2))
This algorithm performs nested loops where the inner loop depends on the size of N.

Function: `quadratic_time_algo(n)`

#### Example Graph:

![Quadratic Time Graph](./images/quadratic_time_graph.png)

#### Application:
Quadratic time algorithms are utilized in tasks like matrix multiplication, generating permutations, or solving certain combinatorial problems.

### 6. Cubic Time Algorithm (O(N^3))
This algorithm performs three nested loops where each loop depends on the size of N.

Function: `cubic_time_algo(n)`

#### Example Graph:

![Cubic Time Graph](./images/cubic_time_graph.png)

#### Application:
Cubic time algorithms find application in solving problems that involve three-dimensional data or nested relationships.

### 7. Polynomial Time Algorithm (O(N^K))
This algorithm performs a loop that depends on the size of N raised to the power of K.

Function: `polynomial_time_algo(n, k)`

#### Example Graph:

![Polynomial Time Graph](./images/polynomial_time_graph.png)

#### Application:
Polynomial time algorithms are used in various optimization and graph algorithms, such as the Traveling Salesman Problem.

### 8. Exponential Time Algorithm (O(2^N))
This algorithm performs a recursive operation with a branching factor of 2.

Function: `exponential_time_algo(n)`

#### Example Graph:

![Exponential Time Graph](./images/exponential_time_graph.png)

#### Application:
Exponential time algorithms are often encountered in problems related to subsets, power set generation, or exhaustive search.

## Usage

1. Clone the repository to your local machine:

```bash
git clone https://github.com/AbrarAmiya/time-complexity-algorithm-implementations.git
cd time-complexity-algorithm-implementations
