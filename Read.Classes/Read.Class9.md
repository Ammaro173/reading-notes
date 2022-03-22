# Read: Class 09

---

> [Back to Home](../README.md)

---

> [references](https://dbader.org/blog/python-dunder-methods)

## What Are Dunder Methods?

> What is it?

    n Python, special methods are a set of predefined methods you can use to enrich your classes. They are easy to recognize because they start and end with double underscores, for example __init__ or __str__.

    As it quickly became tiresome to say under-under-method-under-under Pythonistas adopted the term “dunder methods”, a short form of “double under.”

    These “dunders” or “special methods” in Python are also sometimes called “magic methods.”

> Dunder methods let you emulate the behavior of built-in types. For example, to get the length of a string you can call len('string'). But an empty class definition doesn’t support this behavior out of the box:

### examples

    class NoLenSupport:
    pass

    obj = NoLenSupport()
    len(obj)
    TypeError: "object of type 'NoLenSupport' has no len()"

    > so we made our code more readable and print 4 lines in 1 Line !!

> To fix this, you can add a **\_\_len\_\_** dunder method to your class:

    class LenSupport:
        def __len__(self):
            return 42

    obj = LenSupport()
    len(obj)
    #42

> Another example is slicing. You can implement a **\_\_getitem\_\_** method which allows you to use Python’s list slicing syntax: obj[start:stop].

---

## Special Methods and the Python Data Model

    This elegant design is known as the Python data model and lets developers tap into rich language features like sequences, iteration, operator overloading, attribute access, etc.

    You can see Python’s data model as a powerful API you can interface with by implementing one or more dunder methods. If you want to write more Pythonic code, knowing how and when to use dunder methods is an important step.

    For a beginner this might be slightly overwhelming at first though. No worries, in this article I will guide you through the use of dunder methods using a simple Account class as an example.

> Enriching a Simple Account Class:

    1- Object Initialization: __init__
    2- Object Representation: __str__ , __repr__
    3- Iteration: __len__, __getitem__, __reversed__
    4- Operator Overloading for Comparing Accounts: __eq__, __lt__
    5- Operator Overloading for Merging Accounts: __add__
    6 -Callable Python Objects: __call__
    7- Context Manager Support and the With Statement: __enter__, __exit__

---

> [Back to Home](../README.md)
