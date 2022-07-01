# Read 15

## Trees

### Trees<sup>1</sup>

* A tree is a different type of data structure
  * has nodes just like linked lists, queues, and stacks
  * has other parts
    * root - node at beginning of tree
    * K - number of maximum children any node may have (k = 2 in a binary tree)
    * Left, Right - references to one node in a tree
    * Edge - link between a parent and a child
    * Leaf - a node without children
    * Height - number of edges from root to furthest leaf

![sample-tree](/img/sample-tree.png)

* Like previous data structures, trees can be traversed
  * Depth first - top to bottom
  * Breadth first - all nodes in a level, level-by-level

* Binary trees only have 1 left branch and 1 right branch
* K-ary trees have K number of branches coming off of the root
* K-ary trees can be traversed, its a little more work
* No real rules for where new nodes are "supposed to go" on trees

* BigO
  * Time complexity for adding a node - O(n)
  * Searching for a specific node - O(n)
  * Node insertion using breadth first - O(w) where w is largest width of tree
  * "Perfect binary tree" - every non-leaf node has exactly 2 children
    * max width is `2^(h-1)`, where `h` is height of tree. 
    * height can be calculated as `log n` where `n` is number of nodes

* Binary Search Tree - a type of tree that has *some* structure attached to it.
  * nodes organized in manner where all values smaller than `root` are placed to left, all values larger than `root` placed to right
  * searching a BST
    * compare node searching for against root
      * if smaller, traverse left side
      * if larger, traverse right side
    * BigO
      * Insertion
        * Time = O(h), where h is height
      * Search
        * Space = O(1)

### Footnotes

<sup>1</sup>https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/Trees.html

[Back](/reading-notes/401/401-TOC.html)