
# Exp No - 3

## TITLE : Access Specifiers

### AIM : To implement a Student class using encapsulation (getters and setters) and validate student grade input.

### ALGORITHM :

STEP 1 : Start

STEP 2 : Define Student class with private variables: id, name, grade

STEP 3 : Create setter and getter methods

STEP 4 : Create method to add grade with validation (0–100)

STEP 5 : Read student details (id, name, grade)

STEP 6 : If grade is valid → display student details

STEP 7 : Else → display error message

STEP 8 : End

### PROGRAM :
```
import java.util.Scanner;

class Student {
    private int student_id;
    private String student_name;
    private int grade;  

    public void setStudentId(int student_id) {
        this.student_id = student_id;
    }

    public void setStudentName(String student_name) {
        this.student_name = student_name;
    }

    public int getStudentId() {
        return student_id;
    }

    public String getStudentName() {
        return student_name;
    }

    public int getGrade() {
        return grade;
    }

    public boolean addGrade(int grade) {
        if (grade >= 0 && grade <= 100) {
            this.grade = grade;
            return true;
        } else {
            return false;
        }
    }

    public void display() {
        System.out.println("Student ID: " + student_id);
        System.out.println("Student Name: " + student_name);
        System.out.println("Grade: " + grade);
        System.out.println("-----------------------");
    }
}
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        Student student = new Student();
        student.setStudentId(sc.nextInt());
        sc.nextLine();
        student.setStudentName(sc.nextLine());     
        int grade = sc.nextInt();

        if (student.addGrade(grade)) {
            student.display();
        } else {
            System.out.println("Invalid grade. Please enter a value between 0 and 100.");
        }

        sc.close();
    }
}

```

### OUTPUT :

<img width="1245" height="571" alt="image" src="https://github.com/user-attachments/assets/2315d81b-fdea-4739-a7a3-64be8ea55b8f" />

### RESULT :

Thus to implement a Student class using encapsulation (getters and setters) and validate student grade input was successfully created.
