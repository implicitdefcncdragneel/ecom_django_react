release: python manage.py migrate

web: gunicorn ecom.wsgi --log-file -

worker: python manage.py rqworker default