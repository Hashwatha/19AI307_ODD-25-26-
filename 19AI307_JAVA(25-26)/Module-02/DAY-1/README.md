# Ex.No:2(A) CLASS AND OBJECT

## QUESTION:
Create a class Vehicle with attributes as number, type and owner.

For example:

Input	

TN10AB1234 Car Ravi

TN22CD5678 Bike Meena

Result

TN10AB1234 | Car | Ravi

TN22CD5678 | Bike | Meena

## AIM:

To develop a Java program using CLASS AND OBJECT concepts to store and display vehicle details by creating objects of a class and accessing their data members.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package java.util.Scanner.
3.	Define a class named Vehicle with data members: number, type, and owner.
4.	Declare the main class and main method.
5.	Create a Scanner object to read input.
6.	Create the first object v1 of class Vehicle.
7.	Read vehicle details and assign them to v1.
8.	Create the second object v2 of class Vehicle.
9.	Read vehicle details and assign them to v2.
10.	Display the details of both vehicles using object references.
11.	Close the Scanner object.
12.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement a Class and Objects using Java
Developed by: Hashwatha M
RegisterNumber: 212223240051
*/

import java.util.Scanner;

class Vehicle {
    String number;
    String type;
    String owner;
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        Vehicle v1 = new Vehicle();
        v1.number = sc.next();
        v1.type = sc.next();
        v1.owner = sc.next();

        Vehicle v2 = new Vehicle();
        v2.number = sc.next();
        v2.type = sc.next();
        v2.owner = sc.next();

        System.out.println(v1.number + " | " + v1.type + " | " + v1.owner);
        System.out.println(v2.number + " | " + v2.type + " | " + v2.owner);

        sc.close();
    }
}

```

## OUTPUT:

<img width="1156" height="493" alt="image" src="https://github.com/user-attachments/assets/8c6a687b-9c45-446d-89cb-91a7cdddb693" />

## RESULT:

Thus, the Java program using CLASS AND OBJECT concepts was executed successfully, and the vehicle details were stored using objects and displayed as output.
