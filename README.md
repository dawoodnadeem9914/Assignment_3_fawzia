<div align="center">

# ☕ Java OOP Projects

### *Object-Oriented Programming concepts applied through hands-on Java projects*

[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](#)
[![OOP](https://img.shields.io/badge/OOP-0078D4?style=for-the-badge&logo=java&logoColor=white)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

<br/>

> Demonstrating core Object-Oriented Programming principles through practical Java implementations.

</div>

---

## 📋 Overview

This repository contains Java programs and projects that demonstrate core **Object-Oriented Programming (OOP)** principles — the foundation of modern software engineering.

Developed as part of the Java programming coursework at **University Putra Malaysia (UPM)**, these implementations cover the four pillars of OOP and show how abstract design concepts translate into working, maintainable code.

---

## 🧱 OOP Concepts Covered

| Concept | Description | Example in This Repo |
|---|---|---|
| **Encapsulation** | Bundling data and methods; hiding internal state | Private fields with getter/setter methods |
| **Inheritance** | Deriving new classes from existing ones | Subclasses extending a base class |
| **Polymorphism** | One interface, multiple implementations | Method overriding, interface implementation |
| **Abstraction** | Hiding complexity behind simple interfaces | Abstract classes and interfaces |

---

## 💡 Example: OOP in Action

```java
// Abstraction via interface
public interface Shape {
    double calculateArea();
    double calculatePerimeter();
    void display();
}

// Inheritance + Encapsulation
public class Circle extends BaseShape implements Shape {
    private double radius;  // Encapsulated field

    public Circle(double radius) {
        this.radius = radius;
    }

    // Polymorphism — overriding the interface method
    @Override
    public double calculateArea() {
        return Math.PI * radius * radius;
    }

    @Override
    public double calculatePerimeter() {
        return 2 * Math.PI * radius;
    }

    @Override
    public void display() {
        System.out.printf("Circle | Radius: %.2f | Area: %.2f | Perimeter: %.2f%n",
            radius, calculateArea(), calculatePerimeter());
    }
}
```

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/dawoodnadeem9914/Assignment_3_fawzia.git
cd Assignment_3_fawzia

# Compile
javac Main.java

# Run
java Main
```

Or open in **IntelliJ IDEA** and run directly.

---

## 🔮 Future Improvements

- [ ] Add design patterns (Singleton, Factory, Observer)
- [ ] Add unit tests using JUnit 5
- [ ] Refactor into a structured multi-package project
- [ ] Add JavaDoc documentation to all classes

---

## 👨‍💻 Author

**Dawood Nadeem**  
BSc Computer Science @ University Putra Malaysia (UPM)  
📧 [Captaindawood12@gmail.com](mailto:Captaindawood12@gmail.com)  
🔗 [GitHub](https://github.com/dawoodnadeem9914)

---

<div align="center">

*Java OOP Coursework @ UPM*

</div>
