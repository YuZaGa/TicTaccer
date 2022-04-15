release: python manage.py migrate
web: daphne tic_tac_toe.asgi:application --port $PORT --bind 0.0.0.0 -v2