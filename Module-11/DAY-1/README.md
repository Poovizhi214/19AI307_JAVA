# Ex.No:11(A)         JAVA TREESET
## AIM:
 To write a Java program to create a reverse order view of the elements contained in a given tree set.
## ALGORITHM :
1.	Start
2.	Import `java.util.*`
3.	Define class `Main` with `main` method:
-	a) Initialize `Scanner` and read integer `n`
-	b) Create a `TreeSet` named `set` to store integers in sorted order
4.	Use a loop to read `n` integers and add each to `set`
5.	Use an enhanced `for` loop to print each element in `set`
6.	End


## PROGRAM:
 ```
/*
Program to implement a JAVA TREESET using Java
Developed by: POOVIZHI P
RegisterNumber: 212222020018
*/
```

## Sourcecode.java:
```
import java.util.*;
  public class Main {
  public static void main(String[] args) {
    Scanner sc=new Scanner(System.in);
    int size=sc.nextInt();
     TreeSet<String> t_set = new TreeSet<String>();
  for(int i=0;i<size;i++)
  {
  t_set.add(sc.next());
  }
     System.out.println("Original tree set:" + t_set);  
     Iterator it = t_set.descendingIterator();
     
     System.out.println("Elements in Reverse Order: ");
     while (it.hasNext()) {
        System.out.println(it.next() + " ");
     }
  }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/8fcfb346-1f12-4481-88e3-dbb2f712be76)


## RESULT:
Thus the java program to create a reverse order view of the elements contained in a given tree set was executed successfully.

