# Data Structures

🙏 Welcome to the Data Structures repository! This repository is dedicated to implementing and solving problems related to core data structures and algorithms in Javascript for the learning purposes.

## Contents

In this repository, you'll find efficient and optimized implementations of the following data structures:

- Stack
- Queue
- Deque
- LinkedList
- LinkedListNode
- DoublyLinkedList
- DoublyLinkedListNode
- Heap
- MinHeap
- MaxHeap
- PriorityQueue
- MinPriorityQueue
- MaxPriorityQueue
- BinarySearchTree
- BinarySearchTreeNode
- AVLTree
- AVLTreeNode
- Trie
- TrieNode
- Graph
- DirectedGraph

Each implementation aims to demonstrate both theoretical concepts and practical applications, including time and space complexity analyses where applicable.

## Features

- **Efficient Implementations**: All data structures are implemented using optimal algorithms to ensure high performance for real-world applications.
- **Comprehensive Explanations**: Clear explanations are provided for each data structure, its operations, and real-world use cases.
- **Well-Documented Code**: Each file is well-commented, making it easy to understand and extend the code.


## Data Structure Overview

### 1. Stack
A stack is a linear data structure that follows the LIFO (Last In, First Out) principle. Operations include:
- `push`: Add an element to the top
- `pop`: Remove and return the top element
- `peek`: Retrieve the top element without removing it

### 2. Queue
A queue is a linear data structure that follows the FIFO (First In, First Out) principle. Operations include:
- `enqueue`: Add an element to the end
- `dequeue`: Remove and return the front element
- `peek`: Retrieve the front element without removing it

### 3. Deque (Double-Ended Queue)
A deque allows insertion and removal of elements from both ends. Operations include:
- `addFront`: Insert an element at the front
- `addRear`: Insert an element at the rear
- `removeFront`: Remove an element from the front
- `removeRear`: Remove an element from the rear

### 4. EnhancedSet
A set-like data structure that ensures unique elements, but with enhancements for performance or additional features (e.g., order, priority).

### 5. LinkedList & Doubly LinkedList
A LinkedList is a linear collection of nodes where each node points to the next. A Doubly LinkedList has nodes that point to both the next and previous nodes. Key operations include:
- `insert`: Add a node at the start, end, or specific position
- `delete`: Remove a node
- `find`: Search for a node

### 6. Heap
A heap is a binary tree-based data structure that satisfies the heap property:
- **MinHeap**: The smallest element is at the root
- **MaxHeap**: The largest element is at the root

### 7. PriorityQueue
A PriorityQueue is a data structure that stores elements based on priority rather than insertion order. Can be implemented using a heap:
- **MinPriorityQueue**: The element with the lowest priority comes first
- **MaxPriorityQueue**: The element with the highest priority comes first

### 8. Binary Search Tree (BST)
A BST is a tree data structure where each node has at most two children, and the left child is less than the parent while the right child is greater. Operations include:
- `insert`: Add a node to the tree
- `delete`: Remove a node
- `search`: Find a node

### 9. AVL Tree
An AVL Tree is a self-balancing binary search tree where the height of the two child subtrees of any node differ by no more than one. This ensures operations remain efficient with O(log n) time complexity.

### 10. Trie
A Trie is a tree-like data structure that stores a dynamic set of strings where keys are usually strings. It is particularly useful for tasks like autocomplete and spell-checking.

### 11. Graph
A Graph is a collection of nodes (vertices) and edges (connections between nodes). In a Directed Graph, edges have a direction, whereas an Undirected Graph has bidirectional edges. Operations include:
- `addNode`: Add a new node
- `addEdge`: Create an edge between two nodes
- `removeNode`: Remove a node
- `removeEdge`: Remove an edge

## Contributing
Contributions are welcome! If you'd like to improve the repository, please:
- Ensure your changes are well-tested
- Adhere to the existing code style
- Provide a clear description of the problem you're solving or the feature you're adding
- Do not hesitate to suggest any new ways of implementations of the any data structures.

## Acknowledgements
This repository draws inspiration from:
- Fundamental data structure challenges
- Technical interview preparation resources
- Personal skill enhancement and learning journeys

## Thank You
If you have any questions, feel free to open an issue or reach out. Enjoy coding, and happy learning! 😊