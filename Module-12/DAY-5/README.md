# Ex.No:12(E)  JAVA DEQUEUE

## AIM:
To demonstrate how to remove and display the first element from a Deque using the pollFirst() method in Java Collections with String values.
## ALGORITHM :

1.	Import java.util.*.
2.	Create a Deque using LinkedList.
3.	Add several string elements to the deque.
4.	Use pollFirst() to remove and return the first element.
5.	Print the removed element.
6.	Display the remaining elements in the deque.

## PROGRAM:
 ```
/*
Program to implement a JAVA DEQUEUE
Developed by: POOVIZHI P
RegisterNumber: 212222020018
*/
```

## Sourcecode.java:
```
import java.util.*;

public class deQueueDemo {
	

	public static void main(String args[])
	{
	
		Deque<String> dq = new ArrayDeque<String>();
        
	    Scanner sc=new Scanner(System.in);
	    int size=sc.nextInt();
	    for(int i=0;i<size;i++){
	        dq.offer(sc.next());
	    }
	    System.out.println("Display the element of Dequeue:");
		System.out.println(dq);
		System.out.println(dq.pollFirst());
     	
	}
}
```




## OUTPUT:
![image](https://github.com/user-attachments/assets/b87375c2-1132-4581-a397-3a5af4ecf2cf)



## RESULT:

Thus the java program successfully demonstrates how to use pollFirst() to remove and display the first element from a Deque of strings.


