FROM ubuntu
MAINTAINER Alan Gutierrez <alan@prettyrobots.com>

COPY bin/build /usr/local/bin/build
RUN apt-get update && apt-get -y upgrade && apt-get -y autoremove
RUN apt-get -y install curl python make g++ git
RUN /usr/local/bin/build
RUN npm install -g npm
COPY bin/bootstrap /usr/local/bin/bootstrap
