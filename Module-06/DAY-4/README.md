# Ex.No:6(D) PACKAGES
## AIM:
  To create a Java Program for accessing package from another package using packagename.
 
## ALGORITHM :
1.	Start the Program
2.	Create a directory named pack and save A.java inside it.
2.	Compile A.java from the parent directory using javac pack/A.java.
3.	Create another directory named mypack and save B.java inside it.
4.	Compile B.java from the parent directory using javac mypack/B.java.
5.	Run B from the parent directory with java mypack.B


## PROGRAM:
 ```
/*
Program to implement a Packages using Java
Developed by: POOVIZHI P
RegisterNumber:  212222020018
*/
```

## Sourcecode.java:
```
pack/A.java

package pack;
public class A {
    public void display() {
        System.out.println("Hello from class A in package pack");
    }
}
mypack/B.java
package mypack;
import pack.A;
public class B {
    public static void main(String[] args) {
        A obj = new A();
        obj.display();
    }
}
```
  ## OUTPUT:
![image](https://github.com/user-attachments/assets/81897d04-c7a2-4ea0-a8ec-89e6e7580dcd)

## RESULT:
Thus, the program has accessed the package from another package has been done successfully.

