# JAVAsem2
# School Administration Management System

A Java OOP project demonstrating **Inheritance** and **Runtime Polymorphism** through a simple school role management system.

---

## Project Structure

```
SchoolManagementSystem.java
└── Person          (Base class)
    ├── Teacher     (Subclass)
    └── Student     (Subclass)
```

---

## Classes

### Person (Base Class)
- Attributes: `name`, `age`
- Method: `showRole()` — prints a general message

### Teacher (extends Person)
- Extra Attributes: `subject`, `salary`
- Overrides: `showRole()` — prints teacher-specific info

### Student (extends Person)
- Extra Attributes: `rollNumber`, `course`
- Overrides: `showRole()` — prints student-specific info

### Main Method
- Creates a `Person[]` array of size 2
- Stores a `Teacher` and `Student` object
- Loops through array and calls `showRole()` on each
- Demonstrates **runtime polymorphism**

---

## Requirements

- Java JDK 11 or above
- Any IDE (VS Code, IntelliJ, Eclipse) or terminal

---

## How to Run

**Step 1 — Compile**
```
javac SchoolManagementSystem.java
```

**Step 2 — Run**
```
java SchoolManagementSystem
```

---

## Expected Output

```
=== School Administration Management System ===

I am a Teacher. I teach students.
Name: Mr. Sharma | Age: 35 | Subject: Mathematics | Salary: 55000.0

I am a Student. I study subjects.
Name: Rahul | Age: 18 | Roll No: 101 | Course: Computer Science
```

---

## OOP Concepts Used

| Concept | How it's used |
|--------|----------------|
| Inheritance | Teacher and Student extend Person |
| Method Overriding | showRole() overridden in both subclasses |
| Runtime Polymorphism | Person[] array calls correct method at runtime |
| Constructors | super() used to pass data to parent class |

---

## Author
School Administration Management System — OOP Project  
Language: Java
