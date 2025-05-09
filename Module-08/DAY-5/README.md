# Ex.No:8(E)  INPUT STREAM READER.

## AIM:
To write a byte representing the character "A" (ASCII value 65) to a file named testout.txt using FileOutputStream in Java and demonstrate an IOException (Stream Closed) by attempting to write after the stream is closed.

## ALGORITHM :
1.Import the java.io.* package.
2.Create a FileOutputStream object pointing to "testout.txt".
3.Write the ASCII value 65 to the file using the write() method.
4.Close the file output stream.
5.Try writing to the stream again to deliberately trigger a java.io.IOException.
6.Catch and display the exception.

## PROGRAM:
 ```
/*
Program to implement a INPUT STREAM READER
Developed by: POOVIZHI P
RegisterNumber: 212222020018
*/
```

## Sourcecode.java:
```
 try{
     FileOutputStream fout=new FileOutputStream("testout.txt");
     System.out.println("Successfully Completed");
     fout.write(65);
     fout.close();
     }
catch(Exception e){System.out.println(e);}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/0f2c5a75-cdc9-423e-a56c-0c058e6d0295)



## RESULT:
Thus, the java program is executed and verified.
