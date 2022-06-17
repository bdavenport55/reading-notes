# Read 05

## Linked Lists

### Big O: Analysis of Algorithm Efficiency<sup>1</sup>

* Efficiency measured in 1) running time 2) memory space
* The more that code increases either/both of those, the less efficient it is

Big O is worst case scenario of efficiency - the longest running time taking up the most space

Big Omega is best case scenario - least amount of time to run, using the least space

Big Theta - average case

The amount by which Running Time or Memory Space grows can increase at different speeds, which is called an Order of Growth

![orders-of-growth-table](/img/orders-of-growth-table.png)
![orders-of-growth-plot](/img/orders-of-growth-plot.png)

### Linked Lists<sup>2</sup>

* Linked List - a sequence of `Nodes` that are connected/linked to each other. Each Node references the next Node in the link.

* Traversal - navigation through a linked list
  * Cannot be done using `forEach` nor `for` loop
  * Relies on `Next` value in each node to guide to where next reference is pointing

* `Head` is always first node in a Linked List

### What's a Linked List, Anyway pt1<sup>3</sup>

* Linked lists are linear data structures - sequence and order

* Whereas arrays (static data structures) need memory in a contiguous block, linked lists (dynamic data structures) can be spread around

![memory-allocation](/img/memory-allocation.png)

* Different types of linked lists
  * Singly linked
  * Doubly linked
  * Circular linked

### What's a Linked List, Anyway pt1<sup>4</sup>

* Growing a linked list
  * Find head
  * Make new node, set pointer to current first node
  * Rearrange head node's pointer to point at new node

* "a linked list is usually efficient when it comes to adding and removing most elements, but can be very slow to search and find a single element."

### Footnotes

<sup>1</sup>https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/big_oh.html

<sup>2</sup>https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html

<sup>3</sup>https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d

<sup>4</sup>https://medium.com/basecs/whats-a-linked-list-anyway-part-2-131d96f71996

[Back](/reading-notes/401/401-TOC.html)