# Python-Data-Structures-and-Algorithms
 
# Stack class

This is a Python class that implements a stack data structure. A stack is a linear data structure in which elements are added and removed from one end, called the top. The stack follows the last-in, first-out (LIFO) principle, which means that the last element added to the stack is the first element to be removed.

The `Stack` class has the following methods:

* `__init__(self)`: Initializes the stack.
* `is_empty(self)`: Returns True if the stack is empty, False otherwise.
* `push(self, item)`: Adds an item to the stack.
* `pop(self)`: Removes an item from the stack and returns it.
* `peek(self)`: Returns the top item on the stack without removing it.
* `size(self)`: Returns the number of items in the stack.
* `__str__(self)`: Returns a string representation of the stack.

Here is an example of how to use the `Stack` class:
python
>>> s = Stack()
>>> print(s)
[]
>>> print(s.is_empty())
True
>>> s.push(1)
>>> s.push(2)
>>> s.push(3)
>>> print(s)
[1, 2, 3]
>>> print(s.pop())
3
>>> print(s.peek())
2
>>> print(s.size())
2
The `Stack` class is a useful data structure for implementing a variety of algorithms, such as the infix-to-postfix conversion algorithm and the binary search algorithm.