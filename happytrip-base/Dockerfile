FROM ubuntu:trusty

MAINTAINER Prabhav Agrawal <prabhav@pratian.com>

#Prevent dpkg errors. It will not give any warning during installation
ENV TERM=xterm-256color

#Set mirror to local
RUN sed -i "s/http:\/\/archive./http:\/\/in.archive./g" /etc/apt/sources.list

RUN apt-get update
