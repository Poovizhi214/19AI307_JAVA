# Ex.No:9(B) BYTE ARRAY I/O
## AIM:
To create a java program to write data using ByteArrayOutputStream.


## ALGORITHM :
1.	The user enters a string (data), followed by two integers (start and length) specifying the starting position and number of characters to write.
2.	The string data is converted to a byte array (array).
3.	Using ByteArrayOutputStream, it writes length bytes from array, starting at start.
4.	The written data is retrieved as a string (streamData) and displayed, showing the original input and the specific segment written to the stream.
5.	Any exceptions are caught and handled, displaying stack trace information if an error occurs.




## PROGRAM:
 ```
/*
Program to implement a BYTE ARRAY I/O using Java
Developed by: POOVIZHI P
RegisterNumber: 212222020018
*/
```

## Sourcecode.java:
```
import java.io.*;
import java.util.*;
public class Main {
  public static void main(String[] args) 
  {
      Scanner sc=new Scanner(System.in);
      String s=sc.nextLine();
      try
      {
          FileOutputStream fout=new FileOutputStream(s);
          ByteArrayOutputStream bout=new ByteArrayOutputStream();
          byte[] b=s.getBytes();
          bout.write(b,3,6);
          bout.close();
          System.out.println("Original data: "+s);
          System.out.println("Output stream: "+bout);

    }

    catch(Exception e) {
      e.getStackTrace();
    }
  }
}
```
## OUTPUT:
https://github.com/Poovizhi214/19AI307_JAVA/blob/d21700ef07f51ba7051a42ed09ffb79e913f9b0d/Module-09/DAY-2/BYTE%20ARRAY.png


## RESULT:
Thus, java program to write data using ByteArrayOutputStream was executed and verified successfully.





