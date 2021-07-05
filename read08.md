# SOLID: The First 5 Principles of Object Oriented Design
SOLID stands for:

S - Single-responsiblity Principle
O - Open-closed Principle
L - Liskov Substitution Principle
I - Interface Segregation Principle
D - Dependency Inversion Principle

## what does Single responsiblity means ?
 the the class should solve one and only one problem So it should have a single reason to change. 
 this example defines very well the concept of Single-responsiblity of a class :

 ![img](https://dotnettutorials.net/wp-content/uploads/2018/06/Voilatiing-Single-Responsibility-Principle.png)

 ## What is Open-closed Principle ?
 It tells you to write your code so that you will be able to add new functionality without changing the existing code.
 this principle states that software entities should be open for extension, but closed for modification. As a result, when the business requirements change then the entity can be extended, but not modified.

this can explain who can modify and who can not :
![img](https://cdn.hackernoon.com/images/1*YrFZLk1J5abATMlkEwTgpA.gif)

## what is Liskov Substitution Principle ?
im means that objects of a superclass shall be replaceable with objects of its subclasses without breaking the application. 
so it must behave the same as the superclass . and the reason behind that is to reduce coupling and facilitate code reusability in our application.

## what is Interface Segregation Principle ?
to break the general interface to one or more specific and cohesive interfaces.
so whe we devide our interface into smaller interfaces we  are reducing our class implementation only to required actions without any additional or unnecessary code.
 

 ##  what is Dependency Inversion Principle ?
 high-level modules should not depend on low-level modules ,b oth should depend on abstractions. 
 This abstraction removes the direct dependency on the details, decoupling it and thus allows for easier re-use of the important functionality in the policy. 
 and this can explain the concept :

 ![img](https://ducmanhphan.github.io/img/Java/cdi/cdi-example.png)