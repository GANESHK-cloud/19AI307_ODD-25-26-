# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:

Write a Java program to calculate the factorial of a number using a for loop. The factorial of n is the product of all positive integers less than or equal to n.

## Example:
```
---------------------------
Input	       Result 
0        |  Factorial of 0 is: 1
-----------------------------
```

## AIM:

To write a Java program using a looping statement (for loop) to find the factorial of a given number.

## ALGORITHM :
1.Start the program.

2.Import the necessary package java.util.

3.Read an integer value n from the user.

4.Initialize a variable fact to 1.

5.Use a for loop from 1 to n to multiply the values and calculate factorial.

6.Display the factorial result.

7.Stop the program.



## PROGRAM:
 ```

Program to implement a Looping Statement using Java
Developed by: Ganesh K
RegisterNumber:  212222060057

```

## SOURCE CODE:
```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        long fact = 1;

        for (int i = 1; i <= n; i++) {
            fact *= i;
        }

        System.out.println("Factorial of " + n + " is: " + fact);
    }
}


```


## OUTPUT:

<img width="1239" height="414" alt="Screenshot 2025-11-16 234519" src="https://github.com/user-attachments/assets/37512c1a-c072-44f3-b07d-04778c18169b" />

## RESULT:

Thus, the Java program to calculate the factorial of a number using a looping statement was executed successfully.


