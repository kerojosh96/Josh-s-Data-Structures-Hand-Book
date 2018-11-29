# Stack

A stack is an ordered collection of elements in which items are either added (push) or removed (pop) from only one end. A stack is a Last-In-First-Out structure or (LIFO) and elements cannot be added or removed anywhere but the top. a

# In Memory

![](pics/stack.png)

# Operations

A \[widget\] supports the following operations:
* The efficiency of push and pop are both O(1) because they both only can be added/removed from the head using a variable to store the value of the head and therefore, no iteration is needed.
*     


# Use Cases

* Because pushing onto a stack is O(1), A great use for a stack would for collecting tons of data for later analyses. 

* A stack would not be very useful if you wish to frequently search threw the stack for a specific element, this would be better handled with an array.   


# Example

```
foo = Stack() #creates a new stack 
foo.push("hello")
foo.push("hi")
foo.push(True)
foo.pop()# removes True
print(foo.Peek())

```

(c) 2018 YOUR NAME. All rights reserved.
