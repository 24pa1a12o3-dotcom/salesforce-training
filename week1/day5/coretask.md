
# Day 5 - Apex Introduction Core Tasks

# Task 1: Connect Everything Learned Till Now

## College Management System Integration

### CRM
The CRM system manages student admissions, faculty interactions, and course registrations efficiently.

### Objects
- Student
- Faculty
- Course
- Department
- Fee

### Relationships
- One Department has many Students
- One Faculty teaches many Courses
- One Course contains many Students

### Validation Rules
- Student email cannot be empty
- Course seats cannot exceed limit
- Phone number must contain valid digits

### Formula Fields
- Remaining Seats
- Attendance Percentage
- Fee Balance

### Flow Automation
- Auto email after registration
- Automatic fee reminder notifications
- Auto update remaining seats

### Apex Usage
Apex is used when business logic becomes complex and cannot be handled using Flow alone.

---

# Task 2: Apex Thinking Exercise

## Cases Where Flow is NOT Enough

### 1. Complex Fee Calculation
Different discounts and scholarship rules require advanced logic.

### Why Apex?
Flow becomes difficult to manage for nested calculations and conditions.

---

### 2. Integration with External Payment Gateway
College fee payment system connects with external banking APIs.

### Why Apex?
External API integration requires HTTP callouts and custom handling.

---

### 3. Advanced Eligibility Logic
Eligibility depends on attendance, marks, department rules, and special conditions.

### Why Apex?
Complex decision-making requires custom programming logic.

---

# Task 3: Simple Programming Logic

## Pseudocode Examples

### Example 1
IF course seats are full  
THEN block new registration

---

### Example 2
IF attendance percentage is below 75%  
THEN notify student and faculty

---

### Example 3
IF fee payment is overdue  
THEN send reminder email

---

### Example 4
IF student marks are greater than 90%  
THEN assign scholarship eligibility

---

# Task 4: Reflection Task

Enterprise systems cannot always depend only on clicks and configuration because:
- Business logic can become highly complex
- External integrations require programming
- Large-scale systems need flexible customization
- Performance optimization may require coding
- Advanced automation needs custom logic

Apex helps developers create scalable and flexible enterprise applications inside Salesforce.
