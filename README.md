# heap-sort-
Heap Sort Algorithm Implementation In Python

Heap sort is a sorting technique based upon heap data structure. It makes use of a binary heap for sorting the elements. Heapsort is a comparison-based sorting algorithm. It is an inplace sorting technique. Heapsort is not a stable algorithm.

To implement heapsort, we make use of either min-heap or max-heap. We create a min-heap or a max-heap out of the given array elements and the root node is either the minimum or the maximum element respectively. In every iteration, we delete the root node and store it in the sorted array. Thus, the heapsort algorithm is somewhat similar to the selection sort. In selection sort as well, we used to select the minimum element and insert it into the sorted array.

Heapsort involves mainly two steps to be performed:

1. Building a max-heap or min-heap using the elements of the given array.
2. Deleting the root node of the heap formed in every iteration.

What is a Binary Heap?
A binary heap is a complete binary tree. This means that every node can have at most two elements and the elements are filled in the nodes from left to right. In a complete binary tree, we cannot move to the next node for inserting elements until the previous node is full in its capacity.

A binary heap can be of two types:

1. Min-heap: In a min-heap, the value of the parent node is smaller than both of its children nodes.

2. Max-heap: In a max-heap, the value of the parent node is greater than both of its children nodes.

