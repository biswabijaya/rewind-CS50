# Rewind CS50

## Overview
Welcome to the **Rewind CS50** repository! This repository is designed to help revisit key Computer Science concepts, focusing on **Sorting Algorithms, Data Structures, Searching Techniques, and Time/Space Complexity**. We will use **Go** and **Google Colab** to illustrate these concepts interactively.

## Topics Covered

### Sorting Algorithms
#### **L1 (Basic, O(n²))**
- **Bubble Sort** – Repeatedly swaps adjacent elements if they are in the wrong order.
- **Insertion Sort** – Builds a sorted array one element at a time by inserting in the correct position.
- **Selection Sort** – Repeatedly selects the smallest element and swaps it with the first unsorted element.

#### **L2 (Efficient, O(n log n))**
- **Merge Sort** – Recursively divides the array and merges sorted halves.
- **Quick Sort** – Uses a pivot to partition the array and sorts recursively.
- **Counting Sort** – Counts occurrences of elements and reconstructs the sorted array (works for limited range of integers).

#### **L3 (Advanced, Optimized for Specific Use Cases)**
- **Heap Sort** – Uses a binary heap for O(n log n) sorting.
- **Radix Sort** – Sorts numbers digit by digit.
- **Tim Sort** – Hybrid of Merge and Insertion Sort, optimized for real-world data.

#### **L4 (Specialized & Theoretical Sorting Algorithms)**
- **Shell Sort** – Optimized version of Insertion Sort.
- **Bucket Sort** – Distributes elements into multiple buckets before sorting.
- **Bitonic Sort** – A parallel sorting algorithm useful for hardware implementation.

---

### Hashing
- **Definition:** Hashing is a technique for fast data retrieval using a hash function.
- **Chaining:** A collision resolution technique storing multiple elements at the same index using a linked list.

---

### Data Structures
#### **1. Stack**
- **Array-based Stack**
- **Linked List Stack**
- **Monotonic Stack**

#### **2. Queue**
- **Simple Queue (FIFO)**
- **Circular Queue**
- **Deque (Double-Ended Queue)**
- **Priority Queue**

#### **3. Linked List**
- **Singly Linked List**
- **Doubly Linked List**
- **Circular Linked List**

#### **4. Tree**
- **Binary Tree**
- **Binary Search Tree (BST)**
- **Balanced Trees (AVL Tree, Red-Black Tree)**
- **Heap (Min Heap, Max Heap)**
- **Trie (Prefix Tree)**
- **Segment Tree / Fenwick Tree (BIT)**

#### **5. Graph**
- **Directed & Undirected Graphs**
- **Weighted & Unweighted Graphs**
- **Adjacency Matrix & List Representation**
- **Cyclic & Acyclic Graphs**

---

### Searching Techniques
#### **1. Linear Search (O(n))**
- Checks each element one by one.

#### **2. Binary Search (O(log n))**
- Works on sorted data.

#### **3. Jump Search (O(√n))**
- Efficient for sorted data.

#### **4. Interpolation Search (O(log log n) best case, O(n) worst case)**
- Works best on uniformly distributed data.

#### **5. Exponential Search (O(log n))**
- Used for unbounded or infinite-sized arrays.

#### **6. Fibonacci Search (O(log n))**
- Uses Fibonacci numbers to divide search space.

#### **7. Hashing-based Search (O(1) avg, O(n) worst)**
- Fast lookups using hash tables.

#### **8. Ternary Search (O(log n))**
- Similar to Binary Search but divides into three parts.

---

## Time and Space Complexity
### **1. Time Complexity**
- Measures how execution time grows with input size.
- **Examples:**
  - O(1) → Constant time
  - O(log n) → Logarithmic time
  - O(n) → Linear time
  - O(n²) → Quadratic time

### **2. Space Complexity**
- Measures memory usage based on input size.
- **Examples:**
  - O(1) → Constant space
  - O(n) → Linear space (storing an array of size n)
  - O(n!) → Factorial space complexity (worst-case recursive algorithms)

---

## How to Use This Repository
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/rewind-cs50.git
   cd rewind-cs50
   ```
2. Run Sorting Algorithms in **Go**:
   ```sh
   go run sorting/bubble_sort.go
   ```
3. Use **Google Colab** for interactive explanations:
   - Open `rewind_cs50_colab.ipynb`
   - Run and visualize algorithms step by step

## Contributing
Contributions are welcome! Feel free to submit pull requests with improvements or new explanations.

## License
This project is licensed under the MIT License.

---

### 🚀 Happy Learning! 🎯
