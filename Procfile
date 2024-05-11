web: ./bin/fixie-wrench 8080:worldclockapi.com:80 & python -m speed_tst.py
worker: python -m speed_tst.py

web: gunicorn speed_tst.wsgi

