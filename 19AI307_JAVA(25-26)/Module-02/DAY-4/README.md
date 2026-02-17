# Ex.No:2(D) VARIABLE SCOPE AND CONSTRUCTOR

## QUESTION:

Write a class that uses a constructor to initialize variables and overrides toString() method.

input	

Ram

20

Result

Student{name='Ram', age=20}

## AIM:

To develop a Java program demonstrating VARIABLE SCOPE AND CONSTRUCTOR by initializing instance variables using a constructor and displaying the object details.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Define a class Student with private instance variables name and age.
4.	Create a constructor that initializes these variables using parameters.
5. Override the toString() method to display student details.
6. Declare the main class and main method.
7. Create a Scanner object to read input.
8. Read the name and age from the user.
9. Create an object of Student using the constructor.
10. Print the object details using System.out.println().
11. Close the Scanner object.
12. Stop the program.

## PROGRAM:
 ```
/*
Program to implement a Variable scope and Constructor using Java
Developed by: Hashwatha M
RegisterNumber: 212223240051
*/

import java.util.Scanner;

class Student {
    private String name;
    private int age;
    public Student(String name, int age) {
        this.name = name;
        this.age = age;
    }
    @Override
    public String toString() {
        return "Student{name='" + name + "', age=" + age + "}";
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        String name = sc.nextLine();
        int age = sc.nextInt();
        Student s = new Student(name, age);
        System.out.println(s);

        sc.close();
    }
}
```

## OUTPUT:

<img width="1163" height="610" alt="image" src="https://github.com/user-attachments/assets/5426c780-f67c-4037-bd57-d532aebd0beb" />

## RESULT:

Thus, the Java program demonstrating VARIABLE SCOPE AND CONSTRUCTOR was executed successfully, and the instance variables were initialized through the constructor and displayed correctly.
