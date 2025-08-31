release: python manage.py migrate && python manage.py collectstatic --noinput

web: gunicorn TatGhor.wsgi:application --log-file - 

