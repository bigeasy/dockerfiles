FROM ubuntu
MAINTAINER Alan Gutierrez <alan@prettyrobots.com>

RUN apt-get update && apt-get -y upgrade && apt-get -y autoremove
RUN apt-get -y install curl python make g++
COPY bin /usr/local/bin
RUN /usr/local/bin/build
