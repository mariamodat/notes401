# Java Type System
 Integer is a class, that wraps the int primitive, and making a new Integer() means we're really making an object of type Integer.

* Integer j = 1;          // autoboxing
* int i = new Integer(1); // unboxing

Autoboxing:  is the process of converting a primitive type to a reference.

Unboxing: is the process of converting a reference one to primitive type.

Primitives: int, boolean
reference types: Integer, Boolean.


## Pros and Cons
The decision what object is to be used is based on what application performance we try to achieve, how much available memory we have.
![img](https://techvidvan.com/tutorials/wp-content/uploads/sites/2/2020/06/Pros-Cons-of-Java-tv-1.jpg)


## Single Item Memory Footprint
Memory footprint refers to the amount of main memory that a program uses or references while running. 

* boolean – 1 bit
* byte – 8 bits
* short, char – 16 bits
* int, float – 32 bits
* long, double – 64 bits

* Boolean – 128 bits
* Byte – 128 bits
* Short, Character – 128 bits
* Integer, Float – 128 bits
* Long, Double – 192 bits


Primitives are passed by value, a copy of the primitive itself is passed. Whereas for objects, the copy of the reference is passed, not the object itself. Primitives are independent data types, there does not exist a hierarchy/super class for them. Whereas every Object is descendent of class "Object". 

* Every object has some default methods of itself, which it inherits from the class Object (e.g. toString(), clone(), wait(), notify(), notifyAll(), etc.). The primitives does not have any method associated with themselves.

* With objects, there are two types of copies, Shallow and Deep. There is a significant difference between them. So the choice depends on how do we intend to use them. With primitives, there is no such difference, everything is by default deep copy only.


#  Exceptions
Exceptions in Java.
What Is an Exception?
Exception is like a error massage that appeer when you have somthing goes wrong and if that happend we need to habdle in we can do that by using try and catch.

* The try statement allows you to define a block of code to be tested for errors while it is being executed.

* The catch statement allows you to define a block of code to be executed, if an error occurs in the try block.

ex : 
try {
  //  Block of code to try
}
catch(Exception e) {
  //  Block of code to handle errors
}

What is happen when an error occurs within a method?
If that happen the method will creates a mssage have the error and the type of it and send it to the user.
The Catch or Specify Requirement
In this part it’s telling what happen when the code throw a certain exceptions. the first thing we can do by a try statement that catches the exception. The try must provide a handler for the exception,or a method that specifies that it can throw the exception. The method must provide a throws clause that lists the exception.
Catching and Handling Exceptions.

# Scanner 

* The Scanner class is used to get user input, and it is found in the java.util package.

