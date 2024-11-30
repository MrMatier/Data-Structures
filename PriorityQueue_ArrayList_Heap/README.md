# Priority Queue Implementations: Dynamic Array vs Heap

This section of the repository is dedicated to the study and comparison of priority queue implementations using dynamic arrays and heaps in C++. We have implemented both data structures and rigorously tested their performance characteristics.

## Data Structures

The data structures implemented in this repository include:

- **Priority Queue using Dynamic Array**: Utilizes a dynamic array (`ArrayList`) to store elements along with their priorities. Elements are inserted in order to maintain the priority sequence.

- **Priority Queue using Heap**: Implements a max-heap to efficiently manage elements based on their priorities, ensuring optimal time complexity for insertion and extraction operations.

## Code

The code includes:

- **`PQAL_element`**: A template class representing an element with a value and priority.

- **`ArrayList`**: A template class for a dynamic array that resizes as elements are added.

- **`PriorityQueueArrayList`**: Implements a priority queue using the dynamic array, maintaining elements in sorted order based on priority.

- **`Heap`**: A template class implementing a max-heap for the priority queue.

- **`PriorityQueue`**: An abstract base class defining the interface for priority queues.

- **Main Program**: Provides a user interface to select between the two implementations and perform operations such as insert, extract max, find max, modify key, and get queue size. It also measures and compares the performance of these operations.

## Experiments

Our examination covers:

- **Performance Timing**: Measured the time taken for various operations in both implementations to gauge efficiency.

- **Complexity Analysis**: Conducted both theoretical and empirical analyses to understand the computational complexities.

- **Operation Efficiency**: Evaluated how each implementation performs under different workloads and data sizes.

## Results and Report

Findings and analyses are compiled into the `PriorityQueue_Array_vs_Heap_Report.pdf`, which includes:

- An in-depth discussion of the experimental design and testing procedures.

- Visual graphs and charts illustrating the performance of both implementations across various metrics.

- A comprehensive exploration of the complexities associated with each data structure, contrasting theoretical predictions with actual measured performance.

The report provides a complete narrative from conceptual understanding to practical implications, reflecting the collaborative efforts made in studying these data structures.

**Note**: This repository section is a culmination of joint work with a lab partner, demonstrating the collaborative spirit of scientific inquiry. All tests and benchmarks are conducted with a focus on transparency and academic rigor.
