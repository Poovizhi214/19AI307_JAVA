# Ex.No:2(C)    SINGLE ARRAY

## AIM:
To create a java program to read 5 values and display the all 5 values from array using single dimensional array.

## ALGORITHM :
1.	Start the program.
2.	2.	Import the `Scanner` class from the `java.util` package
3.	Define a class named `ArrayExample`
4.	Inside the `main` method:
-	a) Create a `Scanner` object called `scanner` to take user input
-	b) Declare an integer array `values` of size 5
-	c) Use a `for` loop to iterate from `i = 0` to `i < 5`:
-   d) Take input from the user and store it in `values[i]`
5.	Print "Elements in Array are :"
6.	Use another `for` loop to iterate from `i = 0` to `i < 5`:
-	a) Print each element in `values` followed by a space
7.	Close the `scanner` to release resources
8.	End





## PROGRAM:
 ```
/*
Program to implement a Single Array using Java
Developed by: POOVIZHI P
RegisterNumber:  212222020018
*/
```

## Sourcecode.java:
~~~
import java.util.Scanner;
public class ArrayExample {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in); 
        int[] values = new int[5];
        for (int i = 0; i < 5; i++) {
            values[i] = scanner.nextInt();
        }

        System.out.println("Elements in Array are : ");
        for (int i = 0; i < 5; i++) {
            System.out.print(values[i] + " ");
        }
        scanner.close(); 
    }
}
~~~
## OUTPUT:
~~~
INPUT:10 20 30 40 50
OUTPUT:Elements in Array are : 10 20 30 40 50
~~~

## RESULT:
Thus, the Java program Thus the java program to read 5 values and display the all 5 values from array using single dimensional  was executed successfully.


