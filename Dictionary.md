# Dictionary

A \[dictionary\] is an unordered collection of objects which uses a system of organization of value and key pairs notated using curly brackets.

# In Memory

In memory, a \[widget\] looks like this:

\[sketch or diagram\]

\[description of diagram\]

# Operations

A \[dictionary\] supports the following operations:

* Because dictionaries use hashing algorithms,(in most cases) accessing a value in a dictionary as well as setting a value and deleting an item is Big O(1). The only difference would be in using some kind of iteration which would be big O(n) 
* A hash table uses a hash function to turn an element into a indexable value. If done properly this can allow O(1) access of an element. If two values have the same key and a collision occurs, the performance can degrade into O(n) as it chains multiple arrays of linked lists at each collided value.


# Use Cases

A dictionary is useful a person needs fast retrieval of data. Some common uses include database indexing, error checking and password authentication.  

a dictionary is not very useful when order of elements matters or iteration is needed .

# Example

```
dict = {1:"one",2:"two",3:"three"}
print(dict[1])# prints from key 1
dict[4] = "four" # this adds a new key
print(dict[4]) # prints the value at key 4
del dict[2]# removes the key/value of 2
```

(c) 2018 YOUR NAME. All rights reserved.
