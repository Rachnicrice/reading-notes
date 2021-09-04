# Trees

## WHAT

A tree is a data structure comprised of parent and child nodes where the entry point or 'top' of the tree is known as the root. A tree is a non-linear data structure.

## HOW

A tree is implemented by first creating a 'root' node which whill point to left and right 'leaf' or 'child' nodes. A binary tree is implemented by ensuring that every right child is larger than it's parent and every left node is smaller.

## WHY

A tree is a useful data structure for when you want to store information in a hierarchical fashion. Additionally certain types of trees can be better for specific search functions. For instance, an AVL tree guarentees a O(n log n) time complexity for search functions.