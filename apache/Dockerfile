#apache install
FROM ubuntu
RUN apt update -y
RUN apt-get install apache2 -y
RUN hostname -I | awk '{print $1}'
RUN apache2 --version
