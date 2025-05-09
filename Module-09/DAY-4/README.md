# Ex.No:9(D) TRANSIENT ---SERILIZATION

## AIM:
 To implement a Java program to perform Transient in Employee details in Serializable interface to make its object serialized.

## ALGORITHM :
1.	Get employee name and designation from the user.
2.	Save the Employeeinfo object to emp.txt.
3.	Read the object back from emp.txt.
4.	Print employee name and designation (designation is null due to transient).
5.	Delete File: Delete emp.txt and handle any exceptions while trying to read it.

## PROGRAM:
 ```
/*
Program to implement a Transient using Java
Developed by: POOVIZHI P 
RegisterNumber: 212222020018
*/
```

## Sourcecode.java:

```
class Employeeinfo implements Serializable{
    String name;
    transient String desi;
    Employeeinfo(String a,String b){
        this.name=a;
        this.desi=b;
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/499de189-5775-4e66-9295-eeaac6d35110)


## RESULT:
Thus, implementation of a Java program to perform Transient in Employee details in Serializable interface to make its object serialized was executed and verified successfully.

