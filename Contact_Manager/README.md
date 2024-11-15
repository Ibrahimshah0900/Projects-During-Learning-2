

# Contact Manager

A simple **Contact Manager** application built using Python and the CSV module. This tool allows users to manage their contact information, including names, phone numbers, and emails, by performing CRUD (Create, Read, Update, Delete) operations on a CSV file.



## Features
- **Add Contact**: Easily add new contact details to the CSV file.
- **View Contacts**: Display all stored contacts in a tabular format.
- **Search Contact**: Search for a contact by name or email.
- **Update Contact**: Update the details of an existing contact.
- **Delete Contact**: Remove a contact from the file.
- **Persistence**: All data is saved in the `contacts.csv` file for future use.


## Technologies Used
- **Programming Language**: Python
- **File Format**: CSV
- **Modules**: 
  - `csv`: For reading, writing, and managing CSV files.



## Getting Started

### Prerequisites
- Python 3.x installed on your machine.

### Installation
1. Clone the repository or download the script file:
   ```bash
   git clone https://github.com/yourusername/contact-manager.git
   ```
2. Navigate to the project directory:
   ```bash
   cd contact-manager
   ```
3. Ensure Python is set up correctly:
   ```bash
   python --version
   ```

---

## Usage

1. Run the application:
   ```bash
   python contact_manager.py
   ```
2. Follow the on-screen menu to:
   - Add, view, search, update, or delete contacts.

---

## File Structure
- **`contact_manager.py`**: Main script containing all functionality.
- **`contacts.csv`**: CSV file where all contact details are stored. This file is auto-created if it doesn’t exist.

---

## Sample Workflow

1. **Adding a Contact**:
   - Input:  
     ```
     Name: John Doe  
     Phone: 1234567890  
     Email: john.doe@example.com
     ```
   - Output:  
     ```
     Contact John Doe added successfully!
     ```

2. **Viewing Contacts**:
   - Output:  
     ```
     Name                 Phone          Email
     --------------------------------------------------
     John Doe             1234567890     john.doe@example.com
     ```

3. **Updating a Contact**:
   - Input:  
     ```
     Old Name: John Doe  
     New Name: Johnathan Doe  
     New Phone: 0987654321  
     New Email: john.doe@newmail.com
     ```
   - Output:  
     ```
     Contact John Doe updated successfully!
     ```

4. **Deleting a Contact**:
   - Input:  
     ```
     Name: Johnathan Doe
     ```
   - Output:  
     ```
     Contact Johnathan Doe deleted successfully!
     ```

5. **Searching for a Contact**:
   - Input:  
     ```
     Query: john
     ```
   - Output:  
     ```
     {'Name': 'John Doe', 'Phone': '1234567890', 'Email': 'john.doe@example.com'}
     ```

---

## Learning Outcomes
- Understanding of CRUD operations with CSV files.
- Hands-on experience with Python’s `csv` module for file management.
- Efficient handling of user inputs and persistent data storage.



