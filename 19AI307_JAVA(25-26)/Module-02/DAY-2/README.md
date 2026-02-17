# Ex.No:2(B) METHODS

## QUESTION:

Write a method boolean isEven  (int num) without using % operator that returns true if the number is even.

For example:

Input	

3

Result

false

## AIM:

To develop a Java program using METHODS to check whether a given number is even or odd by defining and invoking a user-defined method.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package java.util.Scanner.
3.	Define a class NumberCheck.
4.	Create a method isEven(int num) that checks whether the number is even and returns a boolean value.
5.	Define the main class and main method.
6.	Create a Scanner object to read input from the user.
7.	Read an integer value from the user.
8.	Create an object of class NumberCheck.
9.	Call the method isEven() using the object and pass the input number.
10.	Display the returned result.
11.	Close the Scanner object.
12.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement a Methods using Java
Developed by: Hashwatha M
RegisterNumber: 212223240051
*/

import java.util.Scanner;
class NumberCheck 
{
    boolean isEven(int num)
    {
        return (num / 2) * 2 == num;
    }
}
class prog {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        NumberCheck nc = new NumberCheck();
        System.out.println(nc.isEven(n));
        sc.close();
    }
}
```

## OUTPUT:

<img width="986" height="421" alt="Screenshot 2026-02-17 084225" src="https://github.com/user-attachments/assets/3486cc2c-fd92-424f-8d75-320735227123" />

## RESULT:

Thus, the Java program using METHODS was executed successfully, and the method correctly determined whether the given number is even or not and displayed the result.
