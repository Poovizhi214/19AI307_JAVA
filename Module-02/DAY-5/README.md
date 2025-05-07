# Ex.No:2(E)  LARGEST ELEMENT IN AN ARRAY

## AIM:
To write a Java program that reads an array size and elements from the user and then finds and prints the largest element in the array.
## ALGORITHM :
1.	Start the program.
2.	Read the size of the array from the user.
3.	Declare an array of the given size.
4.	Read the array elements from the user.
5.	Initialize a variable max with the first element of the array.
6.	Traverse the array using a loop.
7.	Compare each element with min. If an element is larger, update max.
8.	After the loop ends, print the largest number.
9.	End the program.
	

## PROGRAM:
 ```
/*
Program to implement a Largest Element in an Array
Developed by: POOVIZHI P
RegisterNumber:  212222020018
*/
```

## Sourcecode.java:
~~~
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int size=sc.nextInt();
        int[] arr=new int[size];
        for(int i=0;i<size;i++){
            arr[i]=sc.nextInt();
        }
        int max=Integer.MIN_VALUE;
        for(int i=0;i<size;i++){
            if(arr[i]>max){
                max=arr[i];
            }
        }
        System.out.print("The largest element in the array is: "+max);
    }
}
~~~
## OUTPUT:
![image](https://github.com/user-attachments/assets/31a906dc-1a02-4602-a94d-6dc22d1f11fc)

## RESULT:
Thus the java program successfully reads the array size and elements from the user and correctly finds and prints the largest number in the array.




