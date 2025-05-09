# Ex.No:7(B) EXCEPTION HANDLING-FINALLY
## AIM:
To demonstrate the use of try-catch-finally blocks in handling ArrayIndexOutOfBoundsException in Java.

## ALGORITHM :
1.Start the program.
2.Declare and initialize an integer array numbers with elements {1, 2, 3}.
3.Enter the try block:
a)Attempt to access the element at index 5 of the array.
b)This causes an ArrayIndexOutOfBoundsException since the valid indices are 0 to 2.
4.Catch the exception using a catch block:
a)Print "Exception caught in catch block".
5.Execute the finally block:
6.Print "finally block executed" regardless of exception occurrence.
7.Print "Outside try-catch-finally clause" after the try-catch-finally structure.
8.End the program.

## PROGRAM:
 ```
/*
Program to implement a Exception Handling-Finally using Java
Developed by: POOVIZHI P
RegisterNumber:  212222020018
*/
```

## Sourcecode.java:
```
public class ArrayIndexOutOfBoundsExample {
    public static void main(String[] args) {
        int[] numbers = {1, 2, 3};

        try {
            System.out.println(numbers[5]); 
        } catch (ArrayIndexOutOfBoundsException e) {
            System.out.println("Exception caught in catch block");
        } finally {
            System.out.println("finally block executed");
        }

        System.out.println("Outside try-catch-finally clause");
    }
}
```

## OUTPUT:



## RESULT:
Thus the Java program to demonstrate control flow of try-catch-finally clause when NumberFormatException occur in try block and handled in catch block was executed successfully.



