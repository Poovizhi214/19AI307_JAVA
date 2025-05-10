# Ex.No:10(B) JAVA LINKED LIST
## AIM :
To Create a java program to perform linkedlist, read size of the list , read the elements for the linkedlist and display the elements from the linkedlist.


## ALGORITHM :
1.	Start the Program
2.	Import `java.util.*` for input handling and list functionality
3.	Define class `Hello` with the `main` method:
-	a) Create `Scanner` object `sc` for input
-	b) Read an integer `n` to specify the number of strings
-	c) Create a `LinkedList` named `str` to store strings
4.	Use a `for` loop to:
-	a) Read `n` strings from input and add each to `str`
5.	Print the entire `str` list
6.	End



## PROGRAM:
 ```
/*
Program to implement a JAVA LINKED LIST using Java
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
        int size=sc.nextInt();
        sc.nextLine();
        LinkedList<String> list=new LinkedList<>();
        for(int i=0;i<size;i++){
            String s=sc.nextLine();
            list.add(s);
        }
        System.out.println(list);
    }
}
```




## OUTPUT:

https://github.com/Poovizhi214/19AI307_JAVA/blob/c6354f3ee2d4245f5833c3980bd07b517ec0f68f/Module-10/DAY-2/list.png

## RESULT:
Thus the Java program of the creation of a linkedlist was executed successfully.





