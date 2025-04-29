# Ex.No:4(A)  JAVA CONSTRUCTOR
## AIM:
To create a Java program using constructor to print the circumference of rectangle.[l=5,w=6]

## ALGORITHM :
1. Start the Program.
2.	Define a class `circum`
3.	Inside the class, define two integer variables `l` and `w` with values 5 and 6, respectively
4.	Create a constructor `circum()`:
-	a) Calculate the `circumference` as `2 * (l + w)`
-	b) Print the `circumference` twice with different labels ("Area of First Rectangle" and "Area of Second Rectangle")
5.	In `main`, create an object `sc` of the `circum` class
6.	End

## PROGRAM:
 ```
/*
Program to implement a Constructor using Java
Developed by: POOVIZHI P 
RegisterNumber:  212222020018
*/
```

## Sourcecode.java:
~~~
class circum {
    int l = 5;
    int w = 6;
    circum() {
        int circumference = 2 * (l + w); 
        System.out.println("Area of First Rectangle: " + circumference);
        System.out.println("Area of Second Rectangle: " + circumference);
    }
}
public class Main {
    public static void main(String[] args) {
        circum sc = new circum(); 
    }
}
~~~
## OUTPUT:
~~~
Area of First Rectangle: 22
Area of Second Rectangle: 22
~~~
## RESULT:
Thus the Java program using constructor to print the circumference of rectangle was executed successfully.
