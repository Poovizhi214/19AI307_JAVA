# Ex.No:6(E)  MULTIPLE INHERITANCE

## AIM:
To write a Java program using multiple inheritance through interfaces to read student details and marks, calculate the average, and display the mark sheet.

## ALGORITHM :

1.	Start the program.
2.	Create interface Student:
a.	Declare methods to read name and rollno.
3.	Create interface Studentdet:
a.	Declare a method to read marks of 6 subjects and calculate the average.
b.	Create a class Studentdetails that implements both interfaces:
c.	Define variables for name, roll number, marks array, and average.
4.	Implement all methods from the interfaces.
a.	Create a display() method to show student details and average.
5.	In main() method:
a.	Create an object of Studentdetails.
b.	Call the methods to get input and display results.
6.	End the program.


## PROGRAM:
 ```
/*
Program to implement a Multiple Inheritance
Developed by: POOVIZHI P
RegisterNumber:  212222020018
*/
```

## Sourcecode.java:

```
import java.util.*;
class Input{
    static Scanner sc=new Scanner(System.in);
}
class Student{
    String name,reg_no;
    int m1,m2,m3,m4,m5;
    public void get_details(){
        name=Input.sc.next();
        reg_no=Input.sc.next();
    }
}
class Marks extends Student{
    public void get_marks(){
        m1=Input.sc.nextInt();
        m2=Input.sc.nextInt();
        m3=Input.sc.nextInt();
        m4=Input.sc.nextInt();
        m5=Input.sc.nextInt();
    }
}
class Percentage extends Marks{
    int total;
    float per;
    public void calc(){
        total=m1+m2+m3+m4+m5;
        per=(int)total/5;
    }
    public void display(){
        System.out.println("Student Name is "+name);
        System.out.println("Registeration Number is "+reg_no);
        System.out.println("Total is "+total);
        System.out.println("Percentage is "+(float)per);
    }
}
public class Main{
    public static void main(String[] args){
        Percentage obj=new Percentage();
        obj.get_details();
        obj.get_marks();
        obj.calc();
        obj.display();
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/aff6aadc-42a8-4d82-ac4b-0c7efcfc5e8d)

## RESULT:

Thus, the java program demonstrates multiple inheritance using interfaces and successfully displays the mark sheet of a student by collecting personal and academic data. 
