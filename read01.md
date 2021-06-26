# JAVA BASICS 
![img](https://t4d.or.ke/wp-content/uploads/2019/12/Training-Course-in-Java-Programming-Masterclass-t4d.jpg)

## Language Basics :
**Variable** 

![img1](https://static.javatpoint.com/images/java-data-types.png)

## Operators 
 operators are used in mathematical expressions in the same way that they are used in algebra. 
 **Arthmetic** : 
 addition (+) - (Subtraction) * (Multiplication) / (Division) % (Modulus) ++ (Increment) -- (Decrement) 

 **Relational Operators**
 == (equal to) != (not equal to) > (greater than) < (less than) >= (greater than or equal to) <= (less than or equal to) 

 **Logical operators**
 && (logical and) || (logical or) ! (logical not) 

 postfix	expr++ expr--
unary	++expr --expr +expr -expr ~ !


## Expressions 
Expressions are essential building blocks of any Java program, usually created to produce a new value, although sometimes an expression assigns a value to a variable. Expressions are built using values, variables, operators and method calls.
EX:
if (number1 == number2)
    System.out.println("Number 1 is larger than number 2");

    Double a = 2.2, b = 3.4, result;
    result = a + b - 3.4;

    Java Blocks
class Main {
    public static void main(String[] args) {
    	
        String band = "Beatles";
    	
        if (band == "Beatles") { // start of block
            System.out.print("Hey ");
            System.out.print("Jude!");
        } // end of block
    }
}


the output will be (Hey Jude!)


## Control Flow Statements
The statements inside your source files are generally executed from top to bottom, in the order that they appear. Control flow statements, however, break up the flow of execution by employing decision making, looping, and branching, enabling your program to conditionally execute particular blocks of code. This section describes the decision-making statements (if-then, if-then-else, switch), the looping statements (for, while, do-while), and the branching statements (break, continue, return) supported by the Java programming language.

Based on this, we can classify the types of control flow statements as follows:

* Decision Making Statements
* Looping Statements
* Branching Statements


1. Decision Making Statements
We generally use decision-making statements when we have to decide which block of the code will be executed.

There are three types of decision-making statements.

* if statement
* if-else statement
* The switch statement
1. if statement
if statement is the most basic decision-making statement in the java programming language.

2. if-else statement
if-else statement is somewhat similar to the if statement, we are just adding an extra block of the code after the if statement.

If the value of the condition statement is true, the if block will be executed, else the else block will be executed.

3. The switch statement

In the switch statement, there could be several execution paths.
EX :

public class SwitchExample {
 
 public static void main(String[] args) {
 
 
 int rollNumebr = 3;
 
 String studentName;
 
 switch(rollNumebr) {
 
 case 1: studentName = "Rahul";
 break;
 
 case 2: studentName = "Santosh";
 break;
 
 case 3: studentName = "Gaurav";
 break;
 
 case 4: studentName = "Chaitanya";
 break;
 
 case 5: studentName = "Vishal";
 break;
 
 default : studentName = "Invalid roll number";
 break;
 
 }
 
 System.out.println("The name of the student is "+studentName+"!");
 
 }
 
}


##  Looping Statements
* for loop
* while loop
* do-while loop


## for loop 
![img2](https://media.geeksforgeeks.org/wp-content/uploads/20191108131134/For-Loop.jpg)


## While loop 
![img3](https://media.geeksforgeeks.org/wp-content/uploads/20191118164726/While-Loop-GeeksforGeeks.jpg)

## Do While loop 
 in the do-while loop, we are first executing the block of code and then checking the condition.

  continue statement, will skip the current iteration.

  # Code Compiling 
  Compiling is the transformation from Source Code (human readable) into machine code (computer executable). ... A compiler takes the recipe (code) for a new program (written in a high level language) and transforms this Code into a new language (Machine Language) that can be understood by the computer itself.