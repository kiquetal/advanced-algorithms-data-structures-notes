### Chapter 2

- 2.2 The problem: Handling priority

- 2.3 Solutions at hand: Keeping a sorted list

- 2.3.1 Priority queue, will keep a partiaL order of the list.

- 2.3.4 Describing the datastructure:API 

API: top(),peek(),insert(element,priority),remove(element),update(element,newPriority),size()

Contract: The top element returned by the queue is always the element with highest priority currently stored
in the list

Algorithms

Data Structure

A heap is the concrete implementation of the priority queue

2.4.1 Priority queue at work

2.4.2 Priority matters: Generalize FIFO

2.5 Concrete data structures

2.5.1 Comparing perfomance

| Operation | Unsorted array | Sorted array | Balanced tree|
| --------- | -------------- | ------------ | ------------ |
| Insert    | O(1)           | O(n)         | O(log n)     |
| Find-Minimum | O(1)        | O(1)         | O(1)         |
| Delete-Minimum | O(n)      | O(1)         | O(log n)     |




