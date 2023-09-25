# CRT-Intern
TO DO LIST APPLICATION


Project Name: TO-DO LIST APPLICATION

 
Project Overview:
The Task Management System is a Python-based command-line application that allows users to manage their tasks efficiently. This project provides a simple yet effective way to add, remove, mark tasks as completed, and list tasks. It utilizes JSON files for data persistence and includes error handling to ensure smooth user interaction. Let's explore the key features and tools used in this project:

Key Features:

1. Add a Task: Users can add tasks to the system by providing a description, priority level (high, medium, or low), and a due date in the format (YYYY-MM-DD).

2. Remove a Task: Users can remove tasks by specifying the task number they want to delete. The system will validate the input to prevent errors.

3. Mark a Task as Completed: Users can mark a task as completed, changing its status from "Not Done" to "Done." Like removal, this operation requires specifying the task number.

4. List Tasks: Users can view a list of all tasks in the system, displaying their description, priority, due date, and completion status.

5. Data Persistence: The system uses JSON files to store tasks. This ensures that tasks are saved between program executions, providing continuity for the user.

6.Error Handling: The system includes error handling to handle invalid inputs gracefully. Users receive clear messages when they provide incorrect input.

Tools Used:

1. JSON: The project utilizes the JSON format for data storage and retrieval. It makes use of Python's `json` module to read and write task data to/from a JSON file (`tasks.json`).

2. File I/O: Python's file input/output operations are employed for reading and writing tasks to the JSON file. The `open` function is used for file handling.

3. Datetime: The `datetime` module is used to work with due dates, ensuring they are in the correct format and providing date-related functionality.

4.User Input Handling: The project takes user input using the `input` function and validates it to prevent errors during task management operations.

How to Use:
1. Run the script in a Python environment.
2. Follow the menu prompts to add, remove, complete, or list tasks.
3. Tasks are stored in `tasks.json` and persist between program runs.
4. Choose the "Quit" option to exit the program.

Conclusion:
The Task Management System project provides a straightforward and effective way for users to manage their tasks from the command line. It uses Python's built-in libraries and JSON for data storage, making it accessible and easy to use for task management. The project can be further extended with additional features, such as task categorization or task deadlines, to enhance its functionality.
