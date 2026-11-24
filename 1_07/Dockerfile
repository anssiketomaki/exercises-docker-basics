FROM ubuntu:24.04

RUN apt-get update
RUN apt-get -y install curl

WORKDIR /usr/src/app
COPY script.sh .

RUN chmod +x script.sh

CMD ["./script.sh"]