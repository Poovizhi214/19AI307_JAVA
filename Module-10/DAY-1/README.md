# Ex.No:10(A)         JAVA COLLECTION FRAMEWORK –ARRAY LIST
## AIM:
 To Create a Java Program to store n elements(add elements of type String) and then display the n elements using array List.

## ALGORITHM:
1.import java.util.* package.
2.Create an ArrayList<String> to store car names.
3.Add 4 car names using add() method.
4.Insert another car name at index 2 (3rd position) using add(index, element) method.
5.Sort the list using Collections.sort().
6.Print the sorted list

## PROGRAM:
 ```
/*
Program to implement a ARRAY LIST using Java
Developed by: POOVIZHI P 
RegisterNumber: 212222020018 
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    public static void main(String[] args){
        ArrayList<String> cars=new ArrayList<String>();
        Scanner sc=new Scanner(System.in);
        for(int i=0;i<4;i++)
        {
            cars.add(sc.next());
        }
        cars.add(3,sc.next());
        Collections.sort(cars);
        for(String i : cars){
            System.out.println(i);
        }
    }
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/2323b3f9-1723-4e23-ba40-bfc2276702c6)



## RESULT:
TThus the Java Program to store n elements and then display the n elements using array List was executed successfully.

