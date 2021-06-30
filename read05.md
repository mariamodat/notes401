
# Terminology 
# NodeLists 
* What is NodeList :
it's a part of collection frame work where the data inside it is stored as a separate object with a data part and address part.

* Singly :means that there is only one reference, and the reference points to the Next node in a linked list.

* Doubly: t means that there is a reference to both the Next and Previous node.

## what are Head , Current ?
![img](https://static.javatpoint.com/ds/images/singly-linked-list-vs-doubly-linked-list.png)

## how we can loop through the node ? 
we can notice that we can not use the for or foreach loop instead , we can use We depend on the Next.

 * we should check that the Next node in the list is not null. If we accidentally end up trying to traverse on a node that is null, a Null Reference Exception gets thrown and our program will crash.

 ## How do you insert a node in Java? 
 * Create a class Node which has two attributes: data and next. Next is * a pointer to the next node in the list.
 * Create another class InsertEnd which has two attributes: head and tail.
 * addAtEnd() will add a new node at the end of the list: Create a new node.


## And here an example to understand the concept of adding nodes :
![img](https://i.stack.imgur.com/EuReW.png)

## to add understand the process of how to add before we can notice this example to get the idea and the method of adding before .
![imgg](https://media.geeksforgeeks.org/wp-content/uploads/20200822122044/ibhll.jpg)