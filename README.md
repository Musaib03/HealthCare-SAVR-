# Health Care
Health Care is a diagnostic management project developed in Django. Admin can add doctors, add services, and add gallery pictures. Users can see doctors' profiles, make appointments, and contact Health Care through email.

# Clone the Repository

git clone https://github.com/devmahmud/Heart-Care-Django.git

# Technologies Used
Backend
Django
SQLite 
Frontend
HTML
CSS
JavaScript
Bootstrap

# Installation
pip (Python package installer)
virtualenv 

# Steps

Clone the repository:

git clone https://github.com/your-username/campus-security-management.git
cd CampusSecurity

Create and activate a virtual environment:

python3 -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
Install the required packages:

pip install -r requirements.txt

Apply the migrations:
python manage.py makemigraions
python manage.py migrate

Create a superuser:
python manage.py createsuperuser

Run the development server:
python manage.py runserver

Open your browser and navigate to http://127.0.0.1:8000/ to access the application.

# Usage
Admin Panel
Access the admin panel at http://127.0.0.1:8000/admin/ using the superuser credentials.

For email sending functionality, fill up the information in your project settings:
makefile
Copy code
EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'
EMAIL_HOST = 'smtp.gmail.com'
EMAIL_PORT = 587
EMAIL_USE_TLS = True
EMAIL_HOST_USER = 'your email'
EMAIL_HOST_PASSWORD = 'your email password'
To run the program on the local server, use the following command:
Copy code
python manage.py runserver
Then go to http://127.0.0.1:8000 in your browser.


# Developer

Musaib Maqbool Wani




