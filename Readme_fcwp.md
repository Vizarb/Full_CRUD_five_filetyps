Certainly! Here's a `README.md` file formatted for the provided Python script that demonstrates full CRUD operations for CSV, JSON, Excel, XML, and SQLite. You can copy and paste this into your `README.md` file.

---

# Full CRUD Operations in Python

This project demonstrates full CRUD (Create, Read, Update, Delete) operations for various file formats and databases using Python. The script covers:

1. **CSV Files**
2. **JSON Files**
3. **Excel Files**
4. **XML Files**
5. **SQLite Database**

## Overview

The provided script implements the following functionalities:

- **CSV (Comma-Separated Values)**
  - Create and write CSV data
  - Read CSV data
  - Update CSV data
  - Delete CSV data

- **JSON (JavaScript Object Notation)**
  - Create and write JSON data
  - Read JSON data
  - Update JSON data
  - Delete JSON data

- **Excel**
  - Create and write Excel data
  - Read Excel data
  - Update Excel data
  - Delete Excel data

- **XML (eXtensible Markup Language)**
  - Create and write XML data
  - Read XML data
  - Update XML data
  - Delete XML data

- **SQLite**
  - Create and insert data into an SQLite database
  - Read data from SQLite database
  - Update data in SQLite database
  - Delete data from SQLite database

## Requirements

To run this script, you'll need the following Python libraries:

- `pandas`
- `openpyxl` (for Excel files)
- `xml.etree.ElementTree` (for XML files)
- `sqlite3` (for SQLite databases)

You can install the required libraries using pip:

```sh
pip install pandas openpyxl
```

## Usage

### CSV Files

#### Create and Write CSV Data

```python
create_csv(filename, data)
```

#### Read CSV Data

```python
read_csv(filename)
```

#### Update CSV Data

```python
update_csv(filename, old_data, new_data)
```

#### Delete CSV Data

```python
delete_csv(filename, data_to_delete)
```

### JSON Files

#### Create and Write JSON Data

```python
create_json(filename, data)
```

#### Read JSON Data

```python
read_json(filename)
```

#### Update JSON Data

```python
update_json(filename, old_data, new_data)
```

#### Delete JSON Data

```python
delete_json(filename, data_to_delete)
```

### Excel Files

#### Create and Write Excel Data

```python
create_excel(filename, data)
```

#### Read Excel Data

```python
read_excel(filename)
```

#### Update Excel Data

```python
update_excel(filename, old_data, new_data)
```

#### Delete Excel Data

```python
delete_excel(filename, data_to_delete)
```

### XML Files

#### Create and Write XML Data

```python
create_xml(filename, data)
```

#### Read XML Data

```python
read_xml(filename)
```

#### Update XML Data

```python
update_xml(filename, old_data, new_data)
```

#### Delete XML Data

```python
delete_xml(filename, data_to_delete)
```

### SQLite Database

#### Create and Insert Data into SQLite Database

```python
create_sqlite(filename)
insert_sqlite(filename, data)
```

#### Read Data from SQLite Database

```python
read_sqlite(filename)
```

#### Update Data in SQLite Database

```python
update_sqlite(filename, old_data, new_data)
```

#### Delete Data from SQLite Database

```python
delete_sqlite(filename, data_to_delete)
```

## Example Usage

Here's how you can use the provided functions:

```python
# CSV Example
csv_data = [
    ['Name', 'Age', 'Occupation'],
    ['Alice', 30, 'Engineer'],
    ['Bob', 25, 'Data Scientist'],
    ['Charlie', 35, 'Teacher']
]
csv_filename = 'data.csv'
create_csv(csv_filename, csv_data)
read_csv(csv_filename)
update_csv(csv_filename, [['Bob', 25, 'Data Scientist']], [['Bob', 26, 'Senior Data Scientist']])
delete_csv(csv_filename, [['Charlie', 35]])

# JSON Example
json_data = {
    'Name': 'Alice',
    'Age': 30,
    'Occupation': 'Engineer'
}
json_filename = 'data.json'
create_json(json_filename, json_data)
read_json(json_filename)
update_json(json_filename, [json_data], [{'Name': 'Alice', 'Age': 31, 'Occupation': 'Senior Engineer'}])
delete_json(json_filename, [{'Name': 'Alice', 'Age': 31, 'Occupation': 'Senior Engineer'}])

# Excel Example
excel_data = {
    'Name': ['Alice', 'Bob', 'Charlie'],
    'Age': [30, 25, 35],
    'Occupation': ['Engineer', 'Data Scientist', 'Teacher']
}
excel_filename = 'data.xlsx'
create_excel(excel_filename, excel_data)
read_excel(excel_filename)
update_excel(excel_filename, [['Bob', 25]], [['Bob', 26, 'Senior Data Scientist']])
delete_excel(excel_filename, [['Charlie', 35]])

# XML Example
xml_data = {
    'person': [
        {'Name': 'Alice', 'Age': 30, 'Occupation': 'Engineer'},
        {'Name': 'Bob', 'Age': 25, 'Occupation': 'Data Scientist'},
        {'Name': 'Charlie', 'Age': 35, 'Occupation': 'Teacher'}
    ]
}
xml_filename = 'data.xml'
create_xml(xml_filename, xml_data)
read_xml(xml_filename)
update_xml(xml_filename, [{'Name': 'Bob'}], [{'Name': 'Bob', 'Age': 26, 'Occupation': 'Senior Data Scientist'}])
delete_xml(xml_filename, [{'Name': 'Charlie'}])

# SQLite Example
sqlite_filename = 'data.db'
create_sqlite(sqlite_filename)
insert_sqlite(sqlite_filename, [('Alice', 30, 'Engineer'), ('Bob', 25, 'Data Scientist'), ('Charlie', 35, 'Teacher')])
read_sqlite(sqlite_filename)
update_sqlite(sqlite_filename, [('Bob', 25)], [('Bob', 26, 'Senior Data Scientist')])
delete_sqlite(sqlite_filename, [('Charlie', 35)])
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

This `README.md` provides a comprehensive guide for users to understand how to use the script and perform CRUD operations on various data formats and databases.