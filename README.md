# 🎓 Student Record Management System (CLI-Based)

## 📌 Objective

Build a simple **Command-Line Interface (CLI)** based application in Java to **perform CRUD operations** on student records. This project is a part of an internship task for learning basic Java and data structures.

---

## 🛠️ Tools & Technologies

- **Java (JDK)**
- **VS Code / IntelliJ CE**
- Command Line / Terminal

---

## 📚 Features

- Add new student records
- View all student records
- Update existing student records by ID
- Delete student records by ID

---

## 🧩 Data Structure Used

- `ArrayList<Student>` to store and manage dynamic student records in memory.

---

## 🧾 Class Structure

### 1. `Student.java`
Model class with:
- `id` (int)
- `name` (String)
- `marks` (double)

### 2. `StudentManagementSystem.java`
Main class containing:
- Menu-driven UI
- CRUD logic (Add, View, Update, Delete)

---

## ▶️ How to Run

### 🔧 Compile the Program
```bash
javac Student.java StudentManagementSystem.java
