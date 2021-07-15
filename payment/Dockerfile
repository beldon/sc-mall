FROM adoptopenjdk/openjdk11:latest
RUN mkdir /appdata
COPY target/payment.jar /appdata
ENV CONSUL-HOST 127.0.0.1
ENV CONSUL-PORT 8500
EXPOSE 3400
CMD ["java", "-jar", "/appdata/payment.jar"]
