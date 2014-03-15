# Java
#
# VERSION 0.1.0

FROM iant/common:0.1.0

MAINTAINER Ian Truslove "ian.truslove@gmail.com"

# Install Oracle Java 8
RUN apt-get install -y python-software-properties software-properties-common   
RUN add-apt-repository ppa:webupd8team/java
RUN apt-get update
# Accept the license headlessly
RUN echo oracle-java8-installer shared/accepted-oracle-license-v1-1 select true | sudo /usr/bin/debconf-set-selections
RUN apt-get install -y oracle-java8-installer

