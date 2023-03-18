# Tips-and-Tricks

################################################

Create the virtual environment named "env":

> pip install virtualenv

> python -m venv env 

Add the path to the git ignore file (optional):
> echo env/ >> .gitignore

Activate the virtual env:
> .\env\Scripts\activate

################################################

Generate a requirements.txt file:

> pip install pipreqs

> pipreqs /path/to/project

more info related to pipreqs can be found here.

################################################

pip freeze saves all packages in the environment > better for virtual environment of a single project

> pip freeze > requirements.txt

################################################

Install all the packages saved in the requirements.txt file

> pip install -r requirements. txt
