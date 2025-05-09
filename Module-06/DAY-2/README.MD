# Ex.No:6(B) MULTI-LEVEL INHERITANCE

## AIM:
To Develop a Java program to perform Multilevel Inheritance to calculate the area of circle..

## ALGORITHM :
1.	Start the Program.
2.	Define class `Shapes`:
-	a) Method `print_shape()` to print "Shapes Class"
3.	Define class `Circle` that extends `Shapes`:
-	a) Declare integer `rad`
-	b) Method `get()` to read `rad` from user input
4.	Define class `Area` that extends `Circle`:
-	a) Method `cal()` to calculate `result = 3.14 * rad * rad` and print "Area of Circle is " followed by `result`
5.	In `Main` class `main` method:
-	a) Create `Area` object `obj`
-	b) Call `print_shape()`, `get()`, and `cal()` on `obj` to display shape type, read radius, and calculate area
6.	End


## PROGRAM:
 ```
/*
Program to implement a MultiLevel Inheritance using Java
Developed by: POOVIZHI P
RegisterNumber:  212222020018
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

class Shapes {
    void print_shape() {
        System.out.println("Shapes Class");
    }
}

class Circle extends Shapes {
    private int radius;
    public void set() {
        Scanner sc = new Scanner(System.in);
        radius = sc.nextInt();
    }

    public int getRad() {
        return radius;
    }
}

class Area extends Circle {
    void calc() {
        int radius = getRad();
        System.out.println("Area of Circle is " + 3.14 * radius * radius);
    }
}

public class Main {
    public static void main(String[] args) {
        Area obj = new Area();
        obj.print_shape();
        obj.set();
        obj.calc();
    }
}
```


## OUTPUT:
https://github.com/Poovizhi214/19AI307_JAVA/blob/e25ceb1339a9f61523f5b7d0d284c90edc55925b/Module-06/DAY-2/inheritance.png

## RESULT:
Thus the java program for multi-level inheritance was executed successfully.





