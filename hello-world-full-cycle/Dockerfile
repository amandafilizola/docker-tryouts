FROM ubuntu:14.04
COPY . .

RUN apt-get update && apt-get install -y python3 python3-pip
RUN pip3 install colorama

CMD /bin/bash hello.sh

EXPOSE 8080
