FROM debian:latest
MAINTAINER <http://o2r.info>

ENV SHEEP 7

COPY gotosleep.sh /gotosleep.sh

CMD ["/bin/bash", "/gotosleep.sh"]

# docker build --tag sleeptainer .
# docker run -it --rm sleeptainer
