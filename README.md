# To-Do List Application

A simple and interactive to-do list application built using Python's Tkinter library for the GUI. This app allows you to manage tasks by adding, editing, marking as done, and deleting tasks. It also features a JSON-based data persistence system, so your tasks are saved between sessions.

## Features

- **Add Tasks**: Add tasks with a title, description, and category.
- **Edit Tasks**: Modify existing tasks.
- **Mark as Done**: Mark tasks as complete with a visual indicator.
- **Delete Tasks**: Remove tasks from the list.
- **Data Persistence**: Tasks are saved in a JSON file (`tasks.json`), allowing them to persist across sessions.
- **Customizable Background**: Add a background image by placing a file named `file.png` in the project directory.

## Requirements

- Python 3.x
- Tkinter (comes pre-installed with Python)
- Pillow (for handling the background image)

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/todo-list-app.git
    cd todo-list-app
    ```

2. **Install dependencies**:
    - Tkinter is usually included with Python. If it's not installed, follow [Tkinter installation instructions](https://tkdocs.com/tutorial/install.html) for your platform.
    - Install Pillow (for image handling) using pip:
    ```bash
    pip install Pillow
    ```

## Usage

1. **Run the app**:
    ```bash
    python todo_app.py
    ```

2. **Add Tasks**: You can add tasks by entering a title, description, and category.
3. **Edit Tasks**: Select a task, edit the details, and save the changes.
4. **Mark as Done**: Select a task and click "Mark as Done" to complete it.
5. **Delete Tasks**: Select a task and click "Delete Task" to remove it.

## File Structure

- `todo_app.py`: The main Python file containing the To-Do List app code.
- `tasks.json`: JSON file that stores all tasks data.
- `file.png`: The background image file (optional).

## Screenshots

![image](https://github.com/user-attachments/assets/019636e5-a0f0-4ab1-92da-fa9ef8ae5c02)

## Acknowledgements

- [Tkinter Documentation](https://docs.python.org/3/library/tkinter.html)
- [Pillow Documentation](https://pillow.readthedocs.io/)

## Future Enhancements

- Add a graphical summary of task categories.
- Implement sorting and filtering options.
- Add support for task deadlines and notifications.

**File Structure**
- todo-list-app/
- ├── todo_app.py        # Main application file
- ├── tasks.txt          # File for storing tasks
- ├── file.png           # Background image for the GUI
- └── README.md          # Project documentation

**Contributing**
If you'd like to contribute to this project, please fork the repository and submit a pull request. Your contributions are welcome!



