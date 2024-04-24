# Project "Python Notes Journal"

This project is a program for working with notes, created using the Python programming language version 3.11.2 in the PyCharm development environment.

## Functionality
The "Notes Journal" program has the following functionality:
- Displaying the notes journal
- Displaying notes by unique identifier (id)
- Displaying notes by date
- Adding new notes to the journal
- Editing existing notes by identifier
- Deleting notes by identifier

## Project Description
The project was implemented using Pull requests to merge changes from the dev branch into the master branch. The "Notes Journal" application stores data about notes in a text file and provides convenient management of the entries.

## Installing

1. Clone repository

```git clone https://github.com/MilaEgoshina/python_notions```

2. Creating a virtual environment

```python3 -m venv venv```

3. Activation of the virtual environment

```source venv/bin/activate``

4. Running a script to demonstrate the capabilities of python_notions

```python3 main.py --help```

## Project Structure
- Note.py - contains the Note class for representing a note
- controller.py - file with the main application logic
- commands.py - contains methods of the main commands for working with notes
- counter.py - file with a counter for automatically assigning identifiers to notes
- loadFromFile.py - module for extracting data from the notes journal file
- writeToFile.py - module for writing data of the notes journal to a file
- UI - folder with the user interface components

## Usage
1. Make sure you have Python version 3.11.2 installed
2. Download the project repository
3. Run the main.py file to start the application
4. Follow the instructions in the console to work with the notes

## Project Development
The project can be further developed and improved by adding new features, enhancing the user interface, and optimizing the code.
