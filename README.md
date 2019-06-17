# FlaskQuestionPose
This is a simple flask site to ask a user questions and log their responses to a SQL database.

To start, clone this repository. Enter the directory the repository is in, and do the following in the command line:

python
>>from main import db

>>db.create_all()

>>exit()

now, in the command line:

python main.py

and you should be able to see the page running on your local host. To access the database, the .db file will be in the same directory as main.py.
