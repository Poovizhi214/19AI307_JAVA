# Ex.No:4(C)    CONSTRUCTOR CHAINING(SUPER KEYWORD)

## AIM:
To Create a Java program to implement super keyword in constructor.

## ALGORITHM :
~~~
1.Start the Program.
2.Define class Animal:
a)Define a constructor in the Animal class that prints "I am an animal".
3.Define class Dog that extends Animal:
a)Define a constructor in the Dog class that:
b)Calls the super() constructor to invoke the Animal class constructor.
c)Prints "I am a dog".
4.Define the Main class with the main method:
a)In the main method, create a Dog object dog1 which will invoke the constructors of both Animal and Dog.
5.End the Program.
~~~
## PROGRAM:
 ```
/*
Program to implement a Constructor Chaining using Java
Developed by: POOVIZHI P
RegisterNumber:  212222020018
*/
```

## Sourcecode.java:
~~~
class Animal {
   Animal() {
      System.out.println("I am an animal");
   }
}

class Dog extends Animal {
   Dog() {
      super();  
      System.out.println("I am a dog");
   }
}
public class Main {
   public static void main(String[] args) {
      Dog dog1 = new Dog();
   }
}
~~~
## OUTPUT:
![image](https://github.com/user-attachments/assets/44180844-b2f0-4ddd-b7bd-02214e373ccb)

## RESULT:
Thus the java program for constructor chaining using the super keyword was executed successfully.




