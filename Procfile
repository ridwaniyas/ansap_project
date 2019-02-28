web: gunicorn config.wsgi:application
worker: celery worker --app=ansap_project.taskapp --loglevel=info
