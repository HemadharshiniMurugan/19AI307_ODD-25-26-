# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:
In a magical building, an elevator behaves oddly:

If the floor number is divisible by 3 and 5, it says "Skipped".

If the floor number is divisible by 3 only, it says "Beware!".

If the floor number is divisible by 5 only, it says "Blessings!".

Otherwise, it announces the floor number - print - "Floor {number}" .

Write a Java program to simulate this elevator logic for a given floor number.

## AIM:
To develop a Java program that simulates the behavior of a magical elevator by checking a given floor number and printing a special message based on its divisibility by 3 and/or 5.

## ALGORITHM :
1. Read the floor number from the user.
2. Check if the number is divisible by both 3 and 5.
3. If true, print "Skipped".
4. Else check if divisible by 3 or 5 and print the respective message.
5. Else print "Floor {number}".

## PROGRAM:
 ```
/*
Program to implement a conditional statement using Java
Developed by: Hemadharshini M
RegisterNumber: 212222040053
*/
```

## SOURCE CODE:
```
import java.util.*;
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int num=sc.nextInt();
        if(num%3==0 && num%5==0) System.out.print("Skipped");
        else if(num%3==0) System.out.print("Beware!");
        else if(num%5==0) System.out.print("Blessings!");
        else
        System.out.print("Floor "+num);
    }
}
```

## OUTPUT:



## RESULT:
Thus,the program correctly displays “Skipped”, “Beware!”, “Blessings!”, or “Floor <number>” based on the floor number’s divisibility.


