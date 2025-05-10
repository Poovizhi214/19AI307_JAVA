# Ex.No:10(E)  JAVA LINKEDHASH SET

## AIM:
TO write a Java program to trim the capacity of an array list the current list size.
## ALGORITHM :
```
1)Start the program
2)Read an integer n — the number of strings to be added to the ArrayList
3)Create an empty ArrayList<String> named al
4)Display the message "Original array list: " followed by the contents of the list al
5)Call al.trimToSize() to reduce the internal capacity of the list to its current size
6)End the program
```
## PROGRAM:
 ```
/*
Program to implement a LINKEDHASH SET
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
        int n=sc.nextInt();
        ArrayList<String> al=new ArrayList<>();
        for(int i=0;i<n;i++){
            al.add(sc.next());
        }
        System.out.println("Original array list: "+al);
        al.trimToSize();
       System.out.println("Let trim to size the above array:");
       System.out.println(al);
    }
}
```




## OUTPUT:
![image](https://github.com/user-attachments/assets/da76e614-e49d-4ec7-b40f-97bbdd25f4ea)



## RESULT:

Thus the java program was successfully uses LinkedHashSet to store and display elements while maintaining insertion order and ensuring uniqueness. It also shows the correct count of unique elements. 
