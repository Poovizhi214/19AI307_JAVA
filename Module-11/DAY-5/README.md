# Ex.No:11(E)  JAVA HASHMAP

## AIM:
   To Create a java program to create and add objects and check whether a particular key/value exist  in hashmap interface.
## ALGORITHM :
1. Start
2. Create a HashMap<Integer, Double> named map.
3. Read the number of entries (size).
4. Loop through size times:
  a)Read integer key (a) and double value (b).
  b)Add the key-value pair (a, b) to map.
5. Print all key-value pairs using a for-each loop.
6. Check if map contains a key 3 and print the result.
7. Check if map contains the value 3.3 and print the result.
8. End

## PROGRAM:
 ```
/*
Program to implement a HASHMAP
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
        HashMap<Integer,Double> map=new HashMap<>();
        int size=sc.nextInt();
        for(int i=0;i<size;i++){
            Integer a=sc.nextInt();
            Double b=sc.nextDouble();
            map.put(a,b);
        }
        for(Map.Entry m:map.entrySet()){
            System.out.println(m.getKey()+" "+m.getValue());
        }
        System.out.println(map.containsKey(3));
        System.out.println(map.containsValue(3.3));
    }
}
```




## OUTPUT:

![image](https://github.com/user-attachments/assets/9304dba9-53fb-4a1c-9a73-458db20c0917)


## RESULT:
Thus the java program was successfully check whether the particular key/value exist in  HashMap and displays the remaining key-value pairs.




