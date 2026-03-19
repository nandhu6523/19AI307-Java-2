
# Exp No - 1

## TITLE : Introduction to OOPs, Class and Objects, Class Attributes

### AIM : To create a class and objects, assign values, and display the details of cars.

### ALGORITHM :

STEP 1 : Start

STEP 2 : Define a class Car with variables: brand, model, year

STEP 3 : Create two objects (car1, car2)

STEP 4 : Assign values to each object

STEP 5 : Print the details of both cars

STEP 6 : End

### PROGRAM :

```
class Car
{
    String brand;
    String model;
    int year;
}
public class prog {
    public static void main(String[] args) {
        Car car1 = new Car();
        car1.brand = "Toyota";
        car1.model = "Innova";
        car1.year = 2022;

        Car car2 = new Car();
        car2.brand = "Hyundai";
        car2.model = "i20";
        car2.year = 2021;

        System.out.println("Car 1: " + car1.brand + " " + car1.model + " " + car1.year);
        System.out.println("Car 2: " + car2.brand + " " + car2.model + " " + car2.year);
    }
}
```

### OUTPUT :

<img width="605" height="175" alt="image" src="https://github.com/user-attachments/assets/fde4ba78-4e38-44d4-88b2-5c8c4b1b0fe6" />

### RESULT :

Thus was to create a class and objects, assign values, and display the details of cars. successfully created.
