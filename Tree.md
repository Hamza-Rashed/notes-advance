## Hello everyone .. Today we will learn something beautiful and new in our course 401 :fire: :fire: .. Please have fun :blush: :sunglasses: :heart_eyes:

# Tree : 

![](https://camo.githubusercontent.com/75120286a949a6edb283759ff6a760da443661e721412570ff58bf50a5bf2139/68747470733a2f2f636f646566656c6c6f77732e6769746875622e696f2f636f6d6d6f6e5f637572726963756c756d2f646174615f737472756374757265735f616e645f616c676f726974686d732f436f64655f3430312f636c6173732d31352f7265736f75726365732f696d616765732f42696e61727954726565312e504e47)

Node - A node is the individual item/data that makes up the data structure

Root - The root is the first/top Node in the tree

Left Child - The node that is positioned to the left of a root or node

Right Child - The node that is positioned to the right of a root or node

Edge - The edge in a tree is the link between a parent and child node

Leaf - A leaf is a node that does not contain any children

Height - The height of a tree is determined by the number of edges from the root to the bottommost node

-Traversals

An important aspect of trees is how to traverse them. Traversing a tree allows us to search for a node, print out the contents of a tree, and much more! There are two categories of traversals when it comes to trees:

Depth First

Breadth First

-Depth First

Depth first traversal is where we prioritize going through the depth (height) of the tree first. There are multiple ways to carry out depth first traversal, and each method changes the order in which we search/print the root. Here are three methods for depth first traversal:

Pre-order: root » left » right

In-order: left » root » right

Post-order: left » right » root

-Traditionally, breadth first traversal uses a queue (instead of the call stack via recursion) to traverse the width/breadth of the tree. Let’s break down the process.

-Adding a node

Because there are no structural rules for where nodes are “supposed to go” in a binary tree, it really doesn’t matter where a new node gets placed.

One strategy for adding a new node to a binary tree is to fill all “child” spots from the top down. To do so, we would leverage the use of breadth first traversal. During the traversal, we find the first node that does not have 2 child nodes, and insert the new node as a child. We fill the child slots from left to right.

-Big O

The Big O time complexity of a Binary Search Tree’s insertion and search operations is O(h), or O(height). In the worst case, we will have to search all the way down to a leaf, which will require searching through as many nodes as the tree is tall. In a balanced (or “perfect”) tree, the height of the tree is log(n). In an unbalanced tree, the worst case height of the tree is n.

The Big O space complexity of a BST search would be O(1). During a search, we are not allocating any additional space.

![](https://camo.githubusercontent.com/2a6ce69c91919572b5ebd612484c9dc390651d259508acb5f1197779d3b3a83f/68747470733a2f2f7777772e707974686f6e2d636f757273652e65752f696d616765732f4465636973696f6e5f54726565312e706e67)
