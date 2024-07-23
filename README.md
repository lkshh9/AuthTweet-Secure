# AuthTweet Secure

AuthTweet Secure is a Django-based project designed to provide a secure user authentication system along with tweet functionality. The project includes:

- A user authentication system using Django.
- Registration, login, and password reset functionality.
- Tweet functionality that allows users to post and view tweets.



## Setup Instructions

```bash
# Step 1: Create a Virtual Environment
python -m venv myenv

# Step 2: Activate the Virtual Environment
# On Windows:
myenv\Scripts\activate
# On MacOS/Linux:
source myenv/bin/activate

# Step 3: Install Django
pip install django

# Step 4: Upgrade pip (optional but recommended)
pip install --upgrade pip

# Step 5: Freeze the installed packages
pip freeze > requirements.txt

# Step 6: Start a Django Project
django-admin startproject your-project-name

# Step 7: Run the Development Server
python manage.py runserver

# Step 8: Make Migrations
python manage.py makemigrations

# Step 9: Apply Migrations
python manage.py migrate

# Step 10: Create a Superuser
python manage.py createsuperuser
