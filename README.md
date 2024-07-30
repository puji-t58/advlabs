# advlabs
# Flask Password Checker Assignment

This project implements a sign-up and sign-in interface using Flask and SQLite, with a password checker feature. 

## Setup Instructions

### Prerequisites
- Python 3.x
- pip (Python package installer)
- Virtual environment setup

### Installation

1. **Clone the Repository**
   ```sh
   git clone <repository_url>
   cd <repository_directory>
Create a Virtual Environment

python -m venv venv

Activate the Virtual Environment
.\venv\Scripts\activate

On macOS and Linux:
source venv/bin/activate

Install Dependencies:
pip install -r requirements.txt

Configuration
Setup Environment Variables
Create a .env file in the root directory of the project and add the following environment variables:

FLASK_APP=app.py
FLASK_ENV=development
SECRET_KEY=your_secret_key_here


Initialize the Database:
flask shell
>>> from app import db
>>> db.create_all()
>>> exit()

Running the Application
Start the Flask Application:

python app.py

Access the Application
Open your browser and navigate to http://127.0.0.1:5000.

Project Structure
app.py: Main application file containing routes and application logic.
templates/: Directory containing HTML templates.
index.html
signup.html
login.html
secretPage.html
thankyou.html
Password Checker Feature
Password Requirements
The password checker enforces the following rules:

At least 8 characters long
Contains both uppercase and lowercase letters
Includes at least one numeric digit
Contains at least one special character (e.g., @, #, $)
Implementation Details
Form Validation:

Sign-up form ensures password meets the required criteria.
Provides feedback to the user if the password is not strong enough.
Password Hashing:

Passwords are hashed before storing them in the database for security purposes.
Additional Information
Flask Documentation: Flask Official Documentation
SQLite Documentation: SQLite Official Documentation 


Lab08 React To-Do List Application
Project Overview
This project extends a basic React To-Do List application with several additional features. The application allows users to manage tasks, including adding, editing, deleting, and filtering tasks based on their completion status and priority levels. The design incorporates a background image, a header with a logo, and a footer with contact information for enhanced aesthetics.

Features
To-Do List Management
Add New Tasks:

Users can input new tasks and set their priority levels (High, Medium, Low).
Tasks are added to the list with the selected priority.
Edit Tasks:

Users can click the "Edit" button to modify existing tasks.
The task text can be updated and saved.
Delete Tasks:

Users can remove tasks from the list by clicking the "Delete" button.
Toggle Task Completion:

Tasks can be marked as completed or incomplete by clicking on the task.
Filter Tasks:

Users can filter tasks by All, Completed, or Incomplete using filter buttons.
Visual Enhancements
Background Image:

The application features a background image to improve visual appeal.
Header and Footer:

The header includes a logo and the application title.
The footer contains contact information and a copyright notice.
Project Structure
java
Copy code
todofinal/
│
├── public/
│   ├── index.html
│
├── src/
│   ├── App.js
│   ├── App.css
│
├── package.json
├── package-lock.json
Prerequisites
Node.js
npm (Node Package Manager)
Installation and Setup
Navigate to the project directory:

bash
Copy code
cd ~/Desktop/todofinal
Install project dependencies:

bash
Copy code
npm install
Start the development server:

bash
Copy code
npm start
Open your browser and navigate to:

arduino
Copy code
http://localhost:3000
Usage
Add New Task: Enter a new task in the input field, select a priority level, and click "Add Task."
Edit Task: Click the "Edit" button next to a task to enter editing mode. Update the task text and click "Save."
Delete Task: Click the "Delete" button next to a task to remove it from the list.
Toggle Completion: Click on a task to mark it as completed or incomplete.
Filter Tasks: Use the filter buttons to view all tasks, only completed tasks, or only incomplete tasks.
THank you 



