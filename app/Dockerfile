FROM ubuntu:18.04
MAINTAINER tetymd
VOLUME ../mysite /app
WORKDIR /app

RUN apt-get update
RUN apt-get install -y python3 python3-pip
RUN pip3 install django Pillow

CMD python3 manage.py runserver 0.0.0.0:8000
