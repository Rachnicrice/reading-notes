# Linked-Lists

## WHAT

A linked list is a data structure where one node will point to it's following node. Unlike an array, it's order is not set by it's physical location in memory.

## HOW

A linked list is implemented by first creating a 'head' node that denotes the start of the list. Then point the head node at the following element in the list, and point the following element at it's follwing element and so on, until the last node in the sequence points at null.

## WHY

Linked lists are preferable to arrays when quick lookup (i.e. lookup by index) is not necessary. They are also preferred when you don't know the size of the data you or storing or if the data size may grow over time. Most notably linked lists also allow for constant time insertion/deletion from the front of the list (or from both ends of a doubly-linked list).