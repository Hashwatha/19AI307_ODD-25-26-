# Ex.No:2(E) ACCESS MODIFIERS

## QUESTION:

Create a class Calculator with: One non-static method add(int a, int b) that returns the sum, One static method info() that says "Calculator is ready".

For example:

Input	

10

20

Result

Calculator is ready

Sum: 30


## AIM:

To develop a Java program demonstrating ACCESS MODIFIERS by accessing class methods with different access levels and performing addition using a calculator class.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Define a class Calculator.
4.	Create a static method show() to display a message.
5.	Define a method sum(int a, int b) to calculate the sum of two numbers.
6.	Declare the main class and main method.
7.	Create a Scanner object to read input values.
8.	Call the static method show() using the class name.
9.	Read two integer values from the user.
10.	Create an object of Calculator.
11.	Call the sum() method using the object.
12.	Display the result.
13. Stop the program	

## PROGRAM:
 ```
/*
Program to implement a Access Modifiers using Java
Developed by: Hashwatha M
RegisterNumber: 212223240051
*/

import java.util.Scanner;

class Calculator 
{
    static void show()
    {
        System.out.println("Calculator is ready");
    }
    int sum(int a,int b)
    {
        return a+b;
    }
}

class prog {
    public static void main(String[] args) 
    {
        Scanner sc=new Scanner(System .in);
        Calculator.show();
        int x=sc.nextInt();
        int y=sc.nextInt();
        Calculator calc=new Calculator();
        int result=calc.sum(x,y);
        System.out.println("Sum: "+result);
    }
}
```

## OUTPUT:

<img width="1052" height="570" alt="image" src="https://github.com/user-attachments/assets/8e15684e-3d39-4e05-8818-a209dedbd9d3" />

## RESULT:

Thus, the Java program demonstrating ACCESS MODIFIERS was executed successfully, and the methods were accessed appropriately to perform addition and display the result.
