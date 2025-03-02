FROM ubuntu:latest

WORKDIR /app

COPY . /app

RUN apt update && apt install python3 -y python3-pip -y 


CMD ["python3", "app.py"]
