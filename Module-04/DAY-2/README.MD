# Ex.No:4(B) INTRODUCTION TO JAVA INHERITANCE

## AIM:
To write a Java program that defines a Student class containing a student ID and an object of a Subject class which holds subject details.

## ALGORITHM :
~~~
1.Start the Program.
2.Define class Subject:
a)Declare instance variables sub1, sub2, sub3, and sub4 to store subject names.
b)Create a constructor Subject(String s1, String s2, String s3, String s4) to initialize these subject variables.
c)Define method dispSub() to display all subjects.
3.Define class Student:
a)Declare an instance variable Stu_Id to store the student ID.
b)Create an object obj of the Subject class, initializing it with "Java", "DS", "TOC", and "CG".
c)Define method disp(int id) 
4.Define the Main class:
a)In the main method, create an object obj1 of the Student class.
b)Call the disp() method of obj1, passing 101 as the argument to display the student ID and subject details.
5.End the Program.
~~~
## PROGRAM:
 ```
/*
Program to implement a Inheritance using Java
Developed by: POOVIZHI P
RegisterNumber:  212222020018
*/
```
## Sourcecode.java:
~~~
class Subject
{
    String sub1;
    String sub2;
    String sub3;
    String sub4;
    Subject(String s1,String s2,String s3,String s4){
        this.sub1=s1;
        this.sub2=s2;
        this.sub3=s3;
        this.sub4=s4;
    }
    void dispSub()
    {
        System.out.println(sub1+" "+sub2+" "+sub3+" "+sub4);
    }
}
class Student 
{
    int Stu_Id;
    Subject obj=new Subject("Java","DS","TOC","CG");
    void disp(int id)
    {
        this.Stu_Id=id;
          System.out.println(Stu_Id);
       obj.dispSub();
    }
}
public class Main
{
    public static void main(String[] args)
    {
        Student obj1=new Student();
        obj1.disp(101);
        
    }
}
~~~
## OUTPUT:
~~~
101
Java DS TOC CG
~~~
## RESULT:
The Java program correctly displays the student ID and the subjects for a given student was executed successfully.

