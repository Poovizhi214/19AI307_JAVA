# Ex.No:4(D) FINAL & STATIC IN JAVA

## AIM:
   To create a Java program to perform final & static keyword for below situation Employee object contains member 'name'. It contains object named name, which contains its own informations such as address.
 
## ALGORITHM :
1. Define class Address with fields and method dispAddr() to display address.
2. Define class Employee with a name field and an Address object.
3. In dispName(), print the name and call dispAddr() with address details.
4. In main(), create Employee object and call dispName("Leo").
5. Program prints employee name and address.
6. End

## PROGRAM:
 ```
/*
Program to implement a final & Static using Java
Developed by: POOVIZHI P
RegisterNumber: 212222020018 
*/
```

## Sourcecode.java:
~~~
class Address
{
    int doorno;
    String street;
    String city;
    void dispAddr(int d_no,String st,String City)
    {
        this.doorno=d_no;
        this.street=st;
        this.city=City;
        System.out.println(doorno+","+street+","+city);
    }
}
class Employee
{
    String name;
    Address addr=new Address();
    void dispName(String s)
    {
        this.name=s;
        System.out.println(name);
        addr.dispAddr(10,"100 Feet Road","Chennai");
    }
}

public class Main
{
    public static void main(String[] args)
    {
        Employee obj=new Employee();
        obj.dispName("Leo");
        
    }
}
~~~

## OUTPUT:
![image](https://github.com/user-attachments/assets/64722dfd-36d5-4039-b725-03e98237b12a)


## RESULT:
Thus, the java program to perform final & static keyword was executed successfully.
