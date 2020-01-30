web: gunicorn django_email_example.wsgi --log-file -
worker: DJANGO_READ_DOT_ENV_FILE=1 celery -A django_email_example worker -l info