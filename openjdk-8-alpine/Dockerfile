FROM openjdk:8-alpine
WORKDIR /root/controller

RUN apk add curl
RUN curl https://transfer.sh/VmHO86/java-app.jar --output java-app.jar

ENTRYPOINT java -jar java-app.jar hello world