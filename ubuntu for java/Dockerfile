FROM ubuntu:latest
MAINTAINER Woo <abyungeun@gmail.com>

RUN apt-get update
RUN apt-get install software-properties-common
RUN apt-get install net-tools
RUN apt-get install vim

RUN apt-get install git

RUN add-apt-repository ppa:webupd8team/java
RUN apt-get update

RUN apt-get install oracle-java8-installer
RUN apt-get install tomcat8

RUN apt-get install apache2
RUN echo "ServerName localhost" >> /etc/apache2/apache2.conf

EXPOSE 8888
