# To-Do Application

This is a simple To-Do application built with Django and React. The application allows users to create, read, update, and delete (CRUD) tasks.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- Add new tasks
- View existing tasks
- Update task details
- Delete tasks
- Mark tasks as complete or incomplete

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- Python (version 3.8 or higher)
- Node.js (version 14 or higher)
- npm or yarn
- Django (version 3.0 or higher)
- Django REST framework
- React

## Installation

Follow these steps to get the project up and running on your local machine.

### Backend (Django)

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/todo-application.git
    cd todo-application
    ```

2. Create a virtual environment:
    ```sh
    python -m venv venv
    ```

3. Activate the virtual environment:
    - On Windows:
        ```sh
        venv\Scripts\activate
        ```
    - On macOS and Linux:
        ```sh
        source venv/bin/activate
        ```

4. Install the required Python packages:
    ```sh
    pip install -r requirements.txt
    ```

5. Apply migrations:
    ```sh
    python manage.py migrate
    ```

6. Start the Django development server:
    ```sh
    python manage.py runserver
    ```

### Frontend (React)

1. Navigate to the frontend directory:
    ```sh
    cd frontend
    ```

2. Install the required npm packages:
    ```sh
    npm install
    ```

3. Start the React development server:
    ```sh
    npm start
    ```

The React app will run on `http://localhost:3000` and the Django API will run on `http://localhost:8000`.

## Usage

1. Open your browser and go to `http://localhost:3000`.
2. You can now create, view, update, and delete tasks.

## Project Structure

```plaintext
todo-application/
├── backend/
│   ├── manage.py
│   ├── todo/
│   │   ├── __init__.py
│   │   ├── settings.py
│   │   ├── urls.py
│   │   ├── wsgi.py
│   ├── tasks/
│   │   ├── migrations/
│   │   ├── __init__.py
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── models.py
│   │   ├── serializers.py
│   │   ├── views.py
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── App.js
│   │   ├── index.js
│   ├── package.json
├── requirements.txt
└── README.md
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Acknowledgements

This project was inspired by the tutorial from DigitalOcean. Special thanks to the author for the detailed guide.

[Build a To-Do Application Using Django and React](https://www.digitalocean.com/community/tutorials/build-a-to-do-application-using-django-and-react)



