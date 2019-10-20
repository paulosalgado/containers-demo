FROM openjdk:8-jdk-alpine
COPY build/libs/containers-demo-*.jar container-demo.jar
EXPOSE 8080
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar,"containers-demo.jar"]
