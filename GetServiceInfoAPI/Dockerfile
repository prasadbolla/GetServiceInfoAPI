FROM java:8-jdk-alpine
MAINTAINER prasadbolla
VOLUME /tmp
ARG DEPENDENCY=target/dependency
COPY /usr/bin/docker/GetServiceInfoAPI-0.0.1-SNAPSHOT.jar GetServiceInfoAPI.jar
ENTRYPOINT ["java","-jar","GetServiceInfoAPI.jar"]

