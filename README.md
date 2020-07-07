# DS
Med Cabinet - Data and Machine Learning Engineers

Here we created an herokuapp that can predict strains based on the effects and type of medicinal marijuana.


# Dataset

# Move CSV data to database to create an API
# On Windows

set FLASK_APP=app
flask db init
flask db migrate
flask db upgrade

# Documentation
https://flask-migrate.readthedocs.io/en/latest/

# Mac
FLASK_APP=app
flask db init
flask db migrate
flask db upgrade

# Deploy to heroku
Use Database URI 
example DATABASEURI = 'sqlite:///app.db'
Heroku run bash 
Heroku Config
DATABASE_URL = 'sqlite:///app.db'


