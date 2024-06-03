# haskell-task-manager
A command-line Task Manager application that allows users to manage their daily tasks. This application supports adding, listing, updating, and deleting tasks. Each task should have a description, a due date, and a status indicating whether it is pending or completed.

Features and Requirements
1. Task Data Structure
Task ID: A unique identifier for each task.
Description: A short description of the task.
Due Date: The due date for the task.
Status: The status of the task (pending or completed).
2. Core Features
Add Task: Allow users to add a new task with a description, due date, and default status as pending.
List Tasks: Display all tasks with their details. Provide options to filter tasks based on status (pending/completed).
Update Task: Enable users to update the description, due date, or status of an existing task.
Delete Task: Allow users to delete a task by its ID.
3. Command-Line Interface (CLI)
Menu: Display a menu with options for each core feature.
User Input: Handle user input for selecting menu options and providing task details.
Validation: Validate user input to ensure it is correct (e.g., due date format, non-empty descriptions).
4. Data Persistence
File Storage: Save tasks to a file so that they persist between program runs.
Serialization/Deserialization: Implement functionality to read from and write to a file.
5. Advanced Features (Optional)
Search Tasks: Add a feature to search tasks by keyword in the description.
Sort Tasks: Implement sorting of tasks by due date or status.
Concurrency (Optional): Explore Haskell’s concurrency features by allowing multiple tasks to be processed simultaneously (e.g., batch updating statuses).
Technical Requirements
Haskell Basics: Understand Haskell syntax, types, and basic functional programming concepts.
Data Types: Define custom data types for tasks.
I/O Operations: Implement reading from and writing to files.
Error Handling: Handle potential errors, such as invalid user input or file I/O issues.
List Manipulation: Use Haskell’s powerful list functions to manipulate tasks.
Modules: Organize code using Haskell modules for better structure and maintainability.
Project Steps
Setup: Install Haskell and set up your development environment.
Task Data Structure: Define the Task data type and necessary typeclasses (e.g., Show, Eq).
Basic CLI: Implement a simple CLI that prints a menu and handles user input.
Add Task: Write functions to add a task, ensuring the data is validated and stored in a list.
List Tasks: Implement the function to display tasks. Add filtering options.
Update Task: Write functions to update task details, ensuring tasks can be located by ID.
Delete Task: Implement task deletion, allowing users to remove tasks by ID.
File Storage: Implement saving tasks to a file and loading tasks from a file at startup.
Advanced Features: (Optional) Implement search, sort, and concurrency features.
Testing: Test all functionalities thoroughly to ensure they work correctly and handle edge cases.
