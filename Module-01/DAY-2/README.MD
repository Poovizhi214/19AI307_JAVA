# Ex.No:1(B) VARIABLES AND OPERATOR

## AIM:
To write a Java program to get values of variables 'a' and 'b' and then check if both the conditions 'a < 50' and 'a < b' are true. [Class name is ‘Demo’]

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Define a class named 'Demo'
4.	Implement the main method
5.	Create a new instance of the 'Scanner' class named 'sc' to read user input
6.	Read an integer 'a' from the user using the 'nextInt' method of 'sc'
7.	Read another integer 'b' from the user using the 'nextInt' method of 'sc'
8.	Check if 'a' is less than 50 or if 'a' is less than 'b'
a)	If the condition is true, print "true" using the 'print' method of 'System.out'
b)	If the condition is false, print "false" using the 'print' method of 'System.out'
9.	End

## PROGRAM:
 ```
/*
Program to implement a variable and operators using Java
Developed by: POOVIZHI P
RegisterNumber: 212222020018
*/
```

## Sourcecode.java:
~~~
import java.util.*;
public class Demo
{
    public static void main(String[] args){
    Scanner sc=new Scanner(System.in);
    int a = sc.nextInt();
    int b = sc.nextInt();
    System.out.println(a < 50 && a < b);
    }
}
~~~
## OUTPUT:
https://github.com/Poovizhi214/19AI307_JAVA/blob/5468fbe7294c953ddeef184450ed41ef37d34de8/Module-01/DAY-2/variables.png
## RESULT:
Thus, the Java program to get values of variables 'a' and 'b' and then check if both the conditions 'a < 50' and 'a < b' are true is created successfully.
