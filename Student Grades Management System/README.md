

# Student Grades Management System

The **Student Grades Management System** is a Python-based tool designed to manage and analyze student grades efficiently. The system stores student information, subjects, and grades in a CSV file and provides functionalities like adding grades, viewing all grades, calculating average grades, and sorting students by their averages.

---

## Features

- **Add Grades**  
  Add new records for students, including their name, subject, and grade. Handles numeric validation for grades.

- **View Grades**  
  Display all stored student grade records in a tabular format.

- **Calculate Average Grades**  
  Calculate and display the average grade for each student.

- **Sort by Average Grades**  
  Sort students by their average grades in descending order and display the sorted results.

- **Error Handling**  
  Gracefully handles invalid grades, empty files, and missing data.

---

## Technologies Used

- **Python**
  - `csv` module: For reading from and writing to the CSV file.

---

## How to Use

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/student-grades-management-system.git
   cd student-grades-management-system
   ```

2. **Run the Script**
   Make sure Python 3 is installed on your system. Then, execute:
   ```bash
   python grades_management.py
   ```

3. **Choose an Option**
   Follow the on-screen menu:
   - `1`: Add a new grade.
   - `2`: View all recorded grades.
   - `3`: Calculate average grades for each student.
   - `4`: Sort students by their average grades.
   - `5`: Exit the program.

---

## Example Usage

### Adding Grades
```
--- Student Grades Management System ---
1. Add Grade
2. View Grades
3. Calculate Average Grades
4. Sort Students by Average Grades
5. Exit

Enter your choice: 1
Enter student name: Alice
Enter subject: Math
Enter grade: 95
Grade added for Alice in Math.
```

### Viewing Grades
```
--- Student Grades Management System ---
Enter your choice: 2
['Student Name', 'Subject', 'Grade']
['Alice', 'Math', '95']
```

### Calculating Averages
```
--- Student Grades Management System ---
Enter your choice: 3
Average Grades:
Alice: 95.00
```

### Sorting Students by Average Grades
```
--- Student Grades Management System ---
Enter your choice: 4
Students Sorted by Average Grades:
Alice: 95.00
```

---

## Folder Structure

```
.
├── grades_management.py   # Main Python script
├── grades.csv             # CSV file storing student grades (auto-created)
└── README.md              # Project documentation
```

---

## Learning Objectives

This project focuses on:
1. **Working with Tabular Data**
   - Reading, writing, and updating CSV files.
2. **Error Handling**
   - Validating user input and handling file errors gracefully.
3. **Data Aggregation**
   - Calculating averages and sorting data programmatically.
4. **Python Programming**
   - Modular programming using functions for better code organization.

---

## Future Enhancements

- Add a graphical user interface (GUI) for ease of use.
- Include functionality to edit or delete existing grades.
- Provide detailed analytical reports, such as top-performing subjects or students.

