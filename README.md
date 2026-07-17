# 🌳 Binary Search Tree in C#

A complete **Binary Search Tree (BST)** implementation built from scratch in **C#**.

This project was developed to deepen my understanding of **data structures**, **recursion**, **tree traversal algorithms**, and **object-oriented programming** by implementing every operation manually without using built-in tree collections.

---

## 📌 Features

- ✅ Insert nodes
- ✅ Remove nodes
- ✅ Search for values (`Contains`)
- ✅ Clear the tree
- ✅ Count stored nodes
- ✅ Calculate tree height
- ✅ Tree visualization in the console
- ✅ In-Order Traversal
- ✅ Pre-Order Traversal
- ✅ Post-Order Traversal
- ✅ NUnit Unit Tests

---

## 🌲 Tree Structure Example

```text
        50
      /    \
    30      80
   /  \    /  \
 20   40 70   90
```

---

## 📖 Implemented Algorithms

### Insert

Adds a new value while preserving the Binary Search Tree property.

Time Complexity:

| Best | Average | Worst |
|------|---------|--------|
| O(log n) | O(log n) | O(n) |

---

### Remove

Supports all removal cases:

- Leaf node
- Node with one child
- Node with two children (using the in-order successor)

Time Complexity:

| Best | Average | Worst |
|------|---------|--------|
| O(log n) | O(log n) | O(n) |

---

### Search

Efficient recursive search using BST ordering.

Time Complexity:

| Best | Average | Worst |
|------|---------|--------|
| O(log n) | O(log n) | O(n) |

---

### Tree Traversals

#### In-Order (Left → Root → Right)

Returns the values in **sorted order**.

Example:

```text
20 30 40 50 70 80 90
```

---

#### Pre-Order (Root → Left → Right)

Useful for copying or serializing a tree.

---

#### Post-Order (Left → Right → Root)

Useful when deleting an entire tree.

---

### Height

Calculates the maximum depth of the tree recursively.

---

### Print Tree

Displays the tree structure directly in the console.

Example:

```text
│   │   ┌── 100
│   ┌── 99
│   │   └── 90
┌── 88
│       ┌── 77
│   └── 70
50
│       ┌── 49
│   └── 48
│       └── 37
```

---

## 🧪 Unit Tests

This project includes **NUnit** tests covering:

- Insert
- Remove
- Contains
- Height
- Clear
- Count
- Tree Traversals

---

## 🛠 Technologies

- C#
- .NET
- NUnit

---

## 📂 Project Structure

```text
BinarySearchTree
│
├── BinarySearchTree.cs
├── Program.cs
└── BinarySearchTree.Tests
```

---

## 🎯 Learning Objectives

The main goal of this project was to practice:

- Binary Search Trees
- Recursive algorithms
- Tree traversals
- Object-Oriented Programming
- Time complexity analysis
- Unit testing with NUnit

---

## 🚀 Future Improvements

Some features intentionally left for future implementations:

- Generic Binary Search Tree (`BinarySearchTree<T>`)
- Level Order Traversal (BFS)
- AVL Tree
- Red-Black Tree
- Tree balancing
- Lowest Common Ancestor
- Diameter of a Tree

---

## 👨‍💻 Author

**Thiago Santiago**

Computer Science student passionate about Software Engineering, Data Structures, Algorithms, and Backend Development.

GitHub:
https://github.com/Thaysantzs
