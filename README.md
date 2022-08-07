# FLASK125
1) latest version of python installed 2) pip 3) Virtual environment
In python3.8 virtual environment is preinstalled. And you can directly use python3.8 -m venv venv to create a virtual environment in windows.
python -m venv venv
This -m tells python the name of the module we want to use to perform this action
we want to create a virtual environment, which we will call venv and we want this virtual environment to have Python3.8 by default.
Flask(__name__), the constructor of this class Flask that we imported takes the name of the current module, stored in __name__ as an argument and the variable app is now a Flask object.
The PUT Method - PUT is used to send data to a server to create / update a resource. The basic difference between PUT and POST is that a POST request is when you can create multiple copies of the same resource. A PUT request, on the other hand means that you want to create only one copy of the resource, i.e. Signing Up a unique user. The DELETE Method - DELETE is used to delete a resource. The default method used by flask is GET.
