# Student Grade Tracker

A Java-based application to manage and track students' grades across multiple subjects. This project helps in recording, updating, and displaying student performance in a structured and efficient way.

---

## 🎯 Features

- Add student names and their subject-wise grades
- Calculate average grades per student
- Display all stored student information
- Simple console-based user interaction
- Object-Oriented Design using Java classes

---

## 🛠️ Technologies Used

- **Java** – Core application logic
- **Java Collections** – To store and manage student data (like `HashMap`, `ArrayList`)
- **OOP Principles** – Clean modular code using classes and methods

---

## 📁 Project Structure

student-grade-tracker/
├── src/
│ └── StudentGradeTracker.java # Main application file
├── README.md # Project documentation


---

## 💡 How It Works

1. Users (teachers/admins) can input student names and their grades per subject.
2. The app stores each student’s grades using data structures like maps/lists.
3. The user can then retrieve:
   - All students and their grades
   - Each student's average
   - Students who passed/failed (if applicable)

---

## 🧪 Sample Usage

```java
StudentGradeTracker tracker = new StudentGradeTracker();
tracker.addGrade("Priya", "Math", 85);
tracker.addGrade("Priya", "Science", 78);
tracker.displayGrades("Priya");
tracker.displayAllStudents();
# student-grade-tracker
A Java-based console application to manage and track students' grades across multiple subjects using object-oriented programming.
"# StudentGradeTracker" 
