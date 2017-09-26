web: gunicorn config.wsgi:application
worker: celery worker --app=ax.taskapp --loglevel=info
