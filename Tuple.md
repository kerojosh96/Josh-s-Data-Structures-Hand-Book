# \[Tuple\]

A \[Tuple] is a collection which can contain various objects. A tuple is immutable, meaning that once the tuple has been instantiated, nothing can be added or removed.
# In Memory
 
In memory, a \[Tuple\] looks like this:

\[sketch or diagram\]

\[description of diagram\]

# Operations

A \[widget\] supports the following operations:

* Accessing a tuple is Big O(1). Because a tuple is immutable, append() and pop() cannot be used. 
* name: description, Big O efficiency, and explain why / what that means

# Use Cases

A Programmer might want a list of items which never change. For instance, for naming all of the months in a year or to naming video game charaters, a coder could use a tuple.  

It is not as good as \[what] \[why\].

# Example

```
List = ["cat","dog","fish"]
print(List[1])
List[1] = "other value" # This Changes List at index 1
print(List[2])

Tuple = ("cat","dog","fish")
print(Tuple[1])
Tuple[2] = "other value" # this line is NOT valid 
 

```

(c) 2018 Josh Cook. All rights reserved.
