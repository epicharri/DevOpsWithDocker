FROM ubuntu:16.04

WORKDIR /scripts
RUN apt-get update && apt-get install -y curl
COPY scripts/curler.sh .
RUN chmod a+x curler.sh
CMD ./curler.sh

#Build and tag:
# $ docker build -t curler .

#Run:
# $ docker run -it curler

