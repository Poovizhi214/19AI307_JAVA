# Ex.No:5(D) IS-A RELATIONSHIP AND HAS-A RELATIONSHIP
## AIM:
   To Create a java program to find factorial of number using class and object concepts and apply the has-a relationship.
 
## ALGORITHM :
1.	Start the Program
2.	Define class `A`:
-	a) Declare integer `n` and initialize `fact` to 1
-	b) Define method `factorial(int n)`:
-	i) Set `this.n = n`
-	ii) Use a loop from 1 to `n` to calculate `fact = fact * i`
-	iii) Print "Factorial is:" followed by `fact`
3.	In `main` class `main` method:
-	a) Use `Scanner` to read integer `n`
-	b) Create an `A` object and call `factorial(n)`
4.	End

## PROGRAM:
 ```
/*
Program to implement a IS-A RELATIONSHIP AND HAS-A RELATIONSHIP using Java
Developed by: POOVIZHI P
RegisterNumber:  212222020018
*/
```
## Sourcecode.java:
```
import java.util.Scanner;
class A {
    private int n;
    private int fact = 1;
    public void factorial(int n) {
        this.n = n; 
        for (int i = 1; i <= n; i++) {
            fact = fact * i; 
        }
        System.out.println("Factorial is: " + fact);
    }
}
public class Main {
    public static void main(String args[]) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        A obj = new A();
        obj.factorial(n);
    }
}
```
## OUTPUT:
```
INPUT:5
OUTPUT:Factorial is 120
```
## RESULT:
Thus the java program to find factorial of number using class and object concepts and apply the has-a relationship was executed successfully.
