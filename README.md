# python_noob

a run-through of [Learn Python in 10 Minutes](https://www.stavros.io/tutorials/python/)

## Features

* `help()` - manpage for class
* `dir()` - methods for object
* `._doc__` - docblock for function
* Major types: lists `[]`, tuples `()`, dictionaires `{}`, set
  * tuples, ints, strings are immutable
* Functions are first class (as in JS): `fun = len; fun([1,2,3])`
* Slicing: `[:]` everything, `[0:2]` first two elements
  * `[::2]` 2 == step size
* Interpolation: `print("Name: %s, Number: %s" % ("josh", 29))`
* Multiline string: `"""`
* Map interpolation: `print("This %(verb)s a %(noun)s." % {"noun": "test", "verb": "is"})`

* Flow control: `for...in...:`, `if, elif, else`, `break`, `continue`, `while`, `range`

* Functions:
  * named arguments
  * can return a tuple that can be destructured
  * lambdas: `myfun = lambda x: x + 1; myfun(2)`

* Classes:
  * Inheritance: `class MyClass(YourClass):`
    * Supports multiple inheritance
  * Instantiation: `MyClass()`
  * Constructors: `def __init__(self)`
    * Instance methods always are passed `self` first

* `try`, `except`, `else`, `finally`

* `import random`, `from time import clock`

* `pickle` for serialization

* supports list comprehensions

* global variables must use the `global` keyword
