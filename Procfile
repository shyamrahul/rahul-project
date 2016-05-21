web:python flaskCheck.py runserver
web: gunicorn flaskCheck.wsgi --log-file -
heroku ps:scale web=1