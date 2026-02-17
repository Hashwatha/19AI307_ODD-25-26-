# Ex.No:2(C) ACCESS SPECIFIERS

## QUESTION:

Write a Java program to create a class called Person with private instance variables name, age. and country. Provide public getter and setter methods to access and modify these variables.

public class Person {
  
    private String name;
    private int age;
    private String country;

   
    public String getName() {
        return name;
    }
    public void setName(String name) {
        this.name = name;
    }

    
    public int getAge() {
        return age;
    }
    public void setAge(int age) {
        this.age = age;
    }

    
    public String getCountry() {
        return country;
    }
    public void setCountry(String country) {
        this.country = country;
    }
}

Continue your code



## AIM:

To develop a Java program using ACCESS SPECIFIERS to demonstrate data hiding by declaring class variables as private and accessing them through public getter and setter methods.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Define a class Person with private data members: name, age, and country.
4.	Create public getter and setter methods to access and modify the private variables.
5.	Declare the main class and main method.
6.	Create a Scanner object to read input from the user.
7.	Create an object p of class Person.
8.	Read the name, age, and country from the user.
9.	Set the values using setter methods.
10.	Retrieve the values using getter methods.
11.	Display the person details.
12.	Close the Scanner object.
13.	Stop the program.

## PROGRAM:
 ```
/*
Program to implement a Access Specifiers using Java
Developed by: Hashwatha M
RegisterNumber: 212223240051
*/

import java.util.Scanner;
public class Main {
    static class Person {
        private String name;
        private int age;
        private String country;
        public String getName() {
            return name;
        }
        public void setName(String name) {
            this.name = name;
        }
        public int getAge() {
            return age;
        }
        public void setAge(int age) {
            this.age = age;
        }
        public String getCountry() {
            return country;
        }
        public void setCountry(String country) {
            this.country = country;
        }
    }
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        Person p = new Person();
        String name = sc.nextLine();
        int age = sc.nextInt();
        sc.nextLine(); // consume newline
        String country = sc.nextLine();
        p.setName(name);
        p.setAge(age);
        p.setCountry(country);
        System.out.println("Person 1");
        System.out.println("Name: "+p.getName());
        System.out.println("Age: "+p.getAge());
        System.out.println("Country: "+p.getCountry());
        sc.close();
    }
}
```

## OUTPUT:

<img width="1195" height="681" alt="image" src="https://github.com/user-attachments/assets/c1f41343-7661-401b-941b-7f8ee1d0fe68" />

## RESULT:

Thus, the Java program using ACCESS SPECIFIERS was executed successfully, demonstrating data encapsulation by restricting direct access to variables and accessing them through getter and setter methods.
