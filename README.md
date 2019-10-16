# AAACI
Alexa Adelphi Academic Calendar Interface

## Setup for Local Development

#### Setup virtual environment
```console
foo@barr:~/aaaci$ virtualenv -p python3.7 venv    # create virtualenv
foo@barr:~/aaaci$ source venv/bin/activate        # activate virtualenv
```

#### Install required packages
```console
(venv) foo@barr:~/aaaci$ pip install -r requirements.txt
```

#### Run development server
```console
(venv) foo@barr:~/aaaci$ python manage.py runserver
```
Your local development server will be running on http://localhost:8000/
