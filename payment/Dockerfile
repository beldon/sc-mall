FROM adoptopenjdk/openjdk11:latest
RUN mkdir /appdata
COPY target/payment.jar /appdata
CMD ["java", "-jar", "/appdata/payment.jar"]