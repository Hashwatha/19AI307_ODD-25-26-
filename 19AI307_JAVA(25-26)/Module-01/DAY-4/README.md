# Ex.No:1(D) ARRAYS

## QUESTION:
Write a Java program to print all prime numbers present in an array

 
For example:

Input	

5

1

2

3

4

5

Result

2

3

5


## AIM:
To write a Java program using an array to find and print all prime numbers present in the given array elements.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read the number of elements in the array.
4.	Read the array elements from the user.
5.	For each element in the array:

    1. Check whether the number is greater than 1.
    2. Count the number of factors using a loop.
    3. If the number has exactly two factors, it is a prime number.
6. Print all the prime numbers present in the array.
7. Stop the program.

## PROGRAM:
 ```
/*
Program to implement a Array concept using Java
Developed by: HASHWATHA M
RegisterNumber: 212223240051
*/

import java.util.Scanner;
public class Main{
    public static boolean isPrime(int n){
        if(n<=1) return false;
        for(int i=2;i<=Math.sqrt(n);i++){
            if(n%i==0) return false;
        }
        return true;
    }
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        int[] a=new int[n];
        for(int i=0;i<n;i++){
            a[i]=sc.nextInt();
        }
        boolean found=false;
        for(int i=0;i<n;i++){
            if(isPrime(a[i])){
                System.out.println(a[i]);
                found=true;
            }
        }
        if(!found){
            System.out.println("No prime numbers found");
        }
    }
}
```

## OUTPUT:

<img width="1178" height="861" alt="image" src="https://github.com/user-attachments/assets/6e26d309-db9f-4bc8-ad76-78bdf519fde5" />

## RESULT:
Thus, the Java program using an array to identify and print all prime numbers was successfully executed and the output was verified.
