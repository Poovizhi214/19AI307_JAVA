# Ex.No:8(B) IO-FILE READER/WRITER
## AIM:
To implement a Java program that writes a string "Hi Everybody...Welcome all" to a file named testout.txt using the Writer class, and demonstrate handling of file I/O exceptions.


## ALGORITHM :
1.Import required I/O classes (java.io.*).
2.Create a FileWriter or Writer object pointing to "testout.txt".
3.Write the string "Hi Everybody...Welcome all" to the file.
4.Close the writer stream.
5.Optionally try writing again after closing the stream to simulate the Stream Closed exception.
6.Handle exceptions using a try-catch block.
## PROGRAM:
 ```
/*
Program to implement a IO File Reader/Writer using Java
Developed by: POOVIZHI P
RegisterNumber: 212222020018
*/
```

## Sourcecode.java:
```
Writer w = new FileWriter("testout.txt");  
String content = "Hi Everybody...Welcome all";  
w.write(content);  
w.close();  
System.out.println("Wrote File Successfully");  
```
## OUTPUT:
https://github.com/Poovizhi214/19AI307_JAVA/blob/3936ed22b779bbacd70f38d3da5011e68e704095/Module-08/DAY-2/filewriter.png


## RESULT:
Thus, the java program to append a string in a file “testout.txt” using Writer.was executed and verified successfully



