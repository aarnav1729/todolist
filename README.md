# To-Do List CLI Application

This repository contains a simple to-do list application that runs in the Command Line Interface (CLI). The application is built using Python and allows users to manage their tasks efficiently.

## Features
- **Add Tasks:** Users can easily add new tasks to their to-do list.
- **View Tasks:** Displays all the tasks along with their current status (completed or pending).
- **Complete Tasks:** Users can mark tasks as completed, which updates their status.
- **Remove Tasks:** Provides an option to remove tasks from the list if they are no longer needed.

## Installation
1. Clone the repository:
   git clone https://github.com/aarnav1729/todolist.git
2. Navigate to the project directory:
   cd todolist
3. Install the required dependencies:
   pip install -r requirements.txt

## Usage
Run the application using the following command:
   python run.py
Upon running, you will be prompted with a menu to manage your to-do tasks. You can add, view, complete, or remove tasks using the respective options.

## File Structure
- `run.py`: The main entry point for the application, handling user input and displaying the menu.
- `models.py`: Contains the `Task` model which defines the structure of a to-do task.
- `routes.py`: Defines the CLI commands and routes, mapping user inputs to their respective functions.
- `config.py`: Configuration settings for the application.
- `forms.py`: Handles the input forms for tasks, validating user input.
- `requirements.txt`: Lists the dependencies required to run the application.
- HTML and CSS files: These are placeholders for a potential future web-based version of the application.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests. For major changes, it is advisable to open an issue first to discuss the changes you would like to make.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
