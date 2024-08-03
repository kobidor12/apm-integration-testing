FROM python:3.13.0b4

RUN pip install -q -U Flask blinker gunicorn

RUN mkdir -p /app
COPY app.py /app

WORKDIR /app
