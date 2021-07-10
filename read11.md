# Spring MVC and Thymeleaf
## what is Spring ? 
spring boot is a framework that makes it easy to create spring-based app :
* stand-alone and production-grade spring.
* embedded Tomcat , jetty  
*starter configration.
* no code generation.
## Software programs :
* java Development Kit t(JDK).
* intellij IDEA ultimate edition. 

## Spring MVC and Thymeleaf: how to access data from templates
* M : for Model 
* V : for View
* C: for Controller. 


**what is spring model ?** 
it's a model works as container that contains the data of the application, so in another words : it represents a Java object carrying data.

**What is view ?**
view visualizes the data that the model contains.

**what is controller ?**
The controller manages the data flow into model object and updates the view whenever data changes.

**we can add an attribute using the addAttribute method.** 
this can explain : 
![img](https://i.stack.imgur.com/38qzM.png)


**ModelAndView attribute**

![img](https://i.stack.imgur.com/SOJx4.png)

## Requesting parameters :
we can easily request params from the client side to the server.
![imh](https://nullbeans.com/wp-content/uploads/2020/05/urldescription-1.png)

## Session attributes
using @SessionAttribute allows us to retrieve from HTTP session.

## ServletContext attributes
it's a set of methods that the servlet can communicate with its servlet container.

## Spring beans
what is spring beans ? 
it's an object of our application.
* Spring bean is managed by Spring IOC
![img](https://reflectoring.io/assets/img/posts/the-lifecycle-of-spring-beans/spring-bean-lifecycle.png)
