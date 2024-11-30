# Hash Tables: BST-Based and Cuckoo Hashing Implementations

This section of the repository focuses on the implementation and analysis of hash tables using Binary Search Trees (BST) for collision resolution and Cuckoo Hashing in C++. We have developed both methods and thoroughly tested their performance.

## Data Structures

The data structures implemented in this repository include:

- **Hash Table with BST (Separate Chaining)**: Uses a hash table where each bucket is a Binary Search Tree to handle collisions, allowing efficient storage and retrieval.

- **Cuckoo Hashing**: Implements the cuckoo hashing algorithm with three hash functions and multiple hash tables, providing constant time complexity for search operations under ideal conditions.

## Code

The code includes:

- **`KeyValuePair`**: A class representing a key-value pair.

- **`TreeNode`**: A struct for nodes in the BST.

- **`ListBST`**: Implements a Binary Search Tree used in the hash table buckets for separate chaining.

- **`HashBST`**: A hash table class that uses BSTs in each bucket.

- **`CuckooHash`**: Implements the cuckoo hashing algorithm with multiple hash functions and rehashing strategies.

- **`Hash`**: An abstract base class defining the interface for hash tables.

- **`Scanner`**: A class to read key-value pairs from a file and insert them into the hash tables.

- **Main Program**: Provides a user interface to select between the two hash table implementations and perform operations such as insert, find, remove, and print the table. It also includes performance tests.

## Experiments

Our examination covers:

- **Performance Timing**: Measured the time taken for insertion, search, and deletion operations in both hash table implementations.

- **Load Factor Analysis**: Investigated how different load factors affect performance and when rehashing occurs.

- **Collision Resolution Efficiency**: Compared the effectiveness of BSTs and cuckoo hashing in handling collisions.

## Results and Report

Findings and analyses are compiled into the `HashTables_BST_and_CuckooHashing_Report.pdf`, which includes:

- Detailed explanations of the hashing techniques and collision resolution strategies.

- Graphs and charts demonstrating performance metrics under various conditions.

- Comparative analysis highlighting the strengths and weaknesses of each implementation.

The report offers insights into the practical considerations of choosing appropriate hashing techniques based on application requirements.

**Note**: This project emphasizes the importance of efficient data storage and retrieval mechanisms. All experiments are conducted methodically to ensure reliable and meaningful results.
