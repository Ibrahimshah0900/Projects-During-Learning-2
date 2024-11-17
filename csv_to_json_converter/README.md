

# CSV to JSON Converter

A simple and efficient tool that converts data from a CSV file to JSON format. This project demonstrates the use of Python's built-in modules for handling structured data and error handling during file operations.

## Features
- Reads data from a CSV file.
- Converts the data into JSON format.
- Writes the JSON data to a new file.
- Includes robust error handling for:
  - File existence and format validation.
  - Handling permission issues.
  - Catching unexpected errors.

## Technologies Used
- Python
- `csv` module for reading CSV files.
- `json` module for writing JSON files.
- `os` module for file validation.

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/csv-to-json-converter.git
   cd csv-to-json-converter
   ```

2. **Prepare Input**:
   - Place the CSV file you want to convert in the project directory.

3. **Run the Script**:
   - Update the file paths in the script:
     ```python
     csv_to_json('your-input-file.csv', 'your-output-file.json')
     ```
   - Run the script:
     ```bash
     python converter.py
     ```

4. **Output**:
   - The JSON file will be created in the specified output path.

## Example

Input CSV (`example.csv`):
```csv
Name,Age,City
John,30,New York
Jane,25,Los Angeles
Doe,22,Chicago
```

Output JSON (`output.json`):
```json
[
    {
        "Name": "John",
        "Age": "30",
        "City": "New York"
    },
    {
        "Name": "Jane",
        "Age": "25",
        "City": "Los Angeles"
    },
    {
        "Name": "Doe",
        "Age": "22",
        "City": "Chicago"
    }
]
```

## Error Handling
The script includes error handling for:
- **File Not Found**: If the specified CSV file does not exist.
- **Invalid File Format**: Ensures the input file is in CSV format.
- **Permission Issues**: Handles cases where the script lacks the necessary permissions.
- **Unexpected Errors**: Catches any unforeseen issues and provides meaningful feedback.

## Learning Focus
This project is part of a learning journey to understand:
- Data conversion between structured formats.
- File handling in Python.
- Error handling and validations for robust programming.

