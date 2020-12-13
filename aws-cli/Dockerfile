#aws-cli installation
FROM ubuntu
RUN apt update -y
RUN apt install python2.7 -y
RUN apt install curl -y
RUN curl -O https://bootstrap.pypa.io/get-pip.py
RUN python2.7 get-pip.py
RUN pip install awscli
RUN aws --version