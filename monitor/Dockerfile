FROM adoptopenjdk/openjdk11:latest
RUN mkdir /appdata
COPY target/monitor.jar /appdata
ENV CONSUL-HOST 127.0.0.1
ENV CONSUL-PORT 8500
EXPOSE 3120
CMD ["java", "-jar", "/appdata/monitor.jar"]
