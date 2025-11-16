# Ex.No:1(D) ARRAYS

## QUESTION:

Write a Java Program to count Even and Odd Numbers in an Array.

For example:
----------------------------------------
Input	       Result 
5         |  Number of even elements: 2
1         |  Number of odd elements: 3
2         
3
4
5        
-----------------------------------------

## AIM:

To write a Java program using loops to count the number of even and odd elements in an array.

## ALGORITHM :

1.Start the program.

2.Import the package java.util.Scanner.

3.Read the number of elements n from the user.

4.Create an array of size n.

Read all array elements using a loop.

5.If an element is divisible by 2, increment even counter; else increment odd counter.

6.Display the number of even and odd elements.

7.End the program.


## PROGRAM:
 ```

Program to implement a Array concept using Java
Developed by: Ganesh k
RegisterNumber:  212222060057

```

## SOURCE CODE:

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int[] arr = new int[n];
        int evenCount = 0, oddCount = 0;

        for (int i = 0; i < n; i++) {
            arr[i] = sc.nextInt();
            if (arr[i] % 2 == 0) {
                evenCount++;
            } else {
                oddCount++;
            }
        }

        System.out.println("Number of even elements: " + evenCount);
        System.out.println("Number of odd elements: " + oddCount);
    }
}


```


## OUTPUT:



## RESULT:

Thus, the Java program to count even and odd numbers in an array was executed successfully.
