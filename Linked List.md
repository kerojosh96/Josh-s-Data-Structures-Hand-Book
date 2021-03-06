# 

A linked list is an ordered collection of elements in which each node points to the next node. The first node is called the head and each node that is at the end of a list has a default null value.Traversal is accomplished by starting at a node and moving recursively to the next node.     
There are a few different types of linked lists.
* in a singly linked list, each node has only one pointer, pointing to the next node.
*	in a doubly linked list, each node has two points one pointing forwards and the other backwards.   



# In Memory

![](pics/linked.png):



A diagram of a singly linked list in memory. 

# Operations

A linked list supports the following operations:

* Accessing and searching a linked list is O(n) because you have to iterate across the list to find the search value. 
* Adding and deleting a value at the end of a linked list is O(1) because there is a variable which stores the location of the last element. 

# Use Cases

A linked list is useful when quick insertion and deletion are needed. It is also useful when you need to insert a value into the middle of a linked list.

A linked list is not useful if you need random access as you would have to iterate across the list. 

# Example

```
test =  linked_list()
test.push(5)#adds a new value
test.push(1)#adds a new value
test.pop()#removes the last element 

```

(c) 2018 Josh Cook. All rights reserved.

