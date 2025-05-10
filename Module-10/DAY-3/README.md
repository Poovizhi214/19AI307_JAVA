# Ex.No:10(C)             JAVA LIST INTERFACE
 ## AIM :

To Create a List interface implemented by two Linkedlist class , adding n elements to object of two List interface and print all the elements inside the List interface object.Check the two lists are equal or not.

## ALGORITHM :
1)Start
2)Initialize a scanner to read input from the user
3)Create two empty lists: list1 and list2 to store strings
For First List (list1)
4)Read an integer n1 (number of strings to be entered in list1)
5)Loop n1 times:
  → In each iteration, read a line (string) and add it to list1
For Second List (list2)
6)Read an integer n2 (number of strings to be entered in list2)
7)Loop n2 times:
  → In each iteration, read a line (string) and add it to list2
Output and Comparison
8)Print list1
9)Print list2
10)Compare the two lists using .equals()
  → If they are equal, print "Equal"
  → Else, print "Not equal"
11)End



## PROGRAM:
 ```
/*
Program to implement a JAVA LIST INTERFACE using Java
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
        List<String> list1=new ArrayList<String>();
        List<String> list2=new ArrayList<String>();
        int n1=sc.nextInt();
        sc.nextLine();
        for(int i=0;i<n1;i++){
            list1.add(sc.nextLine());
        }
        int n2=sc.nextInt();
        sc.nextLine();
        for(int i=0;i<n2;i++){
            list2.add(sc.nextLine());
        }
        System.out.println(list1);
        System.out.println(list2);
        if(list1.equals(list2))
          System.out.println("Equal");
        else
          System.out.println("Not equal");
    }
}
```




## OUTPUT:
![image](https://github.com/user-attachments/assets/b8550044-f3a9-46a2-8570-2f34fed58c57)



## RESULT:
Thus the java program implemented a List interface was executed and verified successfully.










