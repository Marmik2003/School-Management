web: gunicorn config.wsgi --log-file -
worker_and_beat: celery -A config worker -l INFO
