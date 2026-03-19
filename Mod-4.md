
# Exp No - 4

## TITLE : Variable Scopes and Constructor

### AIM : To demonstrate accessing a static variable using both class name and object.

### ALGORITHM :

STEP 1 : Start

STEP 2 : Define a class with a static variable number

STEP 4 : Read a value and assign it to number using class name

STEP 5 : Display value using class name

STEP 6 : Create an object of the class

STEP 7 : Display value using object

STEP 8 : End

### PROGRAM :
```
import java.util.Scanner;

class MyClass {
    static int number;
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        MyClass.number = sc.nextInt();

        System.out.println("Accessing using class name: " + MyClass.number);

        MyClass obj = new MyClass();
        System.out.println("Accessing using object: " + obj.number);
    }
}

```

### OUTPUT :

<img width="754" height="314" alt="image" src="https://github.com/user-attachments/assets/526efbdf-1783-4a4b-b1a6-f055650fec8f" />

### RESULT :

Thus to demonstrate accessing a static variable using both class name and object was successfully created.
