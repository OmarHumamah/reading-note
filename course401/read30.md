# Hash Tables

## What is hash table

- Hashing is a technique that is used to uniquely identify a specific object from a group of similar objects. Some examples of how hashing is used in our lives include:
  - In universities, each student is assigned a unique roll number that can be used to retrieve information about them.
  - In libraries, each book is assigned a unique number that can be used to determine information about the book, such as its exact position in the library or the users it has been issued to etc.
- In both these examples the students and books were hashed to a unique number.

- The basic idea of a hashtable is the ability to store the key into this data structure, and quickly retrieve the value. This is done through what we call a hash.

---

## terminology

- `Hash`: A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.
- `Buckets`: A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.
- `Collisions`: A collision is what happens when more than one key gets hashed to the same location of the hashtable.

---

## Internal Methods

- `Add()`
  - When adding a new key/value pair to a hashtable:
     1. send the key to the GetHash method.
     2. Once you determine the index of where it should be placed, go to that index
     3. Check if something exists at that index already, if it doesn’t, add it with the key/value pair.
     4. If something does exist, add the new key/value pair to the data structure within that bucket.
- `Find()`
  - The Find takes in a key, gets the Hash, and goes to the index location specified. Once at the index location is found in the array, it is then the responsibility of the algorithm the iterate through the bucket and see if the key exists and return the value.

- `Contains()`
  - The Contains method will accept a key, and return a bool on if that key exists inside the hashtable. The best way to do this is to have the contains call the GetHash and check the hashtable if the key exists in the table given the index returned.

- `GetHash()`
  - The GetHash will accept a key as a string, conduct the hash, and then return the index of the array where the key/value should be placed.

## video

- [![Watch the video](https://img.youtube.com/vi/MfhjkfocRR0/hqdefault.jpg)](https://youtu.be/MfhjkfocRR0)

---
---
- [source](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-30/resources/Hashtables.html)
- [source](https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/)
