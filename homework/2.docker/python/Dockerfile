FROM python:3.8-slim-buster as builder

RUN mkdir /app

COPY . /app

WORKDIR /app

RUN pip3 install -r requirements.txt

EXPOSE 8080

CMD [ "python3", "app.py" ]
