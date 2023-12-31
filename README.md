# Project: Log Analysis

This project is designed to help students understand file systems, relative file paths, and basic data analysis in Python. The task involves reading data from log files, extracting useful information, and writing a summary report.

The project has the following directory structure:

```
.
├── Logs
│   ├── log1.txt
│   ├── log2.txt
│   └── log3.txt
└── Reports
```

- `Logs`: This directory contains several log files (log1.txt, log2.txt, log3.txt). Each log file contains multiple lines of text, with each line representing an event or error that was logged by a system.

- `Reports`: This directory will contain the final output of the project, i.e., the summary reports for each log file.


## Instructions
1. Read the log files from the `Logs` directory. Each line in a log file represents a logged event or error.
2. For each log file, count the number of each type of event or error. Assume that each line begins with a timestamp, followed by a colon, and then the event or error type (e.g., "ERROR: File not found").
3. Write a summary report for each log file in the `Reports` directory. The report should list each type of event or error and the number of times it occurred. The report file should be named `Report_for_<log>.txt`, where `<log>` is the name of the log file.


## Tips 

1. **Listing all files in a directory**: You can use the `os.listdir()` function to get a list of all files in a directory. For example, `os.listdir('./Logs')` will return a list of all files in the `Logs` directory.

2. **Building file paths**: You can use string formatting to build file paths. For example, `f'./Logs/{filename}'` will create a file path to a file in the `Logs` directory. Similarly, `f'./Reports/Report_for_{filename}'` will create a file path to a file in the `Reports` directory.

3. **Reading files**: You can use the `with open()` statement to open a file for reading. This ensures that the file is properly closed after you're done with it. For example, `with open(filepath, 'r') as file:` will open a file for reading.

4. **Writing files**: You can also use the `with open()` statement to open a file for writing. For example, `with open(filepath, 'w') as file:` will open a file for writing.

5. **Reading lines in a file**: You can use a `for` loop to read each line in a file. For example, `for line in file:` will loop over each line in a file.

6. **Writing lines to a file**: You can use the `write()` method to write a line to a file. For example, `file.write(line)` will write a line to a file.

7. **Checking if a string is in a line**: You can use the `in` keyword to check if a string is in a line. For example, `'ERROR' in line` will check if the string 'ERROR' is in the line.
‣湁污獹湩䱧杯ੳ‣湁污獹湩䱧杯ੳ‣湁污獹湩䱧杯ੳ