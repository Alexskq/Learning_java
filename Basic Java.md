# Basic Java
-----------

## Compilation

- Java is a compiled programming language, meaning the code we write in a .java file is transformed into byte code by a compiler before it is executed by the Java Virtual Machine on your computer.

A compiler is a program that translates human-friendly programming languages into other programming languages that computers can execute.

Steps of Java Compilation :  ` File.java -> Compiler -> File.class -> Java Virtual Machime -> Client Program `

The compiling process catches mistakes before the computer runs our code.


## Variable

- int, which stores whole numbers.
- double, which stores bigger whole numbers and decimal numbers.
- boolean, which stores true and false.
- char, which stores single characters using single quotes.
- String, which stores multiple characters using double quotes.
- Static typing, which is one of the safety features of Java.
- Variable naming conventions.
- For unchangeable variable : ```final``` before the variable's name -> `final int yearBorn = 1990`
- The void keyword (which means “completely empty”) indicates that no value is returned after calling that method.

```java
int age = 28;
char grade = 'A';
boolean late = true;
byte b = 20;
long num1 = 1234567;
short no = 10;
float k = (float)12.5;
double pi = 3.14;
```

## Operators 

- Addition (+=)
- Subtraction (-=)
- Multiplication (*=)
- Division (/=)
- Modulo (%=)
- equals() for comparing Strings and other objects

  #### The order is as follows:

  - Parentheses
  - Exponents
  -  Modulo/Multiplication/Division
  - Addition/Subtraction
