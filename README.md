# Task Management System

## Project Overview
The Task Management System is a console-based application developed in C++ that allows users to efficiently manage and track their tasks. This application provides features for adding, editing, deleting, and marking tasks as complete. It also allows users to view all tasks and ensures that tasks are persisted between sessions through file storage. The system helps users stay organized and manage their to-do lists effectively.

## Key Features
- **Add Task**: Allows users to create new tasks with a description, category, priority, and due date.
- **Edit Task**: Provides functionality to edit existing tasks, including modifying the description, category, priority, and due date.
- **Delete Task**: Enables users to delete a task by specifying its unique ID.
- **Mark Task as Complete**: Users can mark a task as completed when it’s finished.
- **Display All Tasks**: Lists all tasks along with their details (description, category, priority, due date, and completion status).
- **Persistence**: Saves tasks to a text file (`tasks.txt`) to ensure that data is retained between application sessions.

## Tech Stack

### Programming Language:
- **C++**: The application is written in C++, utilizing object-oriented programming principles for structuring the task management functionality.

### Libraries and Tools:
- **C++ Standard Library**: Utilizes various features of the C++ Standard Library for task management:
  - `iostream`: For input and output operations.
  - `vector`: For dynamic array handling to store tasks.
  - `string`: For managing text data (task descriptions, categories, etc.).
  - `fstream`: For file reading and writing operations.
  - `sstream`: For string parsing and tokenization when reading and saving tasks.
  - `ctime` and `chrono`: For time-related operations like task due dates.
  - `iomanip`: For formatting the output (especially task display).
  - `algorithm`: For operations like sorting and searching tasks.
  
## Benefits and Use Cases
- **Task Organization**: The system helps users organize and prioritize their tasks effectively, making it easier to manage deadlines and responsibilities.
- **Simple to Use**: The console-based application is easy to navigate, providing users with a straightforward interface to manage their tasks.
- **Persistence**: With tasks being saved to a file, users can close and reopen the application without losing any task data.
- **Customizable**: Users can modify task descriptions, categories, and priorities, allowing for flexible task management.
- **Productivity Boost**: Helps users stay on top of their tasks and ensures that tasks are completed on time by providing features like due dates and completion tracking.

### Use Cases:
- **Personal Task Management**: Individuals can use the system to manage personal to-do lists, set deadlines, and track progress.
- **Project Management**: Small project teams can use the system to manage tasks and track project deadlines and responsibilities.
- **Task Prioritization**: Helps users prioritize tasks based on importance or urgency, ensuring the most important tasks are addressed first.

## Future Enhancements
- **Graphical User Interface (GUI)**: Transition from a console-based application to a GUI-based one for better user interaction and experience. A framework like Qt or SFML could be used.
- **Task Filtering and Sorting**: Add features for filtering and sorting tasks by different parameters, such as priority or due date.
- **Task Reminders**: Implement a reminder system that alerts the user when a task's due date is approaching.
- **Task Categories Management**: Allow users to manage predefined categories, or add/remove categories dynamically.
- **Database Integration**: Replace text file storage with a database (e.g., SQLite) for better scalability and data handling.
- **Multi-user Support**: Extend the system to support multiple users, allowing for collaborative task management.
- **Mobile Version**: Develop a mobile version of the task manager for users to manage their tasks on the go.

## How to Run
1. Clone or download the project files.
2. Compile the C++ source code using any standard C++ compiler:
   ```bash
   g++ -o TaskManager main.cpp
