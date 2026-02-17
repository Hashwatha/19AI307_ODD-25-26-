# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:

Write a Java program to convert a given string from lowercase to uppercase.

Input	

hello

Result

Upper case String is :HELLO

## AIM:

To develop a Java program using STRINGS AND MATH FUNCTION concepts to read a string from the user and convert the given lowercase string into uppercase using built-in string functions.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package java.util.Scanner.
3.	Declare the class and main method.
4.	Create a Scanner object to read input from the user.
5.	Read a string from the user using nextLine().
6.	Convert the input string into uppercase using the string function toUpperCase().
7.	Display the converted uppercase string.
8.	Close the Scanner object.
9.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
Developed by: Hashwatha M
RegisterNumber: 212223240051
*/

import java.util.Scanner;

public class LowerToUpper {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        String str = sc.nextLine();

        String upper = str.toUpperCase();

        System.out.println("Upper case String is :" + upper);

        sc.close();
    }
}
```

## OUTPUT:

<img width="1202" height="457" alt="image" src="https://github.com/user-attachments/assets/e9ad6354-337c-451e-a52b-5500d010505d" />

## RESULT:

Thus, the Java program using STRINGS AND MATH FUNCTION concepts was executed successfully, and the given input string was converted into uppercase and displayed as output.
