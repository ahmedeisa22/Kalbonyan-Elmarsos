# Data Structure
## Learning objectives
* Measuring algorithm performance
* Working with data structures such as arrays, stacks, and queues
* Looping and recursion
* Sorting data
* Searching data
* Filtering and value counting with hash tables

---
 **Algorithms:** Algorithms are basically processes, or recipes, instructions, whatever you want to call them, that describe how to perform certain tasks.
  
-  without understanding algorithms is like trying to build a car without understanding engines. 

**Algorithms characteristics:**
* associated complexity
  * space complexity: which describes how much memory and storage space 
  * time complexity : how much time does it take to complete.
* inputs / outputs
    * what does the algorithsm accept and what are the results.
* classification
   * srial/parallel,exact/approximate,determistic - non determinstic.
  

**Common algorithm:**
* search algorithm:
  (a substring within string)
* sorting algorithm 
  take a set of data, and place it into a particular order.
* Computational algorithms
  take one set of data and derive another set of data from it.
(is a prime number)
* collection algorithms:
manipulating among sets of data that are stored within a particular structure

```py
 Find the greatest common denominator of two numbers
# using Euclid's algorithm


def gcd(a, b):
    while (b != 0):
        t = a       # set aside the value of a
        a = b       # set a equal to b
        b = t % b   # divide t (which is a) by b

    return a


# try out the function with a few examples
print(gcd(60, 96))  # should be 12
print(gcd(20, 8))   # should be 4
```
1. for two integers a and b , where a > b , divided a by b
2. if remainder, r , is 0 then stop: GCD is b
3. otherwise, set a = b and b = r.and repeat at step 1 until r is 0.
  
  **Understanding algorithm performance:**
  * measure how does the performance of an algorithm change, based on the size of the input set of data.
  * Big-O notation: used to describe algorithm performance.
    * describe how a particular algorithm performs as the size of the set of input grows over time.
    * It usually describes the worst case scenario of
    * the reason the letter O is used is because the growth rate of an algorithm's time complexity is also referred to as the order of operation.
* many different algorithms and data structures have more than one Big-O value.
   * inserting or searching for values each of which have their own order of operation.


**common big o notaion**
|  Notaion   |                     Description                     |                                  Example                                   |
| :--------: | :-------------------------------------------------: | :------------------------------------------------------------------------: |
|    o(1)    |                    constant Time                    |                  looking up a single element in an array                   |
|  o(log n)  |                     Logarithmic                     |            finding an item in a stored array in a binary search            |
|    o(n)    |                     Linear Time                     |              searching an unsorted array for a specific value              |
| o(n log n) | complex sorting algorithm like heap sort merge sort |
|   o(n2)    |                      Quadratic                      | simple sorting algorithm like buble sort , selection sort , insertion sort |

---

## common data structure

##### Array: 
Collection of elements identified by index or key.

**Array operation:**
* Calculate item index: O(1)
* inserting or deleting at the begging: O(n).
* inserting or deleting in the middle: O(n).
* insert or delete at the end: O(1).



**Linked List:** 
* Collection of data elemnts ,called node.
* contain reference to the next node
* hold whatever data the applocation need.

**called a singly-linked list. It's called that because there's only one direction of links provided,**


**doubly linked list, which is illustrated here. In this case, each data item has a reference to both the previous and next items that are its neighbors.**

#### Linked list:
* Element can be easy inserted and removed.
* underlying memory dosen't need to be recoganized.
* can't do constant time random item access. 
* item look up is linear.


**Hash Table**
* ability to uniquely map a given key to a specific value.
* They are typically faster than other kinds of table lookup structures.
* array for small database.
* hash tables don't usually order their entries in any particular way.





---
**Rcursion:**
Rcursion is when function call itself.
* need breakpoint.
* this prevent ifinte loop eventual crashes.
* each time the function is called the old arguments are saved

---
**The sorting algorithms:**
* bubble sort
* merge sort
* quick sort

**Bubble sort:**
* very simple to understand and impelement.
* performance: O(n^2^).
  * for loop insde for loo = n^2^.
* other sorting algorithm are much better.
* not considered to be a practical way of sorting data unless the dataset is very small.
  

  **merge sort:**
  * divide and conquer algorithm.
  * break a dataset into individual pieces and merge them.
  * use recusion to operate on data base.
  * performane well on large sets of data.
  * big O(n log n) complexity.
 
 **Quick sort:**
 * divide and conquer algorithm.
 * use recusion to operate on data base.
 * performance better than merge sort
 * oprtates in palce on the data.
 * worest case scenario O(n^2^) when data is mostly sorted.
  
  #### the Quick sort:Pivot point Selection.
  ---
  
![eeee](https://user-images.githubusercontent.com/70604321/162643774-1097b7bb-3a7e-429d-83bb-1772b393bb1d.png)
