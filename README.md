# Hello World Django App

This is a simple Django web application that serves a JSON response with the message `{"Message": "Hello World!"}` at the endpoint `/WEEK5/`.

## Project Overview
The application is built using Django 5.2 and Python 3.12.3. It includes a single route that returns a JSON response when accessed via a browser or HTTP client.

## Installation Instructions
Follow these steps to set up and run the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/L30088991/week5-hello-world.git
   cd hello_world
   ```

2. **Create and Activate a Virtual Environment**:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install django==5.2
   ```

4. **Navigate to the Project Directory**:
   ```bash
   cd hello_world
   ```

5. **Run the Development Server**:
   ```bash
   python manage.py runserver
   ```
   The server will start at `http://127.0.0.1:8000/`.

## Accessing the Hello World JSON Response
- Open a web browser or use an HTTP client (e.g., curl, Postman).
- Navigate to:
  ```
  http://127.0.0.1:8000/WEEK5/
  ```
- You should see the JSON response:
  ```json
  {"Message": "Hello World!"}
  ```

## Project Structure
- `hello_world/`: Contains Django project settings and URL configurations.
- `polls/`: The Django app containing the view and URL for the Hello World endpoint.
- `manage.py`: Django's command-line utility.
- `db.sqlite3`: SQLite database file (created automatically).
- `venv/`: Virtual environment directory (not included in the repository).

## Notes
- Ensure Python 3.12.3 and Django 5.2 are installed in your virtual environment.
- The `.gitignore` file excludes unnecessary files like `venv/` and `__pycache__/`.
- Do not upload zip files to the repository; all necessary files are included directly.
