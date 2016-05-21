web: python flaskCheck.py runserver
web: gunicorn flaskcheck.wsgi --log-file -
heroku ps:scale web=1