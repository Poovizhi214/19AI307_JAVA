# Ex.No:9(E) STRING WRITER

## AIM:
To write a Java program that reads a string from the user and prints it using the StringWriter class.
## ALGORITHM :
```
a.	Start the program.
b.	Import java.io.* and java.util.Scanner.
c.	Create a Scanner object to read input from the user.
d.	Read a string from the user.
e.	Create a StringWriter object.
f.	Write the string to the StringWriter object.
g.	Convert the StringWriter content to a string using .toString().
h.	Print the result on the output screen.
i.	Close the writer.
j.	End the program.
```

## PROGRAM:
 ```
/*
Program to implement a STRING WRITER
Developed by: POOVIZHI P
RegisterNumber: 212222020018
*/
```

## Sourcecode.java:
```
import java.io.StringWriter;

public class Main {
  public static void main(String[] args) {

    String data = "This is the text in the string.";

    try {
      StringWriter writer=new StringWriter();
      writer.write(data);
      System.out.println("Data in the StringWriter: "+writer);
    }

    catch(Exception e) {
      e.getStackTrace();
    }
  }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/920b9d79-8f27-4466-baef-a205faf88327)


## RESULT:
Thus, implementation of  a Java program was successfully reads a string from the user and uses StringWriter to write and print the string to the output screen.

