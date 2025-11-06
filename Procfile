release: cd backend && python manage.py collectstatic && python manage.py migrate
web: cd backend && gunicorn devpro.wsgi --log-file -
