# Data Structures and Algorithms (DSA)

A comprehensive JavaScript implementation of fundamental data structures and algorithms with detailed explanations and exercises.

## 📚 Table of Contents

- [Overview](#overview)
- [Folder Structure](#folder-structure)
- [Topics Covered](#topics-covered)
- [Getting Started](#getting-started)
- [Topics by Directory](#topics-by-directory)
- [Key Concepts](#key-concepts)
- [Resources](#resources)
- [Contributing](#contributing)

## 🎯 Overview

This repository contains JavaScript implementations of essential data structures and algorithms commonly asked in technical interviews. Each topic includes:

- **Implementations** - Full working code examples
- **Exercises** - Practice problems to reinforce learning
- **Explanations** - Comments explaining the logic and approach

Perfect for:
- Interview preparation
- Learning fundamental computer science concepts
- Understanding time and space complexity analysis
- Building a strong programming foundation

## 📁 Folder Structure

```
DSA/
├── 00_bigO/              # Big O Notation & Complexity Analysis
├── 01_arrays/            # Array Data Structure & Problems
├── 02_hashTables/        # Hash Tables & Hashing Concepts
├── 03_linkedLists/       # Linked Lists (Singly & Doubly)
├── 04_stacks/            # Stack Data Structure
├── 05_queues/            # Queue Data Structure
├── 06_trees/             # Tree Data Structures
├── 07_graphs/            # Graph Data Structures
├── 08_recursion/         # Recursion Concepts & Problems
├── 09_sorting/           # Sorting Algorithms
├── 10_searching/         # Searching & Traversal Algorithms
├── 11_dynamicProgramming/# Dynamic Programming Techniques
└── README.md             # This file
```

## 🔍 Topics Covered

### 00_bigO - Big O Notation & Complexity Analysis
**Understanding algorithm efficiency and scalability**

| File | Description |
|------|-------------|
| `bigO_exercise.js` | Practice identifying Big O complexities |
| `bigO_exercise2.js` | Advanced Big O exercises |
| `bigORule2.js` | Simplifying Big O expressions |
| `findNemo.js` | Linear search example - O(n) |
| `findNemo2.js` | Optimized search examples |
| `logAllPairsOfArrays.js` | Nested loop example - O(n²) |
| `printAllNumbersThenAllPairSums.js` | Multiple operations - O(n) + O(n²) |
| `spaceComplexity.js` | Space complexity analysis |

**Key Concepts:**
- Time Complexity: O(1), O(n), O(n²), O(log n), O(n log n)
- Space Complexity
- Best, Average, and Worst Case Analysis

---

### 01_arrays - Arrays & Array Problems
**Working with arrays and solving common problems**

| File | Description | Problem Type |
|------|-------------|--------------|
| `arrayImplementation.js` | Custom array implementation | Data Structure |
| `arrays.js` | Array basics and operations | Fundamentals |
| `containsDuplicate.js` | Detect duplicate elements | Hash Set Problem |
| `longestWord.js` | Find longest word in array | String/Array |
| `maximumSubarray.js` | Kadane's Algorithm | DP/Optimization |
| `mergeSortedArrays.js` | Merge two sorted arrays | Two Pointer |
| `moveZeroes.js` | Move all zeros to end | In-place |
| `reverseString.js` | Reverse array/string | Two Pointer |
| `rotateArray.js` | Rotate array by k steps | Array Manipulation |
| `twoSum.js` | Find two numbers that sum to target | Hash Map |

**Key Concepts:**
- Array indexing and iteration
- Two-pointer technique
- Prefix sums and subarrays
- Time complexity: O(1) access, O(n) search/sort

---

### 02_hashTables - Hash Tables & Hashing
**Hash table implementation and hash-based problems**

| File | Description |
|------|-------------|
| `hashTableImplementation.js` | Custom hash table from scratch |
| `firstRecurringCharacter.js` | Find first repeating character |
| `firstRecurringCharacterExercise.js` | Exercise with hints |
| `hashTableExercise.js` | Hash table practice problems |
| `intro.js` | Hash table fundamentals |

**Key Concepts:**
- Hash functions
- Collision handling
- Time complexity: Average O(1), Worst O(n)
- Space-time tradeoff

---

### 03_linkedLists - Linked Lists
**Singly and doubly linked list implementations**

| File | Description |
|------|-------------|
| `linkedListImplementation.js` | Singly linked list from scratch |
| `doubleLinkedListImplementation.js` | Doubly linked list |
| `reverseLinkedList.js` | Reverse a linked list |

**Key Concepts:**
- Node structures and pointers
- Traversal and insertion
- Deletion operations
- Reversing and cycle detection

---

### 04_stacks - Stacks
**Stack data structure implementations**

| File | Description |
|------|-------------|
| `stackImplementation.js` | Stack using linked list |
| `stackArrayImplementation.js` | Stack using array |

**Key Concepts:**
- LIFO (Last-In-First-Out)
- Push and pop operations
- Applications: function calls, undo/redo, expression evaluation

---

### 05_queues - Queues
**Queue data structure implementations**

| File | Description |
|------|-------------|
| `queueImplementation.js` | Queue using linked list |
| `queueWithStacks.js` | Queue implementation using two stacks |

**Key Concepts:**
- FIFO (First-In-First-Out)
- Enqueue and dequeue operations
- Applications: breadth-first search, scheduling

---

### 06_trees - Trees
**Tree data structure implementations**

| File | Description |
|------|-------------|
| `binaryTreeImplementation.js` | Binary tree from scratch |

**Key Concepts:**
- Tree properties and terminology
- Binary trees and binary search trees
- Tree traversal methods
- Height and balance

---

### 07_graphs - Graphs
**Graph data structure and algorithms**

| File | Description |
|------|-------------|
| `graphImplementation.js` | Graph implementation (adjacency list) |
| `graphExample.js` | Example problems using graphs |

**Key Concepts:**
- Vertices and edges
- Directed and undirected graphs
- Weighted graphs
- Adjacency matrix vs adjacency list

---

### 08_recursion - Recursion
**Recursive problem-solving techniques**

| File | Description |
|------|-------------|
| `factorial.js` | Factorial calculation |
| `fibonacci.js` | Fibonacci sequence |
| `reverseString.js` | Recursive string reversal |

**Key Concepts:**
- Base case and recursive case
- Call stack management
- Tail recursion optimization
- Backtracking

---

### 09_sorting - Sorting Algorithms
**Comprehensive collection of sorting algorithms**

| Algorithm | File | Time | Space | Stable |
|-----------|------|------|-------|--------|
| Bubble Sort | `bubbleSort.js` | O(n²) | O(1) | Yes |
| Selection Sort | `selectionSort.js` | O(n²) | O(1) | No |
| Insertion Sort | `insertionSort.js` | O(n²) | O(1) | Yes |
| Merge Sort | `mergeSort.js` | O(n log n) | O(n) | Yes |
| Quick Sort | `quickSort.js` | O(n log n) | O(log n) | No |
| Heap Sort | `heapSort.js` | O(n log n) | O(1) | No |
| Counting Sort | `countingSort.js` | O(n+k) | O(k) | Yes |
| Radix Sort | `radixSort.js` | O(nk) | O(n+k) | Yes |
| Interview Q | `interviewQuestion.js` | Various | Various | - |

**Key Concepts:**
- Comparison-based sorting
- Non-comparison sorting
- In-place sorting
- Stable vs unstable sorting

---

### 10_searching - Searching & Traversal
**Search algorithms and tree/graph traversal**

| File | Description |
|------|-------------|
| `linearSearch.js` | Sequential search - O(n) |
| `binarySearch.js` | Binary search - O(log n) |
| `breadthFirstSearch.js` | BFS iterative approach |
| `breadthFirstSearchRecursive.js` | BFS recursive approach |
| `depthFirstSearch.js` | DFS traversal |
| `bfsVsDfs.js` | Comparison of BFS and DFS |
| `isValidBST.js` | Validate binary search tree |
| `traversalQuiz.js` | Tree traversal practice |

**Key Concepts:**
- Binary search conditions
- Graph traversal methods (BFS, DFS)
- Pre-order, in-order, post-order traversals
- Applications and use cases

---

### 11_dynamicProgramming - Dynamic Programming
**Optimization using dynamic programming**

| File | Description |
|------|-------------|
| `fibonacci.js` | Optimized Fibonacci with DP |
| `memoization.js` | Memoization techniques |

**Key Concepts:**
- Overlapping subproblems
- Optimal substructure
- Memoization (top-down)
- Tabulation (bottom-up)

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v12 or higher)
- Basic JavaScript knowledge
- Text editor or IDE (VS Code recommended)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/DSA.git
cd DSA
```

2. Run any JavaScript file:
```bash
node 00_bigO/findNemo.js
```

### Running Exercises

Each file is self-contained and can be run directly:

```bash
node 01_arrays/twoSum.js
node 09_sorting/mergeSort.js
node 10_searching/binarySearch.js
```

## 📖 How to Use This Repository

### For Learning:
1. Start with `00_bigO/` to understand complexity analysis
2. Move through data structures in order (arrays → hash tables → linked lists, etc.)
3. Read the comments in each file
4. Modify and test the code yourself

### For Interview Prep:
1. Review the relevant algorithm for your interview
2. Try to solve problems without looking at the solution
3. Compare your approach with the implementation
4. Focus on time and space complexity trade-offs

### For Implementation Reference:
1. Use the implementations as references for building your own solutions
2. Study different approaches to the same problem
3. Understand the trade-offs of different implementations

## 🎓 Key Concepts

### Big O Complexity Chart

| Notation | Name | Example |
|----------|------|---------|
| O(1) | Constant | Hash table lookup |
| O(log n) | Logarithmic | Binary search |
| O(n) | Linear | Simple loop |
| O(n log n) | Linearithmic | Efficient sorting |
| O(n²) | Quadratic | Nested loops |
| O(n³) | Cubic | Triple nested loops |
| O(2ⁿ) | Exponential | Recursive without memoization |
| O(n!) | Factorial | Permutations |

### When to Use Different Data Structures

| Data Structure | Best For | Worst Case |
|----------------|----------|-----------|
| Array | Random access, iteration | Insertion/deletion (middle) |
| Hash Table | Fast lookup, insertion | Worst case with collisions |
| Linked List | Insertion/deletion (beginning) | Random access |
| Stack | LIFO operations, recursion | Not suitable for search |
| Queue | FIFO operations, BFS | Not suitable for random access |
| Tree/BST | Sorted data, hierarchical | Unbalanced tree |
| Graph | Relationships, networks | Complex traversal |

## 📚 Resources

### Recommended Learning Materials:
- **Cracking the Coding Interview** by Gayle McDowell
- **Introduction to Algorithms** by Cormen, Leiserson, Rivest, Stein
- **JavaScript Algorithms** - Multiple implementations and explanations
- **Big-O Cheat Sheet** - Time and space complexity reference

### Online Platforms:
- [LeetCode](https://leetcode.com) - Practice problems
- [HackerRank](https://hackerrank.com) - Algorithm challenges
- [CodeSignal](https://codesignal.com) - Interview prep
- [GeeksforGeeks](https://geeksforgeeks.org) - Detailed explanations

## 💡 Tips for Success

1. **Understand, Don't Memorize** - Focus on understanding the "why" behind algorithms
2. **Practice Regularly** - Solve problems consistently to build muscle memory
3. **Analyze Complexity** - Always think about time and space complexity
4. **Optimize Iteratively** - Start with a working solution, then optimize
5. **Test Edge Cases** - Consider boundary conditions and special cases
6. **Explain Your Solution** - Practice explaining your approach clearly

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Add new algorithms or data structures
- Improve existing implementations
- Add more comprehensive comments
- Fix bugs or issues
- Suggest optimizations

Please ensure your code follows the existing style and includes clear comments.

## 📝 License

This project is open source and available under the MIT License.

## 📧 Contact

If you have questions or suggestions, feel free to reach out!

---

**Happy Learning! 🚀**

*Last updated: February 2026*
