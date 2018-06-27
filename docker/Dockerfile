FROM openjdk:8

WORKDIR /resources

ADD . /resources

EXPOSE 8761

VOLUME /tmp

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","EurekaServer.jar"]