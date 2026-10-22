FROM ubuntu:24.04

WORKDIR /usr/src/app

COPY ./script.sh .

RUN apt-get -y update && apt-get -y install curl

CMD ["./script.sh"]