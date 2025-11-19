
# EX 1A Print All Numbers 
## DATE: 19/11/2025
## AIM:
To Write a Java program that takes an integer input N from the user and prints all the numbers from 1 to N, separated by spaces, on a single line..

## Algorithm
1. Start the program and import the Scanner class to take user input.
2. Create a Scanner object to read an integer input N from the user.
3. Check if N is greater than 0; if not, display "Invalid input. N must be greater than 0."
4. Use a for loop to iterate from 1 to N.
5. Print each number separated by a space on the same line.

## Program:
```
/*
Program to implement Print all numbers
Developed by: SARANYA S.
Register Number: 212223220101
*/

import java.util.Scanner;
public class java{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        for(int i=1;i<=n;i++){
            System.out.print(i+" ");
        }
    }
}
```

## Output:

<img width="1109" height="302" alt="image" src="https://github.com/user-attachments/assets/dfc8dbee-d9f2-417d-b881-389c95a10bc7" />

## Result:
The program successfully print all the numbers from 1 to N. 
