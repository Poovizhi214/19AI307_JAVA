# Ex.No:5(E) HAS-A RELATIONSHIP
## AIM:
To implement a  Java Program to check is a string is palindrome or using has - a relationship.
## ALGORITHM :
1.Start the program.
2.Create a class fun containing a static boolean method isPal(String s): 
a. Base Case 1: If the length of the input string s is 0 or 1, return true .
b. Recursive Step: If the first character of s is equal to the last character of s: i. Recursively call isPal with the substring of s that excludes the first and last characters (from index 1 to length-2). 
c. Base Case 2: If the first character of s is not equal to the last character of s, return false.
3.Create a public class ArrayProgram with a main method.
4.Inside the main method: 
a. Create a Scanner object to read input from the user.
b. Create an object of the fun class named obj.
c. Check the boolean value returned by obj.isPal(string): 
i. If the value is true, print the message: "string is a palindrome". 
ii. If the value is false, print the message: "string is not a palindrome".
5.End the program.

## PROGRAM:
 ```
/*
Program to implement a HAS-A RelationShip
Developed by: POOVIZHI P
RegisterNumber:  212222020018
*/
```
## Sourcecode.java:
```import java.util.Scanner;
class fun{
    public static boolean isPal(String s)
    {   
        if(s.length() == 0 || s.length() == 1)
            return true; 
        if(s.charAt(0) == s.charAt(s.length()-1))
        
        return isPal(s.substring(1, s.length()-1));
        return false;
    }
}
public class ArrayProgram {
  public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String string = scanner.nextLine();
        fun obj=new fun();
        if(obj.isPal(string))
            System.out.println(string + " is a palindrome");
        else
            System.out.println(string + " is not a palindrome");
    
  }
}
```
## OUTPUT:
```
INPUT:MADAM
OUTPUT:MADAM is a palindrome
INPUT:TRY
OUTPUT:TRY is not a palindrome
```
## RESULT:
Thus the java program to check the given string is palindrome or not using has - a relationship was executed successfully. 

