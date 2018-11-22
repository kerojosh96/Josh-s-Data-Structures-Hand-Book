# \[Tuple\]

A \[Tuple] is a collection which can contain various objects. A tuple is immutable, meaning that once the tuple has been instantiated, nothing can be added or removed.
# In Memory
 
In memory, a \[Tuple\] looks like this:


# Operations

A \[tuple\] supports the following operations:

* Accessing a tuple is Big O(1) because when the search value is known, you don't need to iterate across the whole tuple. However, searching is Big O(n) because, depending on where the item is located, you may need to iterate the entire tuple to find what you are looking for.  Because a tuple is immutable, append() and pop() cannot be used and therefore, deletion and insertion are impossible.


# Use Cases

A programmer might want a list of items which never change. For instance, for naming all of the months in a year or naming video game characters, a coder could use a tuple.  

Using a tuple is not very useful when items need to frequently change/add/removed or changed at all.

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
