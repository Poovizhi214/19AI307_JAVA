# Ex.No:7(E)  POLYMORPHISM

## AIM:
To demonstrate method overloading in Java by defining multiple sum() methods with different parameter types, and performing addition operations based on user input.

## ALGORITHM :
```
1.Define a class HelloWorld with two sum() methods:
a)One takes two integers.
b)Another takes two doubles.
2.In the main() method:
a)Create a Scanner object to read input from the user.
b)Read two integers and two double values.
c)Call the appropriate sum() method based on input type.
3.Display the result of both integer and double additions.
```
## PROGRAM:
 ```
/*
Program to implement a Method Overloading in Java
Developed by: POOVIZHI P
RegisterNumber:  212222020018
*/
```

## Sourcecode.java:
```
import java.util.*;

public class HelloWorld{

        void sum(int a,int b){
    System.out.println(a+b);
   }
  void sum(double a,double b){
    System.out.println(a+b);
  }

  public static void main(String []args)
    {
  HelloWorld obj=new HelloWorld();
  Scanner sc=new Scanner(System.in);
  int a=sc.nextInt();
  int b=sc.nextInt();
  double c=sc.nextDouble();
  double d=sc.nextDouble();
  obj.sum(a,b);
  obj.sum(c,d);
     }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/a62c7255-16c5-4b0f-ad9e-e6c207ee5de6)


## RESULT:

Thus the  java program successfully demonstrates method overloading, showing compile-time polymorphism by calculating the sum of two and three numbers using methods with the same name but different parameter lists..


