# Python3_Data_Structures
Code from [Youtube Tutorial Series](https://www.youtube.com/playlist?list=PLEJyjB1oGzx3iTZvOVedkT8nZ2cG105U7). Each lesson begins by introducing the idea behind the data structure then, after explaining some basic concepts, moves over to coding the actual Python class. The code in this repository is all implemented in Python 3, for Python 2 see ['Python_Data_Structures'](https://github.com/bfaure/Python_Data_Structures).

## [AVL Tree (AVL_Tree)](https://www.youtube.com/watch?v=lxHF-mVdwK8)
The AVL Tree is an improvement upon the traditional Binary Search Tree (BST) that implements an auto-balancing feature, with the hopes to keep tree operations closer to O(logn) rather than O(n). After insertions and deletions that cause the tree to become unbalanced, special functions are called to manage the situation by rebalancing any nodes they find to be unbalanced. If you don't have experience with traditional BSTs you should start with the tutorial covering those.

## [Binary Search Tree Validator (BST_Validator)](https://www.youtube.com/watch?v=azupT01iC78)
The BST validator is a function whose purpose is to check whether the input BST adheres to the rules of a binary search tree, namely that for every node, the subtree rooted at its left child contains only smaller values, and the subtree rooted at its right child contains only larger values. The code for this lesson is simple once explained but is not that easy to come up with from scratch.

## [Binary_Search_Tree](https://www.youtube.com/watch?v=f5dU3xoE6ms)
The most popular data structure, the binary search tree is an intuitive way of storing sortable data that provides faster-than-linear search capabilities. Values in a BST are wrapped in a 'node' class used to link the tree together. Given a certain node 'n' with value 'v', all nodes to the right of 'n' contain values larger than 'v', and all nodes to the left contain values smaller than 'v'.

## [Linked_List](https://www.youtube.com/watch?v=JlMyYuY1aXU)
The linked list is a useful data structure providing similar functionality to an array, but in a dynamic package. Albeit, not as useful in Python as in statically typed languages, the linked list is still an interesting project to undertake. Similar to BST, values in a linked list are wrapped in an instance of a 'node' class containing a pointer, allowing the whole list to be linked together by distributed references.

