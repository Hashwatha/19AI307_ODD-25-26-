# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:
Given a month number (1 to 12), print which quarter of the year it belongs to:

Months 1,2,3 → "First Quarter"

Months 4,5,6 → "Second Quarter"

Months 7,8,9 → "Third Quarter"

Months 10,11,12 → "Fourth Quarter"
If the number is not in 1-12, print "Invalid Month".

Write a java program to get the month from user and and display appropriate output for the given input.

For example:

Input	Result
2
First Quarter


## AIM:
To write a Java program using conditional statements to read a month number from the user and display the corresponding quarter of the year.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read the month number from the user.
4.	If the month is 1, 2, or 3, display “First Quarter”.
5.	Else if the month is 4, 5, or 6, display “Second Quarter”.
6.	Else if the month is 7, 8, or 9, display “Third Quarter”.
7.	Else if the month is 10, 11, or 12, display “Fourth Quarter”.
8.	Else, display “Invalid Month”.
9.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement a conditional statement using Java
Developed by: HASHWATHA M
RegisterNumber: 212223240051
*/

import java.util.Scanner;
public class Main{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        int month = sc.nextInt();
        
        if(month >= 1 && month <= 3){
            System.out.println("First Quarter");
        }
        else if(month>=4&&month<=6)   { 
            System.out.println("Second Quarter");
        }
        else if(month>=7&&month<=9){
            System.out.println("Third Quarter");
        }
        else if(month>=10&&month<=12){
            System.out.println("Fourth Quarter");
        }
        else{
            System.out.println("Invalid Month");
        }
        sc.close();
    }
}
```

## OUTPUT:

<img width="1103" height="576" alt="image" src="https://github.com/user-attachments/assets/1cf0a90e-eadc-4b6e-8bd6-50e6a711904c" />

## RESULT:
Thus, the Java program to determine the quarter of the year based on the given month number was successfully executed and the output was verified.
