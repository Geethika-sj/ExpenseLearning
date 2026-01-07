# ExpenseLearning
Expense Learning is a web-based application built using Django that helps users track, manage, and analyze their personal expenses.


Features

Django built-in Admin Dashboard

Secure User Authentication system

Expense Management for learning and practice purposes

Well-organized and easy-to-understand project structure

Requirements

Python 3 or higher

Django framework

 How to Run the Project

Follow the steps below to set up and run the project locally.

Step 1: Download the Project

Clone the repository from GitHub or download the ZIP file and extract it to your system.

Step 2: Create a Virtual Environment
python -m venv myenv

Step 3: Activate the Virtual Environment

myenv\Scripts\activate

Step 4: Install Django
pip install django

Step 5: Apply Database Migrations
python manage.py migrate

Step 6: Start the Development Server
python manage.py runserver


Open your web browser and go to:

http://127.0.0.1:8000/

Creating a Superuser (Admin Access)

To access the Django admin panel, create a superuser using the command below:

python manage.py createsuperuser


Provide the required details:

Username

Email address

Password

After successful creation, open:

http://127.0.0.1:8000/admin/


Log in using the superuser credentials.
