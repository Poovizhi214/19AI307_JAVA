# Ex.No:5(C)    GETTER AND SETTER METHOD

## AIM:
To Create a java program to print the sum of two number using getter and setter method.

## ALGORITHM :
1.  Start the Program
2.	Define class `Employee`:
-	a) Private variables `n1` and `n2`
-	b) Method `setsum(int n1, int n2)` to set values of `n1` and `n2`
-	c) Method `getsum()` to calculate and print `sum = n1 + n2`
3.	In `main` class `main` method:
-	a) Use `Scanner` to read integers `n1` and `n2`
-	b) Create ` Employee ` object, set values, and call `getsum()`
4.	End


## PROGRAM:
 ```
/*
Program to implement a Getter and Setter using Java
Developed by: POOVIZHI P
RegisterNumber:  212222020018
*/
```

## Sourcecode.java:
~~~
import java.util.Scanner;
class Employee {
    private int n1, n2;
    public void setsum(int n1, int n2) {
        this.n1 = n1;  
        this.n2 = n2;  
    }
    public void getsum() {
        int sum = n1 + n2;  
        System.out.println("The sum is: " + sum);  
    }
}
public class Main {
    public static void main(String args[]) {
        Scanner sc = new Scanner(System.in);
        Employee emp = new Employee();
        int n1 = sc.nextInt();
        int n2 = sc.nextInt();
        emp.setsum(n1, n2);
        emp.getsum();
    }
}
~~~

## OUTPUT:
```
INPUT:5 5
OUTPUT:The sum is 10
```
## RESULT:
Thus the java program to print the sum of two number using getter and setter method was executed successfully.






