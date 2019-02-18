# wallapop-server

# Guides

- Boilerplate Flask https://medium.freecodecamp.org/structuring-a-flask-restplus-web-service-for-production-builds-c2ec676de563

# JWT Authentication

- Usamos JWT tokens para atenticar a los usuarios

## Build Setup

```bash
# crear base de dados en mysql server
CREATE DATABASE proyecto-software

# Create migration folder 
python manage.py db init

# Create a migration script from the detected changes in the model 
python manage.py db migrate --message 'initial database migration'

#Apply the migration script to the database
python manage.py db upgrade

```

## Build Setup

```bash
# Run
python manage.py run

#Test
python manage.py test

```


