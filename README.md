Set up a virtual environment to use for our application:

$ python3 -m venv env
$ source env/bin/activate

to install packages using pip according to the requirements.txt file from a local directory

$ python3 -m pip install -r ./requirements.txt

running in VS Code 

$ python3 -m pip install -r ./requirements.txt --user

to run

$ python3 app.py

Release virtual environment

$ deactivate