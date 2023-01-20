# DjengoAuth
its REST API with jwt token 
Django follows the MVT design pattern (Model View Template).

Model - The data you want to present, usually data from a database.
View - A request handler that returns the relevant template and content - based on the request from the user.
Template - A text file (like an HTML file) containing the layout of the web page, with logic on how to display the data.

Requirements:

python --version
pip --version

Create Virtual Environment: py -m venv app
activate the environment: app\Scripts\activate.bat
Install Django : py -m pip install Django
Check Django Version : django-admin --version
Start project : django-admin startproject myapp
Run the Django Project : py manage.py runserver
if show migration Run : python manage.py migrate
