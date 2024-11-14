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
### Clone the Repository:
git clone https://github.com/N01632322/ekroops-task-management-tool-project.git
cd ekroops-task-management-tool-project
### Install all of the Dependencies:
If you have to do so, you have to install all of the dependencies, which includes the "node_modules" folder that contains all of the contents, using the following command: npm install
### Set Up Environment Variables:
If you need to do so, create a .env file in the project root to configure necessary variables like PORT for server setup (database configurations should be skipped as per Phase 2 instructions). If the .env file is there already, then you do not have to follow this instruction at all.
### Start the server:
Start the server, using the following command: node server.js
