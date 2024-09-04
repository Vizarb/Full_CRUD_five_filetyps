# Full CRUD Operations in Python

This project demonstrates full CRUD (Create, Read, Update, Delete) operations for various file formats and databases, including CSV, JSON, Excel, XML, and SQLite.

## Requirements

- Python 3.x
- `openpyxl` for Excel file operations
- `lxml` for XML file operations

Install the required libraries using pip:

    ```bash
    pip install openpyxl lxml

    Script Overview
    crud_operations.py
    This script contains functions to perform CRUD operations on:

    CSV Files
    JSON Files
    Excel Files
    XML Files
    SQLite Database
    1. CSV (Comma-Separated Values)
    Create: create_csv(filename, data)
    Read: read_csv(filename)
    Update: update_csv(filename, old_data, new_data)
    Delete: delete_csv(filename, data_to_delete)
    2. JSON (JavaScript Object Notation)
    Create: create_json(filename, data)
    Read: read_json(filename)
    Update: update_json(filename, old_data, new_data)
    Delete: delete_json(filename, data_to_delete)
    3. Excel
    Create: create_excel(filename, data)
    Read: read_excel(filename)
    Update: update_excel(filename, old_data, new_data)
    Delete: delete_excel(filename, data_to_delete)
    4. XML (eXtensible Markup Language)
    Create: create_xml(filename, data)
    Read: read_xml(filename)
    Update: update_xml(filename, old_data, new_data)
    Delete: delete_xml(filename, data_to_delete)
    5. SQLite
    Create: create_sqlite(filename)
    Insert: insert_sqlite(filename, data)
    Read: read_sqlite(filename)
    Update: update_sqlite(filename, old_data, new_data)
    Delete: delete_sqlite(filename, data_to_delete)
    Usage
    You can modify the example data and filenames in the script to fit your needs. Each section demonstrates creating, reading, updating, and deleting data for the respective file format or database.

    License
    This project is licensed under the MIT License - see the LICENSE file for details.

    vbnet
    Copy code

    Feel free to copy and use the code and README as needed. If you have any more questions or need further modifications, just let me know!