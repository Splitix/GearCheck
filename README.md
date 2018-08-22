# GearCheck
A World of Warcraft web app that checks a characters gear for missing gems and enchants

## Setup/Install

### Prerequirements
+ Python 2
+ Virtual Environment
+ Pip

### Setting up
+ Clone the project to your local machine. 
+ Create a virtual environment
	+ Using terminal type the following command `virtualenv .venv`
	+ enter the virtual environment you just created `source .venv/bin/activate`
+ Install the python requirements using the command `pip install -r requirements.txt`
+ Setup the export variable `export FLASK_APP=run.py`
+ Start the webserver `flask run`
+ Open a browser and enter the address `localhost:5000/`

### Closing and Exiting
+ Turn the web server off by using pressing ctrl + c
+ Leave the virtual environment by typing `deactivate`
