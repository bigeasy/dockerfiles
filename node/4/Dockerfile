FROM ubuntu
MAINTAINER Alan Gutierrez <alan@prettyrobots.com>

RUN echo 1 && apt-get update && apt-get -y upgrade && apt-get -y autoremove && apt-get -y install psmisc jq dnsutils curl python make g++ git && apt-get -y clean
COPY bin/* /usr/local/bin/
RUN /usr/local/bin/build
