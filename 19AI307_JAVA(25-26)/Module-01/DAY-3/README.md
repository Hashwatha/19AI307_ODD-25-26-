# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:
A left-aligned triangle pattern is a pattern of stars (*) where each row contains an increasing number of stars, aligned to the left side.

Write a Java program that:

Prompts the user to enter the number of rows for the triangle.

Uses nested loops to print the left-aligned triangle pattern.

Ensures that each row contains stars corresponding to its row number.

For example:

Input	Result

3

*

* *

* * *


## AIM:
To write a Java program using looping statements to print a left-aligned triangle star pattern based on the number of rows entered by the user.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read the number of rows from the user.
4.	Use an outer loop to control the number of rows.
5.	Use an inner loop to print stars (*) in each row.
6.	Print stars equal to the current row number.
7.	Move to the next line after printing stars in each row.
8.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement a Looping Statement using Java
Developed by: HASHWATHA M
RegisterNumber: 212223240051
*/

import java.util.Scanner;

public class LeftAlignedTriangle {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int rows = sc.nextInt();
        for (int i = 1; i <= rows; i++) {
            for (int j = 1; j <= i; j++) {
                System.out.print("* ");
            }
            System.out.println();
        }
    }
}

```

## OUTPUT:

<img width="1247" height="854" alt="Screenshot 2026-02-03 092448" src="https://github.com/user-attachments/assets/e1df9379-8f9a-46cd-bd4b-bb28e5337d78" />


## RESULT:

Thus, the Java program using looping statements to print a left-aligned triangle star pattern was successfully executed and the output was verified.

