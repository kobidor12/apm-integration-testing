FROM python:3.14.0a3

RUN pip install -q -U Flask blinker gunicorn

RUN mkdir -p /app
COPY app.py /app

WORKDIR /app
