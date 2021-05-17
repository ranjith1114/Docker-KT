FROM ubuntu:latest

RUN apt-get update
RUN apt-get install -y python3 python3-pip
RUN pip install flask

WORKDIR /app
COPY . /app

CMD [ "app.py", "0.0.0.0:5000" ]
