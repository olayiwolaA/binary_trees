# 0x1D. C - Binary trees
`C` `Group project` `Algorithm` `Data structure`
## :open_book: Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
- What is a binary tree
- What is the difference between a binary tree and a Binary Search Tree
- What is the possible gain in terms of time complexity compared to linked lists
- What are the depth, the height, the size of a binary tree
- What are the different traversal methods to go through a binary tree
- What is a complete, a full, a perfect, a balanced binary tree
## Data structures
### Basic Binary Tree
```
/**
 * struct binary_tree_s - Binary tree node
 *
 * @n: Integer stored in the node
 * @parent: Pointer to the parent node
 * @left: Pointer to the left child node
 * @right: Pointer to the right child node
 */
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;
```
### Binary Search Tree
```
typedef struct binary_tree_s bst_t;
```
### AVL Tree
```
typedef struct binary_tree_s avl_t;
```
### Max Binary Heap
```
typedef struct binary_tree_s heap_t;
```
## Tasks
### 0. New node
### 1. Insert left
### 2. Insert right
### 3. Delete
### 4. Is leaf
### 5. Is root
### 6. Pre-order traversal
### 7. In-order traversal
### 8. Post-order traversal
### 9. Height
### 10. Depth
### 11. Size
### 12. Leaves
### 13. Nodes
### 14. Balance factor
### 15. Is full
### 16. Is perfect
### 17. Sibling
### 18. Uncle

