# Clerky
This is the first and most complete toolkit ever for local politicians and clerks.

## Installation
First of all, make a project-directory with this repo as a subdirectory.

### Install requirements
Create a venv first with your favorite venv software. After that run:
``
pip install -r requirements.txt
``
Dont forget to install flask manually on your machine.
``sudo apt-get install python3-flask``

### Export variables
For this, it is recommended to combine all variables export in a file called ``variables``. Place this in the app-folder and run:
```
  export FIREBASE_WEB_API_KEY="Only if you use firebase"
  export MAIL_USERNAME="email"
  export MAIL_PASSWORD="password"
  export MASTER_EMAIL="your@email.com"
  export SITE_BASE_URL="url_of_website"
  export UPLOAD_LOCATION='static'
  export FLASK_APP='__init__.py'
```
And run:
``source variables``


