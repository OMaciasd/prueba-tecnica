FROM python:3.7

RUN pip install -U pip

WORKDIR /usr/src/app

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .
