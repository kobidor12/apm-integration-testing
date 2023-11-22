FROM python:3.10.13

RUN pip install -q -U Flask blinker gunicorn

RUN mkdir -p /app
COPY app.py /app

WORKDIR /app
