
# Exp No - 2

## TITLE : Methods

### AIM : To demonstrate the difference between static and non-static methods in Java.

### ALGORITHM :

STEP 1 : Start

STEP 2 : Define a class with one static method and one non-static method

STEP 3 : Call the static method using class name

STEP 4 : Create an object of the class

STEP 5 : Call the non-static method using the object

STEP 6 : End

### PROGRAM :
```
class MyClass {
    static void staticMethod() {
        System.out.println("I am static");
    }
    void nonStaticMethod() {
        System.out.println("I am non-static");
    }
}

public class prog {
    public static void main(String[] args) {
        MyClass.staticMethod();
        MyClass obj = new MyClass();
        obj.nonStaticMethod();
    }
}

```

### OUTPUT :

<img width="424" height="182" alt="image" src="https://github.com/user-attachments/assets/2e0253b9-f267-467a-b5d3-f94c47dbd5fd" />

### RESULT :

Thus to demonstrate the difference between static and non-static methods in Java was successfully created.
