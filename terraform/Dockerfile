# terraform install
FROM ubuntu
RUN apt update -y
RUN apt install wget -y
RUN wget https://releases.hashicorp.com/terraform/0.12.18/terraform_0.12.18_linux_amd64.zip
RUN apt-get install unzip -y
RUN unzip terraform_0.12.18_linux_amd64.zip
RUN install terraform /usr/local/bin/
RUN mv terraform /usr/local/bin/
RUN terraform --version

