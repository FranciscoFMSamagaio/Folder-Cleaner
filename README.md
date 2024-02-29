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
```
## One-Time Folder Cleaning (folder_cleaner)

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/folder_cleaner.git
    cd folder_cleaner
    ```

2. **Set the Source Directory::**

   - Open the `folder_cleaner.py` file.
   - Set the SOURCE_DIR variable to the path of your source directory.

3. **Run the script:**

    ```bash
    python folder_cleaner.py
    ```

   The script will analyze the specified folder and organize its existing contents according to the rules you defined.

## Continuous Folder Cleaning (auto_folder_cleaner)

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/folder_cleaner.git
    cd folder_cleaner
    ```

2. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Set the Source Directory::**

   - Open the `aut_folder_cleaner.py` file.
   - Set the SOURCE_DIR variable to the path of your source directory.

4. **Run the script:**

    ```bash
    python auto_folder_cleaner.py
    ```

   The `auto_folder_cleaner` script will continuously monitor the specified folder and organize its contents whenever new files are added.

## Example

Consider the following folder structure before running the scripts:

```plaintext
project_folder/
|-- unorganized/
|   |-- document.pdf
|   |-- image.jpg
|   |-- archive.zip
|-- organized/
```

After running both scripts, the folder structure might look like:

```plaintext
project_folder/
|-- unorganized/
|-- organized/
|-- Documents/
|-- document.pdf
|-- Images/
|-- image.jpg
|-- Archives/
|-- archive.zip
```
This is just an example, and you can customize the rules to match your specific needs for both scripts.

## Contributing

If you find any issues or have suggestions for improvement, feel free to open an issue
