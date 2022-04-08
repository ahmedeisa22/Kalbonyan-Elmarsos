# Data Structure
## Learning objectives
* Data types: Booleans, numbers, strings, and more
* Multidimensional arrays
* Jagged arrays
* Search and sort arrays
* Linked lists
* Stacks and queues
* Hash functions and hash tables
* Trees and graphs
 ------

data: information that stored or processd by computer.
**array** collection of elements,where each item is identified by an index or key.
**Data structure:**  A collection with a defined way of accessing and storing item.
**Big O notaion:** Notaion used to describe the performance or complexity of an algorithm.
**o(1) Time:** consistent duration of algorithm  excution in same time regadless of the size of input.

**priority Queue:** each element has a priority associated with it.
**D-E-Q-U-E-K** double-ended queue = item can be added or rempved from either end

| **D-E-Q-U-E-K**     | vs DEQUEUE |
| ------------------- | :--------: |
| noun data structure |    verb    |
---
## Hashbase
**associative key** coolection of key-value pair

**associative array rule:**
* key-value pair are bound together.
* each key must be unique.
* order is't important.
* values are accesed by key.
* duplict value
  **ASCI:** Numerical representation of text characters.
  **Collision:** any time two input produce the samw value.
  **HashTable:** is an implementation of thye associative array abstract data structure.

  **hash tables across languages:**
  * python: dict type
  * swift: dictionary
  * Ruby: hash calss
  * javaScript: object as associative
  * c#/.Net: hash table in system.collection.
  * java: hash table and hash map collection.


  #### big o of (1) => search , delete insertion.

  ---
  ## set
  - collection of unique item.
  - order doesn't matter.
  - no duplicated.

  set works:
  1. take an object.
  2. Hash the object.
  3. store the object using index.
  4. Repeat the proccess and check if have object.
   ---
   ## tree
   **Child node with the same parent are siblings.**
   **node without children leaf.**

   **for tree each node can has:**
   * just one child
   * no children
   * many children
  
  **Heap:** data structure is implemented as a binary tree.
  min heap : the smallest value at the top.
  max heap : the biggest value at the top.



  
  Balance tree: o(log n)
  unBalance tree : o(n)

  heap:
  * find min/max: o(1)
  * insert : o(log n)
  * search: o(n)
  * delete: o(n)

---
![byondCapture](https://user-images.githubusercontent.com/70604321/162356768-f9a6fc53-5833-424d-a64b-6111027947ae.PNG)

#### solve this[Quiz](https://docs.google.com/forms/d/e/1FAIpQLSe5ug8W1GrOGPbhe5CsqDnRLBT9hGZ47IS6VGJsFMMtwTkUXw/viewform?usp=sf_link)

