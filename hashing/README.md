Hashing

Hashing is a technique used in computer science to store, search, and retrieve data efficiently. It converts data (keys) into a fixed-size value called a hash value or hash code using a mathematical function known as a hash function.

The main purpose of hashing is to achieve very fast data access.

Need for Hashing

In traditional data structures like arrays or linked lists, searching for an element may require traversing multiple elements, which increases execution time.

Hashing overcomes this problem by directly calculating the storage location of data using a hash function.

This reduces the time required for:
- Searching
- Insertion
- Deletion
- Retrieval

Why Hashing is Used

Hashing is used because it provides:
- Fast data access
- Efficient searching
- Reduced time complexity
- Better memory organization
- Quick lookup operations

It is mainly used when large amounts of data must be processed quickly.

Advantages of Hashing

1. Fast Access
Hashing provides very fast insertion, deletion, and searching operations.

2. Efficient Searching
Data can often be found in nearly constant time.

3. Reduced Complexity
It simplifies complex searching operations.

4. Better Performance
Hashing performs better than linear searching for large datasets.

5. Efficient Data Storage
It helps organize and manage data systematically.

Disadvantages of Hashing

1. Collision Problem
Different keys may generate the same hash value.

2. Memory Usage
Some hashing methods require additional memory.

3. Poor Hash Function Issues
An inefficient hash function may reduce performance.

4. No Ordering
Hashed data is generally not stored in sorted order.

Components of Hashing

1. Key
The original data element provided as input.

2. Hash Function
A function that converts the key into a hash value.

3. Hash Table
A data structure used to store hashed values.

4. Hash Value
The index or address generated after hashing.

Hash Function

A hash function is a mathematical function that maps data to a fixed-size value.

Characteristics of a good hash function:
- Fast computation
- Uniform distribution
- Minimum collisions
- Deterministic output

Collision in Hashing

A collision occurs when two different keys produce the same hash value.

Since memory size is limited, collisions are unavoidable in most hashing systems.

Collision Resolution Techniques

1. Separate Chaining
Multiple elements are stored at the same index using linked lists.

2. Open Addressing
Another empty location is searched when collision occurs.

Types:
- Linear Probing
- Quadratic Probing
- Double Hashing

Types of Hashing

1. Static Hashing
The size of the hash table remains fixed.

2. Dynamic Hashing
The hash table size changes dynamically according to data size.

Methods of Hashing

1. Division Method
The key is divided by the table size, and the remainder becomes the index.

2. Mid Square Method
The key is squared, and middle digits are selected.

3. Folding Method
The key is divided into parts and combined.

4. Digit Analysis Method
Specific digits from the key are selected.

Load Factor

Load factor represents how full the hash table is.

Load Factor = Number of Elements / Size of Hash Table

A high load factor increases collisions.

Time Complexity of Hashing

Average Case:
- Insertion → O(1)
- Deletion → O(1)
- Searching → O(1)

Worst Case:
- O(n) when many collisions occur.

Applications of Hashing

1. Database Indexing
Used for fast record retrieval.

2. Password Security
Passwords are stored in hashed form.

3. Compiler Design
Used in symbol tables.

4. Caching
Used in cache memory systems.

5. Cryptography
Used in secure communication systems.

6. Dictionaries and Maps
Used in structures like:
- HashMap
- HashSet

Hash Table

A hash table is a data structure that stores data using key-value mapping.

It consists of:
- Keys
- Values
- Hash function
- Array structure

Hash tables provide fast access to stored information.

Rehashing

Rehashing is the process of creating a larger hash table and reinserting all elements when the table becomes too full.

It improves performance and reduces collisions.
