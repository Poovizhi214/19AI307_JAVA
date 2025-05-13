# Ex.No:12(D) JAVA QUEUE
## AIM:
To Write a java program to display the added elements from the Priority Queue and to insert a particular element into the Priority Queue and then display the elements.(Use offer() method).

## ALGORITHM :
1. Start the program
2. Create a Scanner object to read input.
3. Create a PriorityQueue `t` to store Integer elements.
4. Read integer `size` from user (the number of elements to insert).
5. FOR i = 0 to size-1:
   a. Read an integer and add it to the PriorityQueue `t` using the offer() method.
6. Print the contents of the PriorityQueue `t`.
7. END




## PROGRAM:
 ```
/*
Program to implement a JAVA QUEUE using Java
Developed by: POOVIZHI P
RegisterNumber: 212222020018
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    public static void main(String[] args){
        
        PriorityQueue<Integer>t=new PriorityQueue<Integer>();
        Scanner sc=new Scanner(System.in);
        int size = sc.nextInt();
        for(int i=0;i<size;i++){
            t.offer(sc.nextInt());
        }
            System.out.println("Display the element of Queue:");
            System.out.println(t);
        }
    }
```




## OUTPUT:

![image](https://github.com/user-attachments/assets/0a3e562e-eedd-44e4-a4b2-56b2e47d9cb4)


## RESULT:
Thus the java program to display the added elements from the Priority Queue and to insert a particular element into the Priority Queue and then display the elements.(Use offer() method).


