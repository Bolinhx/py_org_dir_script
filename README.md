# File Organizer - Python

This project contains two Python scripts to help organize files in a directory. The **os** library (included in Python's standard library) was used for file system interactions, and Jupyter Notebook was used for testing during development.

- **in.py**: Organizes files into subdirectories based on their file extensions.
- **out.py**: Reverts the organization, moving files back to the original directory and deleting empty subdirectories.

## Prerequisites

- Python 3.x installed.

## How to use

### 1. `in.py`
This script organizes all files in a directory (excluding `.py` files and subdirectories) into separate folders based on their file extensions.

#### How to run:
1. Place the `in.py` script in the directory you want to organize.
2. Open a terminal or command prompt.
3. Navigate to the directory where the script is located.
4. Run the script with the following command:

```bash
python3 in.py
```
After running the script, the files will be organized into subdirectories, one for each file extension.

### 2. `out.py`
This script reverts the organization done by in.py. It removes files from the subdirectories and moves them back to the original directory. It also deletes any empty subdirectories.

#### How to run:
1. Place the `out.py` script in the directory you want to organize.
2. Open a terminal or command prompt.
3. Navigate to the directory where the script is located.
4. Run the script with the following command:

```bash
python3 out.py
```
After running the script, the files will be organized into subdirectories, one for each file extension.

## Notes
- Both scripts do not affect .py files or subdirectories.
- Ensure there are no important files inside the subdirectories, as the files will be moved, and the empty subdirectories will be deleted.
