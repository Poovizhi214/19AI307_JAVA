# Ex.No:2(B) ACCESS MODIFIERS

## AIM:
To develop a Java Program to demonstrate the Default Access Modifier and print whether the given year is a leap year or not.
## ALGORITHM :
1.Start the program.
2.Define a class named LeapYearChecker.
3.Declare an integer variable year with default access.
4.Define a default method checkLeapYear() that: 
a) Checks if the year is divisible by 4.
b) If divisible by 100, then it must also be divisible by 400 to be a leap year. 
c) Prints whether the year is a leap year or not using System.out.println.
5.Define a public method setYear(int y) to assign the value to year.
6.Define the main method as static: 
a) Create an instance of LeapYearChecker class. 
b) Call the setYear() method to assign a year. 
c) Call the checkLeapYear() method.
7.End.

## PROGRAM:
 ```
/*
Program to implement a access modifiers using Java
Developed by: POOVIZHI P
RegisterNumber:  212222020018
*/
```

## Sourcecode.java:
~~~
class LeapYearChecker {
    int year; 
    void checkLeapYear() { 
        if ((year % 4 == 0 && year % 100 != 0) || (year % 400 == 0)) {
            System.out.println(year + " is a leap year.");
        } else {
            System.out.println(year + " is not a leap year.");
        }
    }
   public void setYear(int y) {
        year = y;
    }
     public static void main(String[] args) {
        LeapYearChecker lyc = new LeapYearChecker();
        lyc.setYear(2024);  
        lyc.checkLeapYear();
    }
}
~~~
## OUTPUT:
~~~
INPUT:2001
OUTPUT:2001 is not a leap year.
~~~
## RESULT:
Thus the Java program to demonstrate the default access modifier and check if a year is a leap year was executed successfully.




