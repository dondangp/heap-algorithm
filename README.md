# MinHeap Data Structure

## Methods
### build_min_heap(data): Constructs the heap from a given array of elements.
### heapify(i): Ensures the heap property is maintained starting from index i.
### insert(value): Adds a new element to the heap and reorders the heap to maintain its property.
### pop(): Removes and returns the root node (minimum element) and restores heap order.
### peek(): Returns the root node without removing it.
### is_empty(): Checks if the heap is empty

## Examples
### Input
data = [9, 5, 6, 2, 3, 1, 7]
### Output
Initial heap: [1, 2, 6, 5, 3, 9, 7]
Popped element: 1
Heap after pop: [2, 3, 6, 5, 7, 9]
Heap after insertions: [2, 3, 4, 5, 7, 9, 6, 8]
Peek at root: 2
Popped element: 2
Heap: [3, 5, 4, 8, 7, 9, 6]
Popped element: 3
Heap: [4, 5, 6, 8, 7, 9]
Popped element: 4
Heap: [5, 7, 6, 8, 9]
Popped element: 5
Heap: [6, 7, 9, 8]
Popped element: 6
Heap: [7, 8, 9]
Popped element: 7
Heap: [8, 9]
Popped element: 8
Heap: [9]
Popped element: 9
Heap: []
