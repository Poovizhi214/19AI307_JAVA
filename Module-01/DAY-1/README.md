# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a class named 'Student' with String variable 'name' and String variable 'rollno'.

## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Student'
3.	Declare a String variable 'name' and initialize it with the value "John"
4.	Declare a String variable 'rollno' and initialize it with the value "21CSE03"
5.	Define a class named 'Test'
6.	Define the 'main' method within the 'Test' class
7.	Create an object 'obj' of the 'Student' class
8.	Print the value of 'name' and 'address' variables of the 'obj' object
9.	End



## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: POOVIZHI P
RegisterNumber:  212222020018
*/
```

## Sourcecode.java:
```
class Student {
    String name = "John";
    String rollno = "21CSE03";
}
public class Test {
    public static void main(String[] args) {
        Student obj = new Student();
        System.out.println(obj.name+" "+obj.rollno);
    }
}
```

## OUTPUT:
![Uploading image.png…]()


## RESULT:
Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.
