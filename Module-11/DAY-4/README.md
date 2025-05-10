# Ex.No:11(D) RELATED TO MAP CONCEPTS

## AIM:
To Create a java program to retrieve the key and value from map for all input value.

## ALGORITHM :

1.Start
2.Create a HashMap<Integer, String> named map.
3.Read the number of entries (size).
4.Loop through size times:
5.Read key (a) and value (b), and add to map.
6.Use Iterator to iterate through the map keys
7.Print each key-value pair:
   a)Retrieve key with next(), and value with map.get(key).
8.End



## PROGRAM:
 ```
/*
Program to implement a RELATED TO MAP CONCEPTS using Java
Developed by: POOVIZHI P
RegisterNumber: 212222020018
*/
```

## Sourcecode.java:
```
import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  Map<Integer,String> map=new HashMap<Integer,String>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
Iterator<Integer> keySetIterator = map.keySet().iterator(); while(keySetIterator.hasNext()){ Integer key = keySetIterator.next(); System.out.println("key: " + key + " value: " + map.get(key)); }

   }  
}  
```




## OUTPUT:

![image](https://github.com/user-attachments/assets/3179718d-b787-437d-baf7-b1127d7e547b)


## RESULT:
Thus the java program to retrieve the key and values using map interface was  executed and verified successfully.


