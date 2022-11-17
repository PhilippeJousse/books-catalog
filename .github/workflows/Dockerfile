
FROM docker.io/ubuntu

RUN apt-get update

RUN apt install python3 -y

RUN apt install python3-pip -y

RUN pip install tornado

COPY . /app

WORKDIR /app

CMD python3 /app/src/main.py

EXPOSE 9990
