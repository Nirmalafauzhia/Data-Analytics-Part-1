# 1. Data Basics
# 1.1 Define the concept of data
Data is a collection of facts, information, or values that are recorded, stored, or represented in various forms, such as numbers, text, images, sound, or other formats.
# 1.2 Describe basic data variable types 
• boolean

In Python, the bool data type is used to represent boolean values (True, False). Booleans are used to evaluate expressions and return the boolean True or False based on the result of the expression.

x = 10

y = 5

result = x > y

print(result)

print(type(result))

• numeric

The numeric data type in Python represents the data that has a numeric value. A numeric value can be an integer, a floating number, or even a complex number. These values are defined as Python int, Python float, and Python complex classes in Python.

• string

In Python, the str data type is used to define text component enclosing a sequence of characters within single-quotes or double-quotes. Python strings can contain letters, numbers or special characters.

platform = "JC Chouinard"

print(type(platform))

print(platform)
# 1.3 Describe basic structures used in data analytics
• tables

Tables are used to structured data, it is essentially a two-dimensional structure with rows and columns.

• rows

Rows, also known as records or observations, are the horizontal elements in a table.

• columns

Columns, also known as fields or variables, are the vertical elements in a table. Each column represents a specific attribute or piece of information related to the data set.

• lists

While tables are used for structured data, lists are used for storing unstructured or semi-structured data. A list is a collection of items, where each item can be of a different data type or structure. Lists are often used for tasks like storing unstructured text data, logs, or simple collections of values.
# 1.4 Describe data categories
• qualitative

Survey responses where participants choose from option like “Yes” or “No”.

• quantitative

Sales data showing the number of products sold and prices.

• structured

- Structured data is data that organized and formatted in a way that easy to read

- Student records are stored in the university’s SQL database, containing columns such as Student_ID, Student Name, and Major

• unstructured

- Unstructured data has no particular structure and is difficult to organize or categorize

- This includes Text, images, audio, and video files

- Example : Social media posts, email, images, audio recording.

• metadata

Metadata in this context refers to information about the healthcare data. It includes details such as data source, data format, data creation timestamp, patient ID, data quality, and more.

• big data

The healthcare system collects patient records, medical images, sensor data from wearable devices, electronic health records (EHRs), and more.
# 2. Data Manipulation
# 2.1 Import, store, and export data 
# Fundamental understanding of ETL:
# • extract
# • transform
# • load
# • common data storage file formats (delimited data files, XML, JSON)
# 2.2 Clean data
# Purpose and common practices:
# • handling NULL
# • special characters
# • trimming spaces
# • inconsistent formatting
# • removing duplicates 
# • imputing data
# • validating data
# 2.3 Organize data
# Purpose and common practices:
# • sorting
# • filtering
# • slicing
# • transposing 
# • appending
# • truncating
# 2.4 Aggregate data
# Purpose and common practices:
# • grouping
# • joining/merging 
# • summarizing
# • pivoting
