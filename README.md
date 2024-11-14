# Ekroop's Task Management Tool Project

## Project Overview
Ekroop's Task Management Tool is a full-stack web application designed for effective task management. The tool provides users with a streamlined interface to manage tasks through creation, editing, filtering, and deletion functionalities. Users can set task priorities, sort by creation date or priority, and update statuses (Pending, In Progress, Completed). The project emphasizes RESTful API design, modular routing, middleware integration, and responsive UI components.

## Features
- **Task Creation**: Add new tasks with a title, description, priority, status, and due date.
- **Task Editing**: Modify existing tasks directly from the task display page.
- **Task Filtering and Sorting**: Filter tasks by status (Pending, In Progress, Completed) and sort by creation date or priority.
- **Task Deletion**: Delete tasks with a confirmation prompt.
- **UI Design**: Clean, responsive interface with interactive elements for a smooth user experience.
- **Notifications**: Alerts and prompts for task updates, filtering success, and task deletions.

## Project Structure
ekroops-task-management-tool-project/
├── models/
│   └── Task.js                   # Task schema and model
├── node_modules/                 # Dependencies
├── public/
│   ├── task_creation.html        # Task creation page
│   ├── task_display.html         # Task display and editing page
├── routes/
│   └── taskRoutes.js             # API endpoints for task operations
├── .env                          # Environment variables (excluded from submission)
├── .gitignore                    # Specifies files to exclude from Git tracking
├── package-lock.json             # Ensures consistent dependencies
├── package.json                  # Project metadata and dependencies
└── server.js                     # Main server setup with Node.js and Express

## Setup Instructions
To set up and run the project locally, follow these steps:
### Make sure you are in the right Project Directory:
If you are not in the right Project Directory, which should be ekroops-task-management-tool-project, then you need to run the following command: cd ekroops-task-management-tool-project
### Clone the Repository:
Clone the Repository, by running the following command: git clone https://github.com/N01632322/ekroops-task-management-tool-project
### Install all of the Dependencies:
If you have to do so, you have to install all of the dependencies, which includes the "node_modules" folder that contains all of the contents, by running the following command: npm install
### Set Up Environment Variables:
If you need to do so, create a .env file in the project root to configure necessary variables like PORT for server setup (database configurations should be skipped as per Project Phase 2 Instructions). If the .env file is there already in the project, then you do not have to follow this instruction at all.
### Start the server:
To start the server, run the following command: node server.js
### Access the Application:
Open a tab on your browser and navigate to http://localhost:5000 (which is the specified port in the server.js file) to start using the Task Management Tool Application by managing the tasks, such as creating, reading, updating, and deleting the tasks, and other sorts of things that is available to do on the Task Management Tool Application.
