# django-restful-api 
Is a simple game API application that handles CRUD methods.

## Usage

Able to create new games with the following categories:

    name
    game_category
    release_date
    played
- View all existing games/ View one by ID
- Delete an existing game by ID
- Update an existing game by ID

## Resources
- [Python 3.6](https://docs.python.org/3/)
- [Django REST Framework](http://www.django-rest-framework.org/#installation)
- [Django](https://docs.djangoproject.com/en/1.11/)
## Installation
Clone this repository and navigate to the directory

    $ git clone https://github.com/Mercy-Muchai/django-restful-apis.git
    
Install Python 3.6.4 from [here](https://docs.python.org/3/installing/index.html)

Create a virtual environment [here](http://docs.python-guide.org/en/latest/dev/virtualenvs/)

Download and install [SQLite](http://www.sqlite.org/)

Download [DB Browser for SQLite](http://sqlitebrowser.org/) for easy use of the database

Create a Database with the name you desire e.g games

Install the necessary packages

    $ pip install -r requirements.txt
    
### Start the app

    $ python manage.py runserver 0.0.0.0:6000
On the browser, navigate to route: http://0.0.0.0:8000/games/ to view all games
