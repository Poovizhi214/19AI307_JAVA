# Ex.No:12(A)         JAVA TREE MAP
## AIM:
 To Write a Java program to get all keys from the given a Tree Map.

## ALGORITHM :

1. Start the program
2. Create a TreeMap named tree_map1 to store String key-value pairs.
3. Initialize Scanner object to read input from user.
4. Read integer size from user (number of key-value pairs).
5. FOR i = 0 to size-1:
   a. Read key n1 from user.
   b. Read value s1 from user.
   c. Insert (n1, s1) into tree_map1.
6. Get the set of keys from tree_map1 using keySet().
7. FOR each key in the set of keys:
   a. Print the key.
8. END


## PROGRAM:
 ```
/*
Program to implement a JAVA TREE MAP using Java
Developed by: POOVIZHI P
RegisterNumber: 212222020018
*/
```

## Sourcecode.java:
```
import java.util.*;  
public class Exa {  
   public static void main(String args[]){  

   TreeMap<String,String> tree_map1=new TreeMap<String,String>();      
  Scanner sc=new Scanner(System.in);
   int size=sc.nextInt();
   for(int i=0;i<size;i++)
   {
      String n1 = sc.next();
      String s1= sc.next();
       
   	  tree_map1.put(n1,s1);  
   }
    
 Set<String> keys = tree_map1.keySet();
        for(String key: keys){
            System.out.println(key);
        }
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/bdbcf626-8bac-4edf-87f5-b5bfa3549ae4)



## RESULT:
Thus the Java program to get all apecific keys in a Tree Map was executed successfully.
