# Install

```shell
$ cd ~/Projects
$ git clone git@github.com:griend/kngd.git
$ cd kngd
$ python3 -m venv .venv
$ source .venv/bin/activate
(.venv) $ pip3 install --upgrade pip
(.venv) $ pip3 install --upgrade django
(.venv) $ cd ~/Projects
(.venv) $ django-admin startproject kingdom kngd
```

```shell
$ cd ~/Projects/kndm 
$ source .venv/bin/activate
(.venv) $ python3 manage.py runserver
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).

You have 18 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.
Run 'python manage.py migrate' to apply them.
April 25, 2022 - 12:47:42
Django version 4.0.4, using settings 'kingdom.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.
```
