web: daphne project.asgi:channel_layer --port $PORT --bind 0.0.0.0 -v2
worker: python manage.py runworker -v2
celery: celery -A project.settings worker -l info
