# Django Room Management App

Welcome to the Django Room Management App! This web application allows users to manage rooms with user authentication and CRUD (Create, Read, Update, Delete) functionality.

## Table of Contents

-   [Key Features](#key-features)
-   [Technologies Used](#technologies-used)
-   [How to Use](#how-to-use)
-   [Project Structure](#project-structure)
-   [Contributing](#contributing)
-   [License](#license)

## Key Features

-   **User Authentication:** Secure user registration and login system.
-   **Room CRUD Operations:** Create, view, update, and delete rooms.
-   **User Profile:** Access a personalized user profile with room-related information.
-   **Responsive Design:** Ensures a seamless experience across various devices.

## Technologies Used

-   **Django:** A high-level Python web framework.
-   **SQLite:** A lightweight and efficient database.
-   **HTML, CSS:** For frontend development and styling.

### Cloning the repository

--> Clone the repository using the command below :

```bash
git clone https://github.com/Abhijeet-droid-AI/django-project

```

--> Move into the directory where we have the project files :

```bash
cd DjangoUserPortal

```

--> Create a virtual environment :

```bash
# Let's install virtualenv first
pip install virtualenv

# Then we create our virtual environment
virtualenv envname

```

--> Activate the virtual environment :

```bash
source envname\Scripts\activate

```

--> Install the requirements :

```bash
pip install -r requirements.txt

```

#

### Running the App

--> To run the App, we use :

```bash
python manage.py runserver

```

> ⚠ Then, the development server will be started at http://127.0.0.1:8000/

#

## Project Structure

- `venv`: Virtual environment directory.
  - `...`: Virtual environment files and directories.

- `django_room_management`: Django project directory.
  - `base`: Django app handling room-related functionalities.
  - `templates`: HTML templates for rendering pages.
  - `static`: CSS styles and other static assets.
    - `main.css`: Main stylesheet for consistent styling.
  - `manage.py`: Django project management script.
  - `...`: Other Django project files.

- `requirements.txt`: List of Python dependencies for the project.

- `README.md`: Project overview and documentation.
