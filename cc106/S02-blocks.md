---
sidebar_position: 3
---

# S02 - Basic Programming Blocks

## Java Hello world!

1. Edit `HelloWorld.java` and write the following program.

```java title="HelloWorld.java"
/** 
 * The program displays Hello world to the console.
 * @version 1.0.0 16.07.2023
 * @author Mehrshad Lotfi 
 */
public class HelloWorld
{
  public static void main(String[] args)
  {
    System.out.println("Hello world!");
    System.out.println("============");
  }
}
```

2. Run the following commands to compile and run the code.
```bash
$ javac HelloWorld.java
$ java HelloWorld
Hello world!
============
```


## Download and run karel.jar

Use the instruction from the the GitHub repository
[fredoverflow/karel](https://github.com/fredoverflow/karel)

## Programming blocks

### `for` loop
A `for` loop is a control flow statement used to iterate over 
a block of code repeatedly until a certain condition is met.
It is often used when the number of iterations or the range 
of values to iterate over is known.

The syntax of a for loop in Java is as follows:
```java
for (initialization; condition; update) {
    // code to be executed repeatedly
}
```
Here's an example to demonstrate a simple `for` loop in Java:
```java
for (int i = 1; i <= 5; i++) {
    System.out.println("Iteration: " + i);
}
```

### `while` loop
A `while` loop is a control flow statement that repeatedly 
executes a block of code as long as a given condition is true.
It is commonly used when the number of iterations or the 
termination condition is not known in advance.

The syntax of a while loop in Java is as follows:
```java
while (condition) {
    // code to be executed repeatedly
}
```

Here's an example to demonstrate a simple `while` loop in Java:
```java
int i = 1;
while (i <= 5) {
    System.out.println("Iteration: " + i);
    i++;
}
```

### `if-else` statement
The `if-else` statement is used for conditional execution 
of code. It allows you to specify different blocks of code 
to be executed based on the evaluation of a certain condition. 
The `if-else` statement evaluates a Boolean expression, and 
depending on whether the expression is `true` or `false`,
it executes the corresponding block of code.

The syntax of the if-else statement in Java is as follows:

```java
if (condition) {
    // code to be executed if the condition is true
} else {
    // code to be executed if the condition is false
}
```

Here's an example to demonstrate the usage of `if-else` 
statement in Java:

```java
int number = 10;

if (number > 0) {
    System.out.println("The number is positive.");
} else {
    System.out.println("The number is non-positive.");
}
```
