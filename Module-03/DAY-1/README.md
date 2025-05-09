# Ex.No:3(A)  STRING AND ITS OPERATIONS IN JAVA
## AIM:
To create a java program to read input and print length of the string in java.

## ALGORITHM :
1.  Start the Program.
2.	Import `Scanner` and define class `demo`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read a line of text into `String` variable `str`
4.	Print "The size of the String is " + `str.length()`
5.	End

## PROGRAM:
 ```
/*
Program to implement a String and its Operations using Java
Developed by: POOVIZHI P
RegisterNumber:  212222020018
*/
```
## Sourcecode.java:
~~~
import java.util.*;
public class demo {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in); 
        String str = sc.nextLine(); 
        System.out.println("The size of the String is " + str.length());
        sc.close(); 
    }
}
~~~
## OUTPUT:
![image](https://github.com/user-attachments/assets/ca7b2344-98db-405e-8204-ee66020dd204)

## RESULT:
Thus the java Program to read input and print length of the string in java was executed successfully.

