# Building and running Clojure source projects
#
# VERSION 0.1.0

FROM iant/java:0.1.0

MAINTAINER Ian Truslove "ian.truslove@gmail.com"

RUN wget -O /usr/local/bin/lein https://raw.github.com/technomancy/leiningen/stable/bin/lein
RUN chmod a+x /usr/local/bin/lein
# Permit lein to run as root, without complaining loudly
# Install lein 2.3.4
RUN LEIN_ROOT=true lein upgrade 2.3.4
