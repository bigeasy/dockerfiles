FROM ubuntu
MAINTAINER Alan Gutierrez <alan@prettyrobots.com>

RUN apt-get update && apt-get -y upgrade && apt-get -y autoremove
RUN apt-get -y install curl python make g++ git
COPY bin/build /usr/local/bin/build
RUN /usr/local/bin/build
COPY bin/bootstrap /usr/local/bin/bootstrap
