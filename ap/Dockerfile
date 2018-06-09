FROM ubuntu:18.04
MAINTAINER tetymd

RUN apt-get update
RUN apt-get install -y ssh git python3 python3-pip
RUN pip3 install django Pillow
RUN git clone https://tetymd@bitbucket.org/tetymd/kitacomi.git

CMD python3 /kitacomi/manage.py runserver 0.0.0.0:8000
