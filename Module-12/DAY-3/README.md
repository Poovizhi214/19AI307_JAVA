# Ex.No:12(C)             JAVA STACK & VECTOR
 ## AIM :

To write a java program to read and print the elements  and to fetching the specific element from the index of 3 using vector in java collection.(Use elementAt() method)
## ALGORITHM :
1. Strat the program
2. Create a Vector `t` to store String elements.
3. Read integer `size` from user (number of pairs).
4. FOR i = 0 to size-1:
   a. Read a String and add it to the vector `t`.
   b. Read another String and add it to the vector `t`.
5. Print the entire Vector `t`.
6. Print the element at index 3 from the Vector `t`.
7. END




## PROGRAM:
 ```
/*
Program to implement a JAVA STACK & VECTOR  using Java
Developed by: POOVIZHI P
RegisterNumber: 212222020018
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        Vector<String>t=new Vector<String>();
        int size=sc.nextInt();
        for(int i=0;i<size;i++){
            t.add(sc.next());
            t.add(sc.next());
        }
        System.out.println("The vector is: " + t);
        System.out.println("The element is: " + t.elementAt(3));
    }
}
```




## OUTPUT:

![image](https://github.com/user-attachments/assets/ba350bb1-7718-4418-a0d7-e20178308425)


## RESULT:

Thus the java program to create vector and read the elements for two vector in java collection.(Use equals method ) was executed successfully.








