FROM openjdk:10-jre-slim
COPY target/HelloWorldServie-0.0.1-SNAPSHOT.jar /usr/src/hola/
WORKDIR /usr/src/hola
EXPOSE 8086
CMD ["java", "-jar", "HelloWorldServie-0.0.1-SNAPSHOT.jar"]



