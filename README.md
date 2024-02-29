# Folder Cleaner

## Overview

Folder Cleaner is a Python project consisting of two scripts: `folder_cleaner` and `auto_folder_cleaner`. These scripts are designed to organize a specific folder by cleaning and sorting its contents automatically.

## Features

- **One-Time Folder Cleaning (folder_cleaner):** This script runs once to organize the existing contents of the specified folder based on predefined rules.
- **Continuous Folder Cleaning (auto_folder_cleaner):** This script runs continuously, organizing the folder whenever new files are added.

## Usage

### Prerequisites

Before running the scripts, make sure you have the required dependencies installed. You can install them using:

```bash
pip install -r requirements.txt
One-Time Folder Cleaning (folder_cleaner)
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/folder_cleaner.git
cd folder_cleaner
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Configure Rules (Optional):

Open the folder_cleaner.py file.
Modify the rules as needed based on your folder organization preferences.
Run the script:

bash
Copy code
python folder_cleaner.py
The script will analyze the specified folder and organize its existing contents according to the rules you defined.

Continuous Folder Cleaning (auto_folder_cleaner)
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/folder_cleaner.git
cd folder_cleaner
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Configure Rules (Optional):

Open the auto_folder_cleaner.py file.
Modify the rules as needed based on your folder organization preferences.
Run the script:

bash
Copy code
python auto_folder_cleaner.py
The auto_folder_cleaner script will continuously monitor the specified folder and organize its contents whenever new files are added.

Example
Consider the following folder structure before running the scripts:

lua
Copy code
project_folder/
|-- unorganized/
|   |-- document.pdf
|   |-- image.jpg
|   |-- archive.zip
|-- organized/
After running both scripts, the folder structure might look like:

lua
Copy code
project_folder/
|-- unorganized/
|-- organized/
    |-- Documents/
        |-- document.pdf
    |-- Images/
        |-- image.jpg
    |-- Archives/
        |-- archive.zip
This is just an example, and you can customize the rules to match your specific needs for both scripts.

Contributing
If you find any issues or have suggestions for improvement, feel free to open an issue or create a pull request.

vbnet
Copy code

Feel free to copy and paste this into your project's README.md file. Adjust the content
