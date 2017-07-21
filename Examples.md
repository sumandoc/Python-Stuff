### 1. collections.Counter lets you find the most common elements in an iterable:


```
>>> import collections
>>> c = collections.Counter('helloworld')

>>> c
Counter({'l': 3, 'o': 2, 'e': 1, 'd': 1, 'h': 1, 'r': 1, 'w': 1})

>>> c.most_common(3)
[('l', 3), ('o', 2), ('e', 1)]
```

### 2.
```
>>> import antigravity
```
in python console will take you to [XKCD site](https://xkcd.com/353/).

### 3. Reversing lists in python

Option 1: Reversing a List In-Place With the  list.reverse() Method

```
>>> mylist = [1, 2, 3, 4, 5]
>>> mylist
[1, 2, 3, 4, 5]

>>> mylist.reverse()
None

>>> mylist
[5, 4, 3, 2, 1]
```

Option 2: Using the “[::-1]” Slicing Trick to Reverse a Python List

```
>>> mylist
[1, 2, 3, 4, 5]

>>> mylist[::-1]
[5, 4, 3, 2, 1]
```
Option 3: reversed()

Python’s built-in reversed() function allows you to create a reverse iterator for an existing list or sequence object. This is a flexible and clean solution that relies on some advanced Python features—but it remains readable due to the clear naming of the reversed() function.

```
>>> lst = [1, 2, 3, 4, 5]
>>> list(reversed(lst))
[5, 4, 3, 2, 1]
```












