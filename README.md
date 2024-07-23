# AuthTweet Secure

AuthTweet Secure is a Django-based project designed to provide a secure user authentication system along with tweet functionality. The project includes:

- A user authentication system using Django.
- Registration, login, and password reset functionality.
- Tweet functionality that allows users to post and view tweets.



## Setup Instructions
You can run the provided example project on your local machine by following the steps outlined below.

Step 1: Create a Virtual Environment
```bash
python -m venv myenv
```

Step 2: Activate the Virtual Environment

On Windows:
```bash
myenv\Scripts\activate
```
On MacOS/Linux:
```bash
source myenv/bin/activate
```
Step 3: Install Django
```bash
pip install django
```
Step 4: Upgrade pip (optional but recommended)
```bash
pip install --upgrade pip
```
Step 5: Freeze the installed packages
```bash
pip freeze > requirements.txt
```
Step 6: Start a Django Project
```bash
django-admin startproject your-project-name
```
Step 7: Run the Development Server
```bash
python manage.py runserver
```
Step 8: Make Migrations
```bash
python manage.py makemigrations
```
Step 9: Apply Migrations
```bash
python manage.py migrate
```
Step 10: Create a Superuser
```bash
python manage.py createsuperuser
```
