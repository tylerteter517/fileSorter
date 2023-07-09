# fileSorter
# File Organizer

This script is designed to organize files in a specified directory by moving them into separate folders based on their file extensions. The script categorizes files into four main types: CSV files, image files, PDF files, and text files. It utilizes the `os` and `shutil` modules in Python.

## Prerequisites

- Python 3.x
- `os` module
- `shutil` module

## Usage

1. Ensure that you have Python installed on your system.
2. Download or clone the repository containing this script.
3. Open the script in a text editor.
4. Modify the `path` variable to specify the directory where your files are located. Make sure to use the correct path format for your operating system.
5. Run the script using a Python interpreter.

```python
python file_organizer.py
```

## How it works

1. The script creates four folders (`csv files`, `image files`, `pdf files`, and `text files`) in the specified directory if they don't already exist.
2. It retrieves the list of files in the specified directory.
3. For each file, it checks the file extension and moves it to the appropriate folder if it matches one of the predefined extensions.
4. If a file does not match any of the predefined extensions, it prints a message indicating that the file was not moved.
5. Any errors encountered during the process are captured and stored in the `error` list.
6. Finally, the script prints the list of errors, if any.

**Note:** Please ensure that you have appropriate read and write permissions for the specified directory.

Happy organizing!
