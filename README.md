
# Development 🛠

Environment Setup

`$ git clone https://github.com/Chacha-A-Chacha/GroffyNews_App`

`$ cd News-Web-App/`

### Why use virtualenv?
We use virtualenv to create an isolated environment for your Python project. 
This means that each project can have its own dependencies regardless of what dependencies every other project has.

First, run this command on your command prompt or terminal:

`$ pip install virtualenv`

Second, do the following:

`$ virtualenv “name of virtual environment”`

### Activating the virtual environment

Now go to your terminal or command prompt. Go to the directory that contains the file called activate. 
The file called activate is found inside a folder called Scripts for Windows and bin for OS X and Linux.Activate the environment everytime you open the project

For OS X and Linux Environment:
`$ source /home/GroffyNews_App/“name of virtual environment”/bin/activate`

    The git checkout command lets you navigate between the branches created by git branch . 
    Checking out a branch updates the files in the working directory to match the version stored in that branch, and it tells Git to record all new commits on that branch

`$ git checkout dev`

For Windows Environment:
`“name of virtual environment”\Scripts\activate`

Install requirements

`$ pip install -r requirements.txt`

That's it. You're all Set!

To run the server:

`$ python manage.py runserver`

Open your desired browser and head over to [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

To exit the environment

`$ deactivate `

