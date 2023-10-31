# ToDoList
Full-Stack Development mini project
This is a simple website to manage you todo lists and items in each list
This project is developed using Django framwork with sqllite3 database

# Instructions on how to set up and run this application on your system is as follows:
The backend code is stored in the **todo_app** directory and frontend code is in the **templates** directory

# Django To-Do Lists Application

This is a Django-based to-do list application that allows users to manage their tasks using the todo lists, with few animations

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x: You can download and install Python from [python.org](https://www.python.org/downloads/).
- Django: You can install Django using pip with the command `pip install django`.
- Virtual Environment (optional): It's recommended to set up a virtual environment for your project.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/ankur19986/ToDoList
   ```

2. Navigate to the project directory:

   ```bash
   cd ToDoList
   ```

3. Create a virtual environment (optional):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use venv\Scripts\activate
   ```

4. Install project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Apply database migrations:

   ```bash
   python manage.py migrate
   ```

6. Create a superuser to access the Django admin panel:

   ```bash
   python manage.py createsuperuser
   ```

7. Start the development server:

   ```bash
   python manage.py runserver
   ```

Your Django application should now be up and running locally.

## Usage

- Access the application in your web browser at http://127.0.0.1:8000/  --> You can use the application to manage your todo lists
- Log in with the superuser credentials you created.
- You can manage your to-do lists and tasks through the web interface.

# Screenshots

Home page - It will display all the todo lists, click on the list to see the items and due dates
![image](https://github.com/ankur19986/ToDoList/assets/149323067/224d4552-9c32-4943-ab20-e68ddf0ee2ad)

Create List page
![image](https://github.com/ankur19986/ToDoList/assets/149323067/f52bca77-eda3-49a0-b498-baf7cb191480)

Create Item Page
![image](https://github.com/ankur19986/ToDoList/assets/149323067/70463500-cd3d-4265-8d80-b55326cae047)

Items page - The items with due date will be displayed here and you can create new items, click to update or delete/mark items done
You can even delete the complete list to mark all items as done
![image](https://github.com/ankur19986/ToDoList/assets/149323067/7e424aaf-23fc-48c0-8bf3-bda19c6f1f66)

Update page
![image](https://github.com/ankur19986/ToDoList/assets/149323067/4de59502-92ac-41b1-b4ba-5d133e42507d)

Delete Item page
![image](https://github.com/ankur19986/ToDoList/assets/149323067/6fa5a800-48cb-4974-adb8-ddc28d60befe)

Delete List page
![image](https://github.com/ankur19986/ToDoList/assets/149323067/cbcd6944-e947-4a4e-b681-486f1372c140)

Additional animation applied to the website and the functionalities are is recorded in below video
https://github.com/ankur19986/ToDoList/assets/149323067/4184bc19-f258-4414-9986-c0def376d6e9

* the header is used to navigate back to home page
