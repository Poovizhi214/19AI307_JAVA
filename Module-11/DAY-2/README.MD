# Ex.No:11(B)   JAVA MAP & HASHMAP AND HASHTABLE
## AIM :
To create a java program to create and add objects  in hashmap interface.

## ALGORITHM :

1.	Start the program
2. Create an empty HashMap<Integer, String> named map to store key-value pairs.
3. Read an integer size (number of key-value pairs to be inserted).
4. Repeat the following steps size times:
  a) Read an integer a (key).
  b) Read a string b (value).
  c) Add the key-value pair (a, b) to the map using map.put(a, b).
5. Iterate over the map using a for-each loop with Map.Entry to display all key-value pairs
6.	End




## PROGRAM:
 ```
/*
Program to implement a JAVA MAP & HASHMAP AND HASHTABLE using Java
Developed by: POOVIZHI P
RegisterNumber: 212222020018
*/
```

## Sourcecode.java:
```
import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  HashMap<Integer,String> map=new HashMap<Integer,String>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 
  for(Map.Entry m:map.entrySet()){  
   System.out.println(m.getKey()+" "+m.getValue());  
  }  
 }  
}  
```




## OUTPUT:

https://github.com/Poovizhi214/19AI307_JAVA/blob/ae981be7b42ecae8a01a93eb355a9af853619376/Module-11/DAY-2/hashmap.png


## RESULT:
Thus the java program to retrieve the key and value from hashtable for all input value was executed successfully.







