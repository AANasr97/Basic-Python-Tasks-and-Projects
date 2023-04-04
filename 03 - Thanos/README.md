# Thanos Project

<img src="thanos.jpg">

### Description

This Python program performs file manipulation operations using the OS module. It is a demonstration of how to rename files in a folder and how to delete files randomly using Python.

### Usage

1. Clone the repository.
2. Navigate to the project directory.
3. Run the `thanos.py` file.

### Requirements

* Python 3.x
* tqdm

### Features

#### Renaming Files

The `rename_files()` function renames all files in the specified directory using the `os.rename()` method. It generates new filenames by adding a number to the end of each filename. The new filenames are stored in the same directory as the original files.

#### Start Destroying The World

The `thanos_snap()` function takes a list of filenames as an argument and deletes half of them randomly using the `os.remove()` method. The function first calculates the number of files to delete, which is half of the total number of files in the directory. It then loops through and deletes files randomly using the `random.choice()` method until the required number of files are deleted. After deleting the files, the function prints a message indicating that everything is balanced.

### Done By

#### Ahmed NasrElDin