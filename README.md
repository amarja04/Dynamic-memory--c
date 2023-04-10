# Linked Lists --c

Linkedlist in simple terms is a linear collection of data elements. These data elements are called nodes. Linked list is a data structures. Thus, it acts as a building block to implement data structures such as stacks, queues, and their variations. A linked list can be perceived as a train or a sequence of nodes in which each node contains one or more data fields and a pointer to the next node which in turn can be used to implement other data.

 ![download](https://user-images.githubusercontent.com/125913981/230955380-a125d640-80b7-491f-a14c-a3d38b42db83.png)
 
 Each node contains two sub-elements. A data part that stores the value of the element and next part that stores the pointer to the next node
 The first node also known as HEAD is always used as a reference to traverse the list. The last node points to NULL. Linked list can be visualized as a chain of nodes, where every node points to the next node.


![image](https://user-images.githubusercontent.com/125913981/230955846-851d3ce1-96ea-4fc2-bba9-64ef4f414249.png)

[1] Singly-Linked List 

A singly linked list is the simplest type of linked list in which every node contains some data and a pointer to the next node of the same data type.

By saying that the node contains a pointer to the next node, we mean that the node stores the address of the next node in sequence.
A singly linked list allows traversal of data only in one way


[2] Doubly-Linked List 

A doubly linked list or a two-way linked list is a more complex type of linked list which contains a pointer to the next as well as the previous node in the sequence.  Therefore, it consists of three parts —data, a pointer to the next node, and a pointer to the previous node.
      
The PREV field of the first node and the NEXT field of the last node will contain NULL.
The PREV field is used to store the address of the preceding node, which enables us to traverse the list in the backward direction.

A doubly linked list provides the ease to manipulate the elements of the list as it maintains pointers to nodes in both the directions (forward and backward). The main advantage of using a doubly linked list is that it makes searching twice as efficient.


[3] Circular Linked List  

         
In a circular linked list, the last node contains a pointer to the first node of the list.
We can have a circular singly linked list as well as a circular doubly linked list. 
     
While traversing a circular linked list, we can begin at any node and traverse the list in any direction, forward or backward, until we reach the same node where we started.  Thus, a circular linked list has no beginning and no ending.
 
