# Warbler
Welcome to Warbler, my twitter clone! Warbler has similar features to Twitter, with a focus on backend development and user authentication. The MVP for this project isto extend a somewhat-functioning Twitter clone. It is intended for practice reading and understanding an existing application, as well as fixing bugs in it, writing tests for it, and extending it with new features.

- Implemented logout route
- Added additional fields to the user profile (location, bio, the header image)
- Fixed user cards (show bio for users)
- Added a form that allows users to edit their profile
- Fixed the homepage so that the most recent 100 warblers from the users that the logged in user followers, rather than all of them,  are shown to the user upon login 
- Implemented authentication features
- Implemented like features
- Wrote and implemented unit tests


To run this application in development mode:
1. Create the Python virtual environment:

  :class: console

  $ python3 -m venv venv
  $ source venv/bin/activate
  (venv) $ pip install -r requirements.txt

Important Note:
If you are using Python 3.8 instead of 3.7, then you will have issues with installing some of the packages in the requirements.txt file into your virtual environment.
For Python 3.8 students, we recommend deleting pyscopg2-binary from the requirements.txt file, and using pip install pyscopg2-binary in the terminal in order to successfully install this package.
Set up the database:

(venv) $ createdb warbler
(venv) $ python seed.py
Start the server:

(venv) $ flask run


  

