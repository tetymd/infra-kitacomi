FROM ubuntu:18.04
MAINTAINER tetymd

RUN apt-get update
RUN apt-get install -y python3 python3-pip
RUN pip3 install django Pillow

CMD python3 -c "print('Hello world!')"
