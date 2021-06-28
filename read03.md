# Java Type System
ava has a two-fold type system consisting of primitives such as int, boolean and reference types such as Integer, Boolean. Every primitive type corresponds to a reference type.


 Integer is a class, that wraps the int primitive, and making a new Integer() means we're really making an object of type Integer.

 Integer j = 1;          // autoboxing
int i = new Integer(1); // unboxing


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

We can notice that a single variable of Boolean type occupies as much space as 128 primitive ones, while one Integer variable occupies as much space as four int ones.

Primitives are passed by value, a copy of the primitive itself is passed. Whereas for objects, the copy of the reference is passed, not the object itself. Primitives are independent data types, there does not exist a hierarchy/super class for them. Whereas every Object is descendent of class "Object". 

* Every object has some default methods of itself, which it inherits from the class Object (e.g. toString(), clone(), wait(), notify(), notifyAll(), etc.). The primitives does not have any method associated with themselves.

* With objects, there are two types of copies, Shallow and Deep. There is a significant difference between them. So the choice depends on how do we intend to use them. With primitives, there is no such difference, everything is by default deep copy only