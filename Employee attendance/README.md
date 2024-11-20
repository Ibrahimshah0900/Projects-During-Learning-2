 **Employee Attendance Tracker**

**Overview**
The **Employee Attendance Tracker** is a Python-based project designed to manage employee attendance data efficiently. It stores employee information and daily attendance records in CSV files, generates attendance reports, and visualizes attendance data through graphs. The project is easy to use, making it ideal for small businesses or personal use.


## **Features**
1. **Add Employee**  
   - Add employee details, including Employee ID, Name, and Department.

2. **Add Attendance**  
   - Record daily attendance for employees, specifying whether they are present or absent.

3. **Generate Attendance Report**  
   - View the total number of days each employee was present.

4. **Department-Wise Report**  
   - Get a summary of total attendance for each department.

5. **Attendance Graph**  
   - Visualize employee attendance data using a bar graph.

6. **File Initialization**  
   - Automatically initializes `employee.csv` and `attendance.csv` files if they do not exist.

---

## **Technologies Used**
- **Python**:
  - `csv`: To handle CSV file operations.
  - `os`: For file handling.
  - `collections.defaultdict`: To simplify data aggregation.
  - `matplotlib`: For data visualization.

---

## **Setup Instructions**
1. Clone the repository or download the source code.
2. Ensure you have Python installed on your system.
3. Install the required library for graph visualization:
   ```bash
   pip install matplotlib
   ```
4. Run the program:
   ```bash
   python attendance_tracker.py
   ```

---

## **How to Use**
1. **Run the Program**: Launch the script in your terminal or Python environment.
2. **Select an Option**:
   - Choose from options like adding employees, recording attendance, generating reports, or viewing graphs.
3. **Follow Prompts**: Enter details such as Employee ID, Name, Date, or Status when prompted.

---

## **File Structure**
- **`employee.csv`**: Stores employee details:
  - Columns: `ID, Name, Department`.
- **`attendance.csv`**: Stores attendance records:
  - Columns: `Date, EmployeeID, Status`.

---

## **Example Usage**
### Add Employee
```text
Enter Employee ID: E001
Enter Name: John Doe
Enter Department: HR
Employee added successfully.
```

### Add Attendance
```text
Enter Date (YYYY-MM-DD): 2024-11-18
Enter Employee ID: E001
Enter Status (present/absent): present
Attendance recorded successfully.
```

### Generate Report
```text
Attendance Report:
Employee ID: E001, Total Days Present: 10
```

### Generate Graph
- A bar graph will display showing the number of days each employee was present.



## **Project Structure**
- **attendance_tracker.py**: Main program file.
- **employee.csv**: Employee details file (auto-created).
- **attendance.csv**: Attendance records file (auto-created).



## **Future Enhancements**
1. Add a graphical user interface (GUI).
2. Integrate with a database for larger datasets.
3. Provide export options for reports (e.g., PDF, Excel).

