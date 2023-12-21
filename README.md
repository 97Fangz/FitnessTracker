# Pushup Tracker Website

This is a CRUD (Create, Read, Update, Delete) web application built using Flask and Python. It allows users to sign up, log in, and manage their accounts. Users can track their daily pushups and add comments for each session.

## Features

- User Authentication: Users can sign up for an account or log in if they already have one. Passwords are securely hashed and stored.
  
- Pushup Tracking: Once logged in, users can track their daily pushup count. They have the ability to add, update, and delete their pushup records.

- Comments: Users can add comments to each pushup session, providing insights, notes, or thoughts about their workout.

## Technologies Used

- Flask
- Python
- SQLAlchemy (for database interaction)
- HTML/CSS (for frontend)
- Bootstrap (for UI components)

## Installation

1. Clone this repository.

   ```bash
   git clone https://github.com/yourusername/pushup-tracker.git
   ```

2. Create a virtual environment.

   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment.

   On Windows:

   ```bash
   venv\Scripts\activate
   ```

   On macOS and Linux:

   ```bash
   source venv/bin/activate
   ```

4. Install dependencies.

   ```bash
   pip install -r requirements.txt
   ```

5. Set up the database.

   ```bash
   flask db init
   flask db migrate
   flask db upgrade
   ```

6. Run the application.

   ```bash
   flask run
   ```

   Access the application in your browser at `http://127.0.0.1:5000`
