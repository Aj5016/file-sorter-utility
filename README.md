# File Sorter Utility

A powerful and flexible Python script designed to automatically organize files in a directory based on their extensions. It helps keep your workspace clean by sorting cluttered folders into categorized subdirectories.

## Features

- **Automated Sorting**: Moves files into designated folders (e.g., Images, Documents, Videos) based on their file extensions.
- **Recursive Cleanup**: Option to scan and sort files within nested subdirectories.
- **Dry Run Mode**: Preview the changes that will be made without actually moving any files.
- **Exclusions**: Skip specific files or folders from being processed.
- **Customizable**: Easily add or modify file extensions and category names in the script.

## Prerequisites

- **Python 3.6 or higher** must be installed on your system. No external dependencies are required.

## Installation

1. Clone this repository or download the script:
   git clone https://github.com/Aj5016/file-sorter-utility.git
   
2. Navigate to the downloaded directory:
   cd file-sorter-utility

## Usage

Run the script from your terminal or command prompt. By default, it will organize the directory it is executed in.

### Basic Usage

python file_sorter.py


### Dry Run (Preview Changes)
To see what files will be moved without actually making any changes, use the dry-run flag (if you configured it via command-line arguments in your script):

python file_sorter.py --dry-run


*(Note: Update the command examples above based on the exact arguments your script accepts, such as `--path`, `--recursive`, or `--exclude`)*

## Customizing Categories

To change how files are categorized, open `file_sorter.py` in a text editor and modify the dictionary mapping extensions to folder names. For example:

CATEGORIES = {
    "Images": [".jpg", ".jpeg", ".png", ".gif"],
    "Documents": [".pdf", ".docx", ".txt", ".xlsx"],
    "Archives": [".zip", ".tar", ".gz", ".rar"]
}


## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Aj5016/file-sorter-utility/issues) if you want to contribute.

## License

This project is open-source and available under the [MIT License](LICENSE).

*** 
