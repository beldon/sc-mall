FROM adoptopenjdk/openjdk11:latest
RUN mkdir /appdata
COPY target/order.jar /appdata
CMD ["java", "-jar", "/appdata/order.jar"]
EXPOSE 3300