# hello-world-django-python

Prerequisites

1 - Install Python Code extension
2 - Install a version 3 of Python
3 - Add the python to the PATH variable

Creating a Django Project

1 - Create a folder called hello_django in file system
2 - Create a virtual environment in the new folder. Inside the previously created folder, open a terminal and execute the command:
      python -m venv env
3 - In the same terminal, execute the command:
      code .
4 - In VS Code, open the Command Palette and select the Python: Select Interpreter. 
      (View > Command Palette or (Ctrl+Shift+P)). 
5 - The command presents a list of available interpreters that VS Code can locate automatically from the list, select the virtual environment in your project folder that starts with ./env or .\env
6 - Run Terminal: Create New Integrated Terminal (Ctrl+Shift+`) from the Command Palette, which creates a terminal and automatically activates the virtual environment by running its activation 
    script.
7 - The selected environment appears on the left side of the VS Code status bar, and notice the "(venv)" indicator that tells you that you're using a virtual environment
8 - Install the Django in the virtual environment.
      python -m pip install django

Creating and running a Django APP

1 - To Create a Django project, after Django and Python are installed, run the command:
      django-admin startproject web_project .
2 - To Verify the project in web server:
      python manage.py runserver
3 - Ctrl+click the http://127.0.0.1:8000/ to access the application
4 - Ctrl+C to stop the server (started by python runserver command)
5 - Create a Django APP. This will create the app. Change the code as you want.
      python manage.py startapp hello
6 - To execute the app, run the command:
      python manage.py runserver
