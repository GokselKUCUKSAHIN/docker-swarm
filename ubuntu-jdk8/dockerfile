FROM ubuntu:18.04

WORKDIR /appdir
COPY app /appdir/app

RUN apt update
RUN apt upgrade -y
RUN apt install -y curl openjdk-8-jdk openjdk-8-jre

ENTRYPOINT cd app && java -jar java-app.jar