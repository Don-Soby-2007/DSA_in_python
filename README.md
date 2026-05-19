# DSA in Python

This repository is a practice-based collection of Python notebooks for learning Data Structures and Algorithms. Each notebook focuses on one topic and contains handwritten implementations, small examples, and basic operations to help understand how the structure or algorithm works.

Repo link: `https://github.com/Don-Soby-2007/DSA_in_python`

## What this repo contains

This repo covers:

- Arrays and basic array operations
- Singly linked lists
- Doubly linked lists
- Stacks
- Queues
- Recursion
- Linear search and binary search
- Bubble sort, selection sort, and insertion sort
- Merge sort
- Quick sort
- Trees and binary search trees
- Heaps and heap sort

The notebooks are written for learning by implementation, so most topics are built from scratch instead of relying on Python libraries.

## Notebook guide

### `array.ipynb`

Introduces basic array/list operations in Python such as:

- printing elements
- inserting values
- removing elements with `pop()`
- finding maximum and minimum values manually

This is the starting point for understanding how sequence-based data is stored and manipulated.

### `LinkedList.ipynb`

Implements a singly linked list using custom `Node` and `LinkedList` classes. It includes:

- append
- insert at position
- delete by value
- pop from left and right
- reverse
- remove duplicates
- find the middle node
- display/traversal

### `Doubly_LinkedList.ipynb`

Implements a doubly linked list where each node stores both `next` and `prev` references. It includes:

- building a linked list from an array
- append on left and right
- pop on left and right
- delete by value
- reverse
- insert at a position

This notebook helps show how two-way traversal is different from a normal linked list.

### `Stack.ipynb`

Implements a stack using linked-list nodes. It covers:

- `push()`
- `pop()`
- `peek()`
- checking if the stack is empty
- tracking stack size

This notebook demonstrates the LIFO principle: Last In, First Out.

### `Queue.ipynb`

Contains two queue implementations:

- circular queue using a fixed-size array
- circular linked queue using nodes

Operations include:

- enqueue
- dequeue
- empty/full checks
- peek for the linked version

This notebook is useful for understanding FIFO behavior: First In, First Out.

### `Recursion.ipynb`

Shows recursive problem solving with examples such as:

- factorial
- Fibonacci with memoization
- recursive binary search

This notebook demonstrates how a function can call itself and how memoization improves repeated recursive work.

### `Linear&Binary_serach.ipynb`

Covers searching techniques, including:

- linear search
- binary search
- finding a single non-repeating element in a sorted array
- finding a missing number using binary-search logic

This notebook compares simple sequential search with faster search on sorted data.

### `Bubble_Selection_Insertion_Sort.ipynb`

Focuses on simple comparison-based sorting methods. The notebook includes implementations for:

- bubble sort
- insertion sort

These are good beginner sorting algorithms because they are easy to trace step by step. The filename also indicates selection sort as part of the topic area.

### `Merge_Sort.ipynb`

Implements merge sort using:

- a `merge()` helper
- a recursive `mergeSort()` function

This notebook demonstrates divide-and-conquer sorting with stable merging.

### `Quick_Sort.ipynb`

Implements quick sort and shows two partition strategies:

- Hoare partition
- Lomuto partition

The recursive sorter uses the partition result to sort subarrays efficiently.

### `Tree.ipynb`

Builds a binary search tree from scratch and explores traversal techniques. It includes:

- recursive insertion
- iterative insertion helper
- search in BST
- tree display
- preorder, inorder, and postorder traversals
- iterative traversals
- level-order traversal
- BST deletion logic

This is one of the broadest notebooks in the repo because it combines structure, traversal, and modification.

### `Heaps.ipynb`

Implements both:

- min heap
- max heap

It covers:

- insert
- bubble up
- bubble down
- extract minimum
- heapify
- heap sort with max heap

This notebook shows how heaps are stored in arrays and how parent-child index relationships work.

## Basic idea of the data structures and algorithms in this repo

### Array

An array or Python list stores items in contiguous order and allows direct access by index. It is simple and fast for reading values, but inserting or deleting in the middle can be costly because elements may need to shift.

### Linked List

A linked list stores data in nodes connected by pointers. It is useful when you want flexible insertion and deletion without shifting many elements. A singly linked list only moves forward, while a doubly linked list can move in both directions.

### Stack

A stack follows `LIFO`:

- the last item added is the first one removed

Common uses include undo operations, expression evaluation, and recursion support.

### Queue

A queue follows `FIFO`:

- the first item added is the first one removed

Queues are useful in scheduling, buffering, and breadth-first style processing.

### Tree / Binary Search Tree

A tree organizes data hierarchically. In a Binary Search Tree, values smaller than a node go to the left and larger values go to the right. This makes searching, inserting, and deleting more efficient when the tree is well shaped.

### Heap

A heap is a special tree usually stored in an array. A min heap keeps the smallest element at the top, while a max heap keeps the largest at the top. Heaps are useful for priority queues and sorting.

### Recursion

Recursion is a method where a function solves a problem by calling itself on a smaller version of that problem. It is especially useful for trees, divide-and-conquer algorithms, and mathematical definitions.

### Searching

- Linear search checks elements one by one.
- Binary search repeatedly cuts the search space in half, but it works correctly only on sorted data.

### Sorting

- Bubble sort repeatedly swaps adjacent out-of-order values.
- Insertion sort grows a sorted portion one item at a time.
- Merge sort splits the array, sorts each side, and merges them.
- Quick sort chooses a pivot and partitions around it.
- Heap sort uses heap structure to repeatedly place the largest value in its final position.

## How to use this repo

### Option 1: Open locally with Jupyter

1. Clone the repository:

```bash
git clone https://github.com/Don-Soby-2007/DSA_in_python.git
cd DSA_in_python
```

2. Start Jupyter Notebook:

```bash
jupyter notebook
```

3. Open any `.ipynb` file and run the cells.

### Option 2: Open in VS Code

1. Clone the repository.
2. Open the folder in VS Code.
3. Install the Python and Jupyter extensions if needed.
4. Open any notebook and run it cell by cell.

## How to fork this repo

If you want your own copy on GitHub:

1. Open the repository on GitHub:
   `https://github.com/Don-Soby-2007/DSA_in_python`
2. Click the `Fork` button in the top-right corner.
3. Choose your GitHub account.
4. GitHub will create a copy under your profile.

After forking, clone your own fork with:

```bash
git clone https://github.com/<your-username>/DSA_in_python.git
cd DSA_in_python
```

## Who this repo is for

This repository is useful for:

- beginners learning DSA in Python
- students practicing interview-style concepts
- anyone who wants notebook-based examples instead of only theory

## Notes

- The repository is notebook-based, so the best way to explore it is topic by topic.
- Some notebooks are focused on implementations more than explanation text.
- The file `Linear&Binary_serach.ipynb` keeps the original filename used in the repo.

## Contributing

If you fork this repository, you can:

- improve explanations
- add more test examples
- add time and space complexity notes
- expand the missing topics in future notebooks

## Author

Created by Don Soby.
