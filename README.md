# Comp-Sci-10-11-2021

## Java Collections Framework (JCF): Lists, Stacks, Queues, Priority Queues, Sets, and Maps

### Data Structurs vs Abstract Data Types
* **Data Structures:**
  * A specific way of organizing data and operations to access/use the data
  * Structure of the data tied directly to the implementation
* Abstract data type: An implementation independent group of data and a set of operations on this data - use a programming language to implement

### Data Structures We Know
* Both arrays and ArrayList are the data structures
  * Implementation dependent
* What are the similarities between ArrayList and arrays?
  * Organization of data?
  * Operations?
  * Both can have duplicate elements
  * Both are unordered lists
  * both use index to access elements
  * Both can have null values
* What are the differences between these?
  * Organization of data?
  * Operations?
  * Array is **static** in size
  * ArrayList is **dynamic** in size
  * Automatic resizing may slow down the performance
  * ArrayList **can not** have primitive data types
  * **Type safety** in ArrayList is ensured with the use of Generics

### Class hierarchy for ArrayList
* Interfaces are abstract data types

### Collection Interface
* What is a collection
  * "Bag" (or "pile") of objects
* What does the Collection interface provide?
  * add()
    * What happens when we cannot add a new entry?
      * Do nothing
      * Signal the client
  * remove()
  * contains()
  * Iterator: a means of iterating over all objects in the collection
* Interface Collection<E>
* Type Parameters: E - the type of elements in this collection
* All Superinterfaces: Iterable<E>
* All Known
  * Subinterfaces: BeanContext, BeanContextServices, BlockingDeque<E>, BlockingQueue<E>
* Classes: 

## LinkedList
* Example of a linked list using people
  * Singly linked list versus doubly linked list
  * How do we search for items?
  * How efficient is it to add items?
  
* Java API: examine LinkedList API
