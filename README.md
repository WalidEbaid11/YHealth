"The method of running the graduation project":

Ensure you have virtualenv installed. You can verify this by running the command:
pip install virtualenv
If it is not installed, please follow these instructions to install it on your system: https://virtualenv.pypa.io/en/ --version 
If it's not installed, you can download and install it from here: https://pypi.org/project/virtualenv/
- Run pip install -r requirements.txt to install dependencies
- Run python manage.py makemigrations
- Run python manage.py migrate
- Run python manage.py runserver
- Navigate to http://127.0.0.1:8000/ in your browser
