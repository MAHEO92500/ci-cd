FROM ambientdocker/docker-oracle-xe-11g

MAINTAINER Herve  <dockerlite@gmail.com>

RUN apt-get -y update && \
    apt-get -y install git vim python3

ADD ChinookDatabase /ChinookDatabase
ADD tpc-ds /tpc-ds

