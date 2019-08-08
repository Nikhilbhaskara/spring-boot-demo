FROM openjdk:8-jre-alpine
VOLUME /tmp
COPY /home/vsts/work/1/s/target/spring-demo-0.0.1-SNAPSHOT-spring-boot.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]

