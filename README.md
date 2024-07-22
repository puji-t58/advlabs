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


