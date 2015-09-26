## What is this repository for? ##

Various web apps for various events which will take place during felicity buzz2k15.

## How do I get set up? ##

**Install the requirements:**

1. virtualenv --no-site-packages --distribute venv
2. source venv/bin/activate
3. pip install -r requirements.txt

**Entering the virtual environment**

1. source venv/bin/activate

**Create/Sync the database:**

1. ./manage.py makemigrations 
2. ./manage.py migrate

**Starting the server:**

1. ./manage.py runserver [host:port]

**Exiting the virtual environment**

1. deactivate