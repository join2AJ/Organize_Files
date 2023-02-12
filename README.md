# Organize Files

This program helps you organize files into separate directories based on their file extensions. This is useful when you have a folder with a lot of different types of files and want to sort them in a more organized way.

## How to use
1. Copy the code into a file called `organize_files.py`
2. Open a terminal window and navigate to the directory where the file is located
3. Run the command `python organize_files.py`
4. The program will then run and sort your files into separate directories based on their file extensions.

## How it works
The program uses the `os` and `shutil` modules to interact with the file system and move files into their respective directories. It first gets the current working directory and then loops through all the files in that directory. For each file, it checks its file extension and then moves it into the appropriate directory based on that extension.

Here are the different directories and file extensions that are recognized by the program:

- Python files: `.py`
- Image files: `.jpg`, `.png`, `.gif`
- Excel files: `.xls`, `.xlsx`, `.xltx`, `.xlsm`
- Other files: all other file extensions

If a file extension is not recognized by the program, the file is moved into the "Other files" directory.

The program handles errors such as missing files and permissions errors by simply ignoring them and moving on to the next file.
