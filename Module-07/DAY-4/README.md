# Ex.No:7(D) SYNCHRONIZATION
## AIM:
 To write a Java program that demonstrates the use of synchronized methods by performing a cube operation on a number, simulating a delay of 400 milliseconds for each computation using multiple threads.
## ALGORITHM :
```
1.Create a class Table with a synchronized method cube(int n) to compute and display the cube of a number.
2.Simulate a delay of 400ms after computing each cube.
3.Create multiple thread classes or use anonymous classes to call the cube() method.
4.Each thread will use the same instance of Table to demonstrate synchronization.
5.Observe that only one thread at a time accesses the synchronized method, ensuring thread safety
```
## PROGRAM:
 ```
/*
Program to implement a Packages using Java
Developed by: POOVIZHI P
RegisterNumber:  212222020018
*/
```

## Sourcecode.java:
```
class Table {
    public void cube(int range) {
       
        synchronized (this) {
            for (int i = 1; i <= range; i++) {
                try {
                   
                    Thread.sleep(400); 
                } catch (InterruptedException e) {
                    e.printStackTrace();
                }
                int result = i * i * i;
                System.out.println("cube for range value " + range + " " + i + ":" + result);
            }
        }
    }
}

class MyThread extends Thread {
    private Table table;
    private int range;
    public MyThread(Table table, int range) {
        this.table = table;
        this.range = range;
    }

    @Override
    public void run() {
        table.cube(range);  
    }
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/449d3a85-78c5-445c-8b63-b4dbb4b6e0d3)



## RESULT:
Thus the java program for synchronization was executed successfully.

