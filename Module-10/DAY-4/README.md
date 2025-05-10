# Ex.No:10(D) JAVA HASHSET & LINKEDHASHSET

## AIM:
To Write a java program to read n elements and display the n elements, after remove one elements from the hashset("Ravi") and then display the elements.

## ALGORITHM :
1)Initialize a Scanner to read input from the user
2)Read an integer n — the number of strings to be added to the HashSet
3)Create an empty HashSet<String> named al
4)Repeat the following steps n times:
  a) Read a string using sc.next()
  b) Add the string to the HashSet al (duplicates are ignored automatically)
5)Print the contents of the HashSet with the label: "HashSet: "
6)Remove the element "Ravi" from the HashSet using al.remove("Ravi")
7)end

## PROGRAM:
 ```
/*
Program to implement a JAVA HASHSET & LINKEDHASHSET using Java
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
        HashSet<String> al=new HashSet<>();
        for(int i=0;i<n;i++){
            al.add(sc.next());
        }
        System.out.println("HashSet: "+al);
        al.remove("Ravi");
        System.out.println("HashSet after removing elements: "+al);
    }
}
```




## OUTPUT:
![image](https://github.com/user-attachments/assets/813408bb-3b7d-4a15-bfd9-182d42d759d2)



## RESULT:
Thus the java program of hashmap concepts was executed and verified successfully.



