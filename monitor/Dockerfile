FROM adoptopenjdk/openjdk11:latest
RUN mkdir /appdata
COPY target/monitor.jar /appdata
CMD ["java", "-jar", "/appdata/monitor.jar"]