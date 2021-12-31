This Todolist Project is built in Django Framework using Python.

As the basic step, created a 'virtual environment' with a name (here todoenv). 
Installed the latest versions of Django and python in that environment.

Then a python project named 'todo' and its curresponding application named 'todolist' created
using the commands 'django-admin startproject todo' and 'python manage.py startapp todolist' respectively.

Then along with the existing files and folders in django framework, folder like 'static' made to store all the static files like images.
Sameway, extra files like forms.py and urls.py created to support the proper functionality of the project.
Inline css is used only for giving the background image. For the rest of the styles, Tailwind and Bootstap is used.

Django provides  default SQLite database which is used in this project to create a model where all the todolist can be stored.
Every item in the list will have a text field to store the content and a boolean field to represent whether the todo item has been completed or not by the user. 

This project can be run by :
1. Navigating to the exact location of this project folder in the terminal (Anaconda Prompt).
2. Activate the virtual environment created (todoenv).
3.Type the command to run the project:
		python manage.py runserver
4.Then type the address given ( http://127.0.0.1:8000/) as result at the addressbar of your browser (Google Chrome, Firefox etc.) 
to view your resulting website.
