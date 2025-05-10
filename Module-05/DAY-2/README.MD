# Ex.No:5(B) TIGHTLY ENCAPSULATED CLASS

## AIM: 
To create a Java program that checks whether a given number is an Armstrong number, using the concept of tightly encapsulated class.
## ALGORITHM :
1.Start the program.
2.Define SetAndGet class:
a) Declare a private integer variable ar to store the number.
b) Implement setarm(int ar) method to set the value of ar.
c) Implement getarm() method to calculate and check whether the number is an Armstrong number.
3.In main method:
a) Use Scanner to read an integer input.
b) Create an object of SetAndGet class, set the number using setarm(), and check if it's an Armstrong number using getarm().
4.End the program.

## PROGRAM:
 ```
/*
Program to implement a tightly encapsulated class using Java
Developed by: POOVIZHI P
RegisterNumber:  212222020018
*/
```
## Sourcecode.java:
~~~
import java.util.*;
public class SetAndGet {
private int ar;
public void getarm() {
    int arm=0,a,temp;
    //int n=Integer.parseInt(ar);
    int n=ar;
    temp=n;
	while(n>0)
	{
		a=n%10;
		arm=arm+(a*a*a);
		n=n/10;
	}
	if(arm==temp)
	System.out.println(temp+" is a armstrong number ");
	else
	System.out.println(temp+" is not a armstrong number ");
	
}
public void setarm(int ar) {
      this.ar=ar;
}
public static void main(String args[]){
 Scanner sc=new Scanner(System.in);
 SetAndGet obj = new SetAndGet();
 int str=sc.nextInt();
 obj.setarm(str);
 obj.getarm();
}
}
~~~
## OUTPUT:
https://github.com/Poovizhi214/19AI307_JAVA/blob/fbbc45f0be8d55f276fff6198dcab1c504fbc2ac/Module-05/DAY-2/armstrong.png

## RESULT:
Thus a java program to display the value of volume of cylinder get the radius and height value as input and use tightly encapsulated class was executed successfully.



