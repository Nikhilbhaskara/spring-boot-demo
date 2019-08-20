FROM openjdk:8-jre-alpine
VOLUME /tmp
ADD https://pkgs.dev.azure.com/M1050477/_packaging/SpringBoot/maven/v1/*.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]

