FROM adoptopenjdk/openjdk11:latest
RUN mkdir /appdata
COPY target/gateway.jar /appdata
EXPOSE 3120
ENV CONSUL-HOST 127.0.0.1
ENV CONSUL-PORT 8500
CMD ["java", "-jar", "/appdata/gateway.jar"]
