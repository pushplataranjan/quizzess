web: gunicorn config.wsgi:application
worker: celery worker --app=quizzess.taskapp --loglevel=info
