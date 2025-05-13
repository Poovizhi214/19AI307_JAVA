# Ex.No:12(B)   COMPARABLE & COMPARATOR INTERFACE
## AIM :
To Write a java program to compare two elements , if element is greater means display 1 otherwise display -1 use only comparable interface in java collection.


## ALGORITHM :
1.	Start the Program.
2.	Import `java.util.*` and `java.util.Map.Entry`
3.	Define `Example6` class with `main` method:
-	a) Initialize `TreeMap<String, String> tree_map1`
-	b) Read integer `size` for entries count.
4.	Use a loop to:
-	a) Read `String` values `n1` and `s1`
-	b) Insert each pair into `tree_map1`
5.	Print `tree_map1` as `"Original TreeMap content: "`
6.	Define `sort_key` class that implements `Comparator<String>`:
-	Override `compare` method to compare `String` values `str1` and `str2` using
`compareTo`
7.	End


## PROGRAM:
 ```
/*
Program to implement a COMPARABLE & COMPARATOR INTERFACE using Java
Developed by: POOVIZHI P
RegisterNumber: 212222020018
*/
```

## Sourcecode.java:
```
import java.util.*;
public class ComparableExample {

    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        
        Integer valA = Integer.valueOf(sc.nextInt());
        Integer valB = Integer.valueOf(sc.nextInt());

        int comparisonA = valA.compareTo(valB);
        int comparisonB = valB.compareTo(valA);

        System.out.println(comparisonA);
        System.out.print(comparisonB);
    }
}
```




## OUTPUT:

https://github.com/Poovizhi214/19AI307_JAVA/blob/48393a82ceabc5723fc672ffb0c6bafe9b9afd90/Module-12/DAY-2/COMPARATOR.png

## RESULT:
Thus the java program to compare two elements , if element is greater means display 1 otherwise display -1 use only comparable interface in java collection was executed successfully




