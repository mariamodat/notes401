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
 which means that  the concept is : the class is **open for extension, but closed for modification**. 

this can explain who can modify and who can not :
![img](https://cdn.hackernoon.com/images/1*YrFZLk1J5abATMlkEwTgpA.gif)

## what is Liskov Substitution Principle ?
im means that objects of a superclass shall be replaceable with objects of its subclasses , so it must behave the same as the superclass ,so we dont have to doublicate codes .
## what is Interface Segregation Principle ?

 we devide our interface into smaller interfaces we  are reducing our class implementation only to required actions without any additional or unnecessary code.
 

 ##  what is Dependency Inversion Principle ?
 high level modules should not depend on low level modules ,both should depend on abstractions. 
 so it  allows for easier re-use of the important functionality in the policy. 
 and this can explain the concept :

 ![img](https://ducmanhphan.github.io/img/Java/cdi/cdi-example.png)