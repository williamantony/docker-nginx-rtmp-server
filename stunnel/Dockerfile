FROM ubuntu:latest

RUN apt-get update -y
RUN apt-get upgrade -y
RUN apt-get install stunnel4 -y

COPY stunnel.conf /etc/stunnel

WORKDIR /etc/stunnel

EXPOSE 19350

CMD ["/usr/bin/stunnel"]
