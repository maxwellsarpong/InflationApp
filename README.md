# InflationApp
A Django machine learning project to predict inflation.

## Getting Started

Setup project environment with [virtualenv](https://virtualenv.pypa.io) and [pip](https://pip.pypa.io).

```bash
$ virtualenv project-env
$ source project-env/bin/activate
$ pip install -r https://raw.githubusercontent.com/maxwellsarpong/InflationApp/master/requirements.txt

# You may want to change the name `projectname`.
$ django-admin startproject --template https://github.com/maxwellsarpong/InflationApp/archive/master.zip projectname

$ cd projectname/
$ cp settings_custom.py.edit settings_custom.py
$ python manage.py migrate
$ python manage.py runserver
```

## Features

* Basic Django scaffolding (commands, templatetags, statics, media files, etc).
* Split settings in two files. `settings_custom.py` for specific environment settings (localhost, production, etc). `projectname/settings.py` for core settings.
* Simple logging setup ready for production envs.

## Contributing

I love contributions, so please feel free to fix bugs, improve things, provide documentation. Just send a pull request.

      OR
      
## Continuing with the project
```
$ git clone https://github.com/maxwellsarpong/InflationApp.git
$ cd InflationApp
$ install contents of requirements.txt
$ Open your xampp
$ create database cpi
$ run python manage.py migrate
$ next run python manage.py runserver to run on localhost
```
