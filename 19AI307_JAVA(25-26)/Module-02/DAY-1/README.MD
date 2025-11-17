# Ex.No:2(A) CLASS AND OBJECT

## QUESTION:
Define a class Car with brand (String), color (String), and year (int). Create 2 different objects of Car  Assign values to attributes. Print the details of both cars.

Example:
```
---------------------------
Input	       Result 
Toyota   | Brand: Toyota
Red      | Color: Red
2015     | Year: 2015
Honda    | Brand: Honda
Blue     | Color: Blue
2018     | Year: 2018
-----------------------------
```
## AIM:

To write a Java program that demonstrates the use of classes and objects by defining a Car class and creating objects with assigned attributes.

## ALGORITHM :

1.Start the program.

2.Create a class named Car with attributes brand, color, and year.

3.Create a method to display car details.

4.In the main method, create two objects of Car.

5.Assign values to object attributes.

6.Call the display method to print details.

7.End the program.

## PROGRAM:
 ```

Program to implement a Class and Objects using Java
Developed by: Ganesh k
RegisterNumber:  212222060057

```

## SOURCE CODE:
```java
import java.util.*;

class Car {
    String brand;
    String color;
    int year;

    void display() {
        System.out.println("Brand: " + brand);
        System.out.println("Color: " + color);
        System.out.println("Year: " + year);
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        Car c1 = new Car();
        c1.brand = sc.nextLine();
        c1.color = sc.nextLine();
        c1.year = Integer.parseInt(sc.nextLine());

        Car c2 = new Car();
        c2.brand = sc.nextLine();
        c2.color = sc.nextLine();
        c2.year = Integer.parseInt(sc.nextLine());

        c1.display();
        c2.display();
    }
}

```

## OUTPUT:




## RESULT:

Thus, the Java program to implement Class and Object using a Car class was executed successfully.


