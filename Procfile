release: python manage.py migrate --noinput && python manage.py collectstatic --noinput
web: gunicorn nextlevelapi.wsgi --log-file -