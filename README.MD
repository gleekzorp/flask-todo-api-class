# Python Flask TODO Api

> Python Flask backend app for keeping track of todos.  It uses a flask sqlite database along with flask-marshmallow for object serialization/deserialization.  You can Post, Get, Patch, and Delete todos through flask routes.

> Create Database
- Make sure your in your pipenv shell and hop into a python repl and run these commands.  After you run these commands you will see an app.sqlite file.
```
$ pipenv shell
$ python
>>> from app import db
>>> db.create_all()
```