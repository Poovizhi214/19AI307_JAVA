# Ex.No:3(D) STRING TOKENIZER IN JAVA

## AIM:
To create a java program using StringTokenizer class that tokenizes a string "welcome to java# programming" on the basis of # symbol.

## ALGORITHM :
1.	Start the Program
2.	Import `Scanner` and `StringTokenizer` and define class `tok`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Initialize the string `str` as "Welcome to java# Programming"
4.	Create a `StringTokenizer` object `token` to tokenize `str`
5.	Use a `while` loop to iterate through tokens:
-	a) Print each token using `token.nextToken()`
6.	End

## PROGRAM:
 ```
/*
Program to implement a String Tokenizer using Java
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
        String str="welcome to java# programming";
        StringTokenizer st=new StringTokenizer(str,"#");
        while(st.hasMoreTokens()){
            System.out.println(st.nextToken());
        }
    }
}
~~~

## OUTPUT:
![image](https://github.com/user-attachments/assets/e00f5c8b-855e-4767-b005-7f075d0dac38)

## RESULT:
Thus the java program using StringTokenizer class that tokenizes a string "Welcome to java#programming" on the basis of #  was executed successfully.
