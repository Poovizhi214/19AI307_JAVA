# Ex.No:11(C)             JAVA LINKED HASHMAP
 ## AIM :

To Create a java program to display the contains key of 104 and to retrieve the key and value using linked hash map.

## ALGORITHM :

1.	Start the Program
2.	Import `java.util.*`
3.	Define class `A` with `main` method:
-	a) Initialize `Scanner` and read integer `n`
-	b) Create a `LinkedHashMap` named `hash` to store integer keys and string values
4.	Use a loop to:
-	a) Read an integer and string from the user
-	b) Add the integer as the key and the string as the value in `hash`
5.	Use an enhanced `for` loop to iterate through `hash` and print each key-value pair
6.	Check if the `hash` contains the key `104` and print the result
7.	End


## PROGRAM:
 ```
/*
Program to implement a JAVA LINKED HASH MAP using Java
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
        LinkedHashMap<Integer,String> map=new LinkedHashMap<>();
        int size=sc.nextInt();
        for(int i=0;i<size;i++){
            Integer a=sc.nextInt();
            String b=sc.next();
            map.put(a,b);
        }
        for(Map.Entry m:map.entrySet())
        System.out.println("key: "+m.getKey()+" value: "+m.getValue());
        System.out.println("Does HashMap contains 104 as key: "+map.containsKey(104));
    }
}
```




## OUTPUT:
![image](https://github.com/user-attachments/assets/907772c5-d450-45ad-98fd-c548bcbdbebd)



## RESULT:
Thus the  java program to display the contains key of 104 and to retrieve the key and value using linked hash map was executed successfully.








