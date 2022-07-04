## [Go to Home Page]() | [Sololearn](https://www.sololearn.com/)

# Samples

01. [x] [reverse]()

## Classes

### Inheritance

- Inheritance share functionality between classes.
- A class that inherits from another class is called a subclass.
- A class that is inherited from is called a superclass.
- The function super that refers to the parent class.
- Inherit A1 class from B1 class A1(B1)

* **Magic Methods for comparisons**
    - __lt__ for <
    - __le__ for <=
    - __eq__ for ==
    - __ne__ for !=
    - __gt__ for >
    - __ge__ for >=

* **Magic Methods for making classes**
    - __len__ for len()
    - __getitem__ for indexing
    - __setitem__ for assigning to indexed values
    - __delitem__ for deleting indexed values
    - __iter__ for iteration over objects (e.g., in for loops)
    - __contains__ for in

### Encapsulation
- There are no ways of enforcing that a method or attribute be strictly private.(weakly)
- Private methods and attributes have a single underscore at the beginning.(strongly)
- Private methods and attributes have a double underscore at the beginning of their names. call: _class__privatemethod

## Class Methods
    - @classmethod

## Static Methods
    - @staticmethod

## Properties
    - @property
    - to make an attribute read-only
    - be set by defining setter/getter functions
    - to use a decorator of the same name as the property, followed by a dot and the setter/getter keyword