FROM python:3.10-bullseye

WORKDIR /app

RUN pip install --upgrade pip
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

COPY . .
