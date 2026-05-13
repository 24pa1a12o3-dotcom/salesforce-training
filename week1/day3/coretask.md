
# Day 3 - Data Modeling Core Tasks

## Task 1: Design a College Management System

### Objects
- Student
- Faculty
- Course
- Department

### Relationships
- One Department can have many Students
- One Department can have many Faculty members
- One Faculty can teach many Courses
- One Course can have many Students

### Lookup Relationships
- Student → Department
- Faculty → Department
- Course → Faculty

---

# Task 2: Formula Thinking

## Formula Fields

### 1. Full Name
Combines First Name and Last Name automatically.

### 2. Remaining Seats
Remaining Seats = Total Seats - Enrolled Students

### 3. Percentage
Percentage = (Marks Obtained / Total Marks) * 100

### Why Formula Fields?
Formula fields reduce manual calculations and improve accuracy.

---

# Task 3: Validation Rule Thinking

## Validation Rules

### 1. Email cannot be empty
Prevents incomplete student records.

### 2. Student age cannot be negative
Prevents invalid age values.

### 3. Course seats cannot exceed limit
Prevents over-allocation of students.

---

# Task 4: Reflection Task

Structured data helps companies:
- Maintain accurate records
- Reduce duplicate data
- Improve reporting and automation
- Manage relationships between records efficiently

Using random spreadsheets can lead to data inconsistency and errors.
