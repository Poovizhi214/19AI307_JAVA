# Ex.No:4(E)  PARAMETERIZED CONSTRUCTOR
## AIM:
To write a parameterized constructor in the Employee class that initializes name and designation, and then call getter methods in the main() method of another class (Sample) to display the values.

## ALGORITHM :
~~~
1.	Start the program.
2.	Define a class Employee:
    a.	  Declare two private string variables: name and designation.
3.	Create a parameterized constructor in Employee:
4.	Accept two parameters: name and designation.
5.	Assign the parameters to the class fields.
6.	Define two getter methods in the Employee class:
     a.	getName() – returns the value of name.
     b.	getDesg() – returns the value of designation.
7.	Create another class Sample with the main method.
8.	Inside the main method:
     a.	Create an object of Employee using the constructor and pass "John" and "Asst.Manager" as arguments.
     b.	Call getName() and store the result in a variable empName.
     c.	Call getDesg() and store the result in a variable empDesg.
9.	Print the values of empName and empDesg.
10.	End the program
~~~

## PROGRAM:
 ```
/*
Program to implement a Parameterized Constructor Using Java
Developed by: POOVIZHI P
RegisterNumber:  212222020018
*/
```

## Sourcecode.java:
~~~
class Employee {
    private String name;
    private String designation;
    Employee(String name, String designation) {
        this.name = name;
        this.designation = designation;
    }
    public String getName() {
        return name;
    }
    public String getDesg() {
        return designation;
    }
}
public class Sample {
    public static void main(String[] args) {
        Employee emp = new Employee("John", "Asst.Manager");
        String empName = emp.getName();
        String empDesg = emp.getDesg();
        System.out.println("Employee Name: " + empName);
        System.out.println("Employee Designation: " + empDesg);
    }
}
~~~

## OUTPUT:
~~~
Employee Name: John
Employee Designation: Asst.Manager
~~~

## RESULT:
Thus, the  java program was successfully demonstrates the use of a parameterized constructor to initialize class fields.

 


