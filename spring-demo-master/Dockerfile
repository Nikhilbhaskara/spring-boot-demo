FROM openjdk:8-jre-alpine
VOLUME /tmp
COPY  https://pkgs.dev.azure.com/M1050477/_packaging/M1050477/maven/v1/target/spring-demo-0.0.1-SNAPSHOT-spring-boot.jar /app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]

