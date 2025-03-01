- **Date**: Nov-25-2024
- **Tags**: #ComputerScience #Lists #Class351

## **Summary**
A brief explanation or overview of the topic. 
E.g., "This note explains the basics of Binary Search Trees, their properties, and implementation."

---

## **Key Concepts**
- **Definition**: What is it? Why is it important?
  - Example: A Binary Search Tree is a node-based data structure that stores elements in sorted order for efficient lookups.
- **Key Properties**:
  - Example: Each node has at most two children. The left subtree contains only nodes with values less than the node, etc.

---

## **Code Snippets**
```java
// Example: Binary Search Tree Insert
class Node {
    int data;
    Node left, right;
    public Node(int item) {
        data = item;
        left = right = null;
    }
}
