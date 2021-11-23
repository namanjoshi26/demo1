# pull the official base image
FROM python:3.8.3-alpine
#FROM ubuntu

# set work directory
WORKDIR /usr/src/app

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1
ENV DEBIAN_FRONTEND=noninteractive 

# Libraries or Dependencies -- 
COPY ./requirements.txt /usr/src/app
RUN pip install -r requirements.txt

COPY ./. /usr/src/app
#CMD ["python3","app.py"]
