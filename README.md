[![Python Version](https://img.shields.io/badge/python-3.6-brightgreen.svg)](https://python.org)
[![Django Version](https://img.shields.io/badge/django-3.0-brightgreen.svg)](https://djangoproject.com)


## Running the Project Locally

First, clone the repository to your local machine:

```bash
git clone https://github.com/mohammed-muzzammil/Thescholars
```

Create Virtual Env and Install the requirements:

```bash
cd Thescholars
(If on Windows)
cd env
cd Scripts
activate
(then go back to Thescholars Directory)
cd\
pip install -r requirements.txt
```

Create the database and run the development server:

```bash
cd Thescholars
python manage.py migrate
python manage.py loaddata datas.json
python manage.py runserver
```

The project will be available at http://127.0.0.1:8000, Login using::

**Teacher**

username: `teacher`
password: `teacher`

**Student**

username: `student`
password: `student`


## License

The source code is released under the [MIT License](https://github.com/sibtc/django-multiple-user-types-example/blob/master/LICENSE).
