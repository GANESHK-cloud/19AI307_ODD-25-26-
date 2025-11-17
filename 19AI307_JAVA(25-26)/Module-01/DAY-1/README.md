
# Ex.No:1(A) INTRODUCTION TO JAVA PROGRAMMING, DATA TYPES, VARIABLES AND OPERATORS 

## QUESTION:
Lovely has mastered printing in Java, and now she wants to learn how arithmetic operators work. She’s curious about how Java can add, subtract, multiply, divide, and find remainders of two numbers.

Write a Java program that:

Accepts two integer numbers from the user.

Demonstrates all 5 arithmetic operations:

Addition (+)

Subtraction (-)

Multiplication (*)

Division (/)

Modulus (%)

Displays the result of each operation in a separate line with a clear message.

Input Format
First line: Integer → first number

Second line: Integer → second number

Output Format
Each line shows the result of an arithmetic operation in this format:


Sum = <value>
Difference = <value>
Product = <value>
Quotient = <value>
Remainder = <value>
Ensure integer division and modulus are correctly handled. Assume the second number will not be 0.

## For example:
```
---------------------------
Input	       Result 
10        |  Sum = 13
3         |  Difference = 7
          |  Product = 30
          |  Quotient = 3
          |  Remainder = 1
-----------------------------

```
## AIM

To implement variables and operators in Java using basic arithmetic operations.

## ALGORITHM

Start the program.

Declare the required variables.

Assign values to the variables.

Perform arithmetic operations using operators.

Display all results.

## PROGRAM
```
Program to implement Variables and Operators using Java
Developed by: Ganesh K
RegisterNumber: 212222060057
```

## Sourcecode 

```java
public class Sourcecode {
    public static void main(String[] args) {

        int a = 10;
        int b = 20;

        int sum = a + b;
        int diff = a - b;
        int product = a * b;
        int div = b / a;
        int mod = b % a;

        System.out.println("A = " + a);
        System.out.println("B = " + b);
        System.out.println("Sum = " + sum);
        System.out.println("Difference = " + diff);
        System.out.println("Product = " + product);
        System.out.println("Division = " + div);
        System.out.println("Modulus = " + mod);
    }
}
```

## OUTPUT


<img width="1237" height="433" alt="image" src="https://github.com/user-attachments/assets/3b116eb2-eb16-4746-9485-866a232c508a" />


## RESULT

The Java program to demonstrate variables and operators was executed successfully.


