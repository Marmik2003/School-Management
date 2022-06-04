web: gunicorn config.wsgi --log-file -
worker_and_beat: REMAP_SIGTERM=SIGQUIT celery -A config.celery worker -B --loglevel=info
