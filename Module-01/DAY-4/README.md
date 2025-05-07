# Ex.No:1(D) USER DEFINED METHOD.

## AIM:
To create a Java program to print the area of a circle by defining an instance method and using a local variable with value 2.
[Class Name is ‘Circle’ function name is ‘calculateArea()’ and return type of function is ‘void’]

## ALGORITHM :
~~~
1.Start the program.
2.Define a class named Circle.
3.Declare a public method named calculateArea with no parameters.
4.Inside the calculateArea method:
a) Declare a double variable radius and assign it the value 2.0
b) Calculate the area using the formula area = 3.14 * radius * radius
c) Store the result in a double variable named area
d) Print the calculated area using the System.out.println statement
5.Define the main method as static.
6.Inside the main method:
a) Create an instance of the Circle class called circleObj
b) Call the calculateArea method on the circleObj object
~~~
## PROGRAM:
 ```
/*
Program to implement a User Defined Method using Java
Developed by: POOVIZHI P
RegisterNumber:  212222020018
*/
```

## Sourcecode.java:
~~~
public class Circle {
    public void calculateArea() {
        double radius = 2.0;
        double area = 3.14 * radius * radius;
        System.out.println("Area of the circle: " + area);
    }

    public static void main(String[] args) {
        Circle circleObj = new Circle();
        circleObj.calculateArea();
    }
}
~~~
## OUTPUT:
![image](https://github.com/user-attachments/assets/4f519883-de18-4391-a8d2-1e85dd4bbac6)


## RESULT:
Thus, the Java program to print the area of a circle by defining an instance method and using a local variable with value 2.0 was successfully created and executed, producing the correct output.

