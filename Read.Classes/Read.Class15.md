# Read: class 15 (Trees data structure)

---

> [Back to Home](../README.md)

---

> [references](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/Trees.html)

## Trees?

> What is it?

    The data structure is a specialized method to organize and store data in the computer to be used more effectively. There are various types of data structures, such as stack, linked list, and queue, arranged in sequential order. For example, a linked data structure consists of a set of nodes that are linked together by links or points.

    Similarly, the tree data structure is a kind of hierarchal data arranged in a tree-like structure. It consists of a central node, structural nodes, and sub nodes, which are connected via edges. We can also say that tree data structure has roots, branches, and leaves connected with one another.

> Basic Terminology In Tree Data Structure:

Parent Node: The node which is a predecessor of a node is called the parent node of that node. {2} is the parent node of {6, 7}.
Child Node: The node which is the immediate successor of a node is called the child node of that node. Examples: {6, 7} are the child nodes of {2}.
Root Node: The topmost node of a tree or the node which does not have any parent node is called the root node. {1} is the root node of the tree. A non-empty tree must contain exactly one root node and exactly one path from the root to all other nodes of the tree.
Degree of a Node: The total count of subtrees attached to that node is called the degree of the node. The degree of a leaf node must be 0. The degree of a tree is the maximum degree of a node among all the nodes in the tree. The degree of the node {3} is 3.
Leaf Node or External Node: The nodes which do not have any child nodes are called leaf nodes. {6, 14, 8, 9, 15, 16, 4, 11, 12, 17, 18, 19} are the leaf nodes of the tree.
Ancestor of a Node: Any predecessor nodes on the path of the root to that node are called Ancestors of that node. {1, 2} are the parent nodes of the node {7}
Descendant: Any successor node on the path from the leaf node to that node. {7, 14} are the descendants of the node. {2}.
Sibling: Children of the same parent node are called siblings. {8, 9, 10} are called siblings.
Depth of a node: The count of edges from the root to the node. Depth of node {14} is 3.
Height of a node: The number of edges on the longest path from that node to a leaf. Height of node {3} is 2.
Height of a tree: The height of a tree is the height of the root node i.e the count of edges from the root to the deepest node. The height of the above tree is 3.
Level of a node: The count of edges on the path from the root node to that node. The root node has level 0.
Internal node: A node with at least one child is called Internal Node.
Neighbour of a Node: Parent or child nodes of that node are called neighbors of that node.
Subtree: Any node of the tree along with its descendant

## Types of Tree data structures

The different types of tree data structures are as follows:

1. General tree

A general tree data structure has no restriction on the number of nodes. It means that a parent node can have any number of child nodes.

2. Binary tree

A node of a binary tree can have maximum number of two child nodes. In the given tree diagram, node B, D, and F are left children, while E, C, and G are the right children.

3. Balanced tree

If the height of the left sub-tree and the right sub-tree are equal or differs at most by 1, the tree is known as balanced tree data structure.

4. Binary search tree

As the name implies, binary search trees are used for various searching and sorting algorithms. The examples include AVL tree and red-black tree. It is a non-linear data structure. It shows that the value of the left node is less than its parent, while the value of right node is greater than its parent.

Properties

The following are the properties of tree data structures.

• For the n number of nodes, the edges of a tree are equal to (n – 1). For example, 5 nodes includes (5 – 1) 4 edges in a tree data structure, as shown in the above tree diagram.

• The arrow in the structure represents the path. Every edge connects two nodes.

• Any two nodes or vertices of the tree graph are connected by exactly one edge.

• The depth of the node is defined as the length of the path from the root node to the node a. The height of the node ‘a’ is the longest path from the node ‘a’ to the leaf node of the given tree.

Applications

The applications of tree data structures are as follows:

• Spanning trees

It is the shortest path tree used in the routers to direct the packets to the destination.

• Binary Search Tree

It is a type of tree data structure that helps in maintaining a sorted stream of data.

• Storing hierarchical data

Tree data structures are used to store the hierarchical data, which means data arranged in the form of order.

• Syntax tree

The syntax tree represents the structure of the program’s source code, which is used in compilers.

• Trie

It is the fast and efficient way for dynamic spell checking. It is also used for locating specific keys from within a set.

• Heap

It is also a tree data structure that can be represented in a form of array. It is used to implement priority queues.

---

> [Back to Home](../README.md)
