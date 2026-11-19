
# Task Management System

## Project Overview
The Task Management System is a Python-based command-line application designed to help users organise and manage their daily tasks.

Users can create, view, search, update, complete and delete tasks. The application stores task information in a JSON file so that records remain available after the application is closed and restarted.

## Features
- Add new tasks.
- View all available tasks.
- Search tasks using a unique Task ID.
- Update existing task details.
- Mark tasks as completed.
- Delete tasks with confirmation.
- Validate user inputs.
- Store and retrieve tasks using JSON.
- Display a menu-driven command-line interface.

## Technologies Used
- Python
- JSON
- Google Colab
- Google Drive
- GitHub

## Task Information
Each task contains:
- Task ID
- Title
- Description
- Status
- Priority
- Due Date

## How to Run the Application
1. Download or clone the project repository.
2. Make sure Python 3 is installed.
3. Open a terminal in the project folder.
4. Run the following command:

```bash
python main.py
```

5. Select an option from the application menu.

## Data Storage
Task records are stored in the `tasks.json` file. The application automatically saves changes and loads existing records when it starts.

## Project Files
- `main.py` – Main Python application.
- `tasks.json` – Stores task records.
- `README.md` – Project documentation.
- `Untitle5.ipynb` – Development notebook.

## Conclusion
This project demonstrates the use of Python programming concepts, functions, loops, conditional statements, input validation and JSON file handling to develop a simple task management application.
