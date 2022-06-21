# Python - Classes and Objects
In this project, I learned the following:

* What is OOP and 
* Python classes, objects and instance
* What an attribute is and how to use public, protected and private attributes
* Methods in Python and how to use the __init__ method
* Data Abstraction, Data Encapsulation, and Information Hiding
* How to dynamically create arbitrary new attributes for existing instances of a class
* How to bind attributes to object and classes
* How to use the getattr function

## Resources
* [Object Oriented Programming1](https://python.swaroopch.com/oop.html)
* [Object Oriented Programming2](https://python-course.eu/oop/object-oriented-programming.php)
* [Properties vs. Getters and Setters](https://python-course.eu/oop/properties-vs-getters-and-setters.php)
* [Learn to Program 9 : Object Oriented Programming(YT)](https://www.youtube.com/watch?v=1AGyBuVCTeE&)
* [Python Classes and Objects(YT)](https://www.youtube.com/watch?v=apACNr7DC_s)

## Tasks :page_with_curl:
* **0. My first square**
  * [0-square.py](./0-square.py): An empty class `Square` that defines a square
  * You are not allowed to import any module

* **1. Square with size**
  * [1-square.py](./1-square.py): A class `Square` that defines a square by: (based on `0-square.py`)
  * Private instance attribute: `size`
  * Instantiation with `size` (no type/value verification)
  * Without importing any module
Why?
Why size is private attribute?

* **2. Size validation**
  * [2-square.py](./2-square.py): A class Square that defines a square by: (based on 1-square.py)
  * Private instance attribute: size
  * Instantiation with optional size: def __init__(self, size=0):
  * Without importing any module

* **3-square.py**
  * [3. Area of a square](./3. Area of a square): A class Square that defines a square by: (based on 2-square.py)
  * Private instance attribute: size
  * Instantiation with optional size: def __init__(self, size=0):
  * Public instance method: def area(self): will return the current square area
  * Without importing any module

* **4. Access and update private attribute**
  * [4-square.py](./4-square.py): A class Square that defines a square by: (based on 3-square.py)
  * Private instance attribute: size
    * property def size(self): to retrieve it
    * property setter def size(self, value): to set it:
    * size must be an integer, otherwise raise a TypeError exception with the message size must be an integer
    * if size is less than 0, raise a ValueError exception with the message size must be >= 0
  * Instantiation with optional size: def __init__(self, size=0):
  * Public instance method: def area(self): that returns the current square area

* **5. Printing a square**
  * [5-square.py](./5-square.py): A class Square that defines a square by: (based on 4-square.py)
  * Private instance attribute: size
    * property def size(self): to retrieve it
    * property setter def size(self, value): to set it:
    * size must be an integer, otherwise raise a TypeError exception with the message size must be an integer
    * if size is less than 0, raise a ValueError exception with the message size must be >= 0
  * Instantiation with optional size: def __init__(self, size=0):
  * Public instance method: def area(self): that returns the current square area
  * Public instance method: def my_print(self): that prints in stdout the square with the character #:
    * If size is equal to 0, the program will print an empty line
  * Without importing any module

* **6. Coordinates of a square**
  * [6-square.py](./6-square.py): A class Square that defines a square by: (based on 5-square.py)
  * Private instance attribute: size:
    * property def size(self): to retrieve it
    * property setter def size(self, value): to set it:
    * size must be an integer, otherwise raise a TypeError exception with the message size must be an integer
    * if size is less than 0, raise a ValueError exception with the message size must be >= 0
  * Private instance attribute: position:
    * property def position(self): to retrieve it
    * property setter def position(self, value): to set it:
    * position must be a tuple of 2 positive integers, otherwise raise a TypeError exception with the message position must be a tuple of 2 positive integers
  * Instantiation with optional size and optional position: def __init__(self, size=0, position=(0, 0)):
  * Public instance method: def area(self): that returns the current square area
  * Public instance method: def my_print(self): that prints in stdout the square with the character #:
    * if size is equal to 0, the program should print an empty line
  * No module import was used


## Author:
[Excel](github.com/trillionclues)


## Copyright: 
ALX(Holberton School)
