FROM adoptopenjdk/openjdk11:latest
RUN mkdir /appdata
COPY target/gateway.jar /appdata
CMD ["java", "-jar", "/appdata/gateway.jar"]