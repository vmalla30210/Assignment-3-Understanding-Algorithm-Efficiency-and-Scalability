Overview
This repository contains implementations and analyses of two key algorithms: Randomized Quicksort and Hashing with Chaining. The assignment explores the efficiency and scalability of these algorithms through theoretical analysis and empirical testing.

Files
randomized_quicksort.py: Contains the implementation of the Randomized Quicksort algorithm.
deterministic_quicksort.py: Contains the implementation of the Deterministic Quicksort algorithm.
hash_table.py: Contains the implementation of the Hash Table with Chaining.
Report.pdf: A detailed report on the theoretical and empirical analysis of the algorithms.
Getting Started
To run the code and conduct the analyses, follow these steps:

Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/algorithm-efficiency.git
cd algorithm-efficiency
Run Randomized Quicksort and Deterministic Quicksort:

Open a terminal and navigate to the directory containing randomized_quicksort.py and deterministic_quicksort.py.

You can run the implementations by executing:

bash
Copy code
python randomized_quicksort.py
python deterministic_quicksort.py
The scripts will output timing results for both sorting algorithms across different types of input arrays.

Run Hash Table with Chaining:

Open a terminal and navigate to the directory containing hash_table.py.

You can test the hash table operations (insert, search, delete) by executing:



python hash.py
The script will demonstrate the functionality of the hash table and its performance.

Summary of Findings
Randomized Quicksort vs. Deterministic Quicksort:

Randomized Quicksort generally performs better in scenarios where Deterministic Quicksort may encounter worst-case performance, such as sorted or reverse-sorted arrays. The empirical results confirm the theoretical expectation that Randomized Quicksort has a more predictable average performance due to its random pivot selection.
Hashing with Chaining:

Hashing with Chaining provides an efficient method for handling collisions in hash tables. The performance of operations is closely tied to the load factor, with dynamic resizing being a key strategy for maintaining efficiency.
