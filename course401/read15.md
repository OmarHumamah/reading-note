# Trees

## What are Binary Trees ?

- A binary tree is a tree data structure comprising of nodes with at most two children i.e. a right and left child. The node at the top is referred to as the root.

- They are used for searching and sorting as they provide a means to store data hierarchically. Some common operations that can be conducted on binary trees include insertion, deletion, and traversal.

## Terminology

- `Node`: A Tree node is a component which may contain it’s own values, and references to other nodes
- `Root`: The root is the node at the beginning of the tree
- `K`: A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, k = 2.
- `Left`: A reference to one child node, in a binary tree
- `Right`: A reference to the other child node, in a binary tree
- `Edge`: The edge in a tree is the link between a parent and child node
- `Leaf`: A leaf is a node that does not have any children
- `Height`: The height of a tree is the number of edges from the root to the furthest leaf

## Traversal methods in Binary Trees

1. Depth First
   - Depth first traversal is where we prioritize going through the depth (height) of the tree first. There are multiple ways to carry out depth first traversal, and each method changes the order in which we search/print the root.
     - Pre-order: root >> left >> right
     - In-order: left >> root >> right
     - Post-order: left >> right >> root
2. Breadth First
   - Breadth first traversal iterates through the tree by going through each level of the tree node-by-node.


