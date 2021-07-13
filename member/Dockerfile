FROM adoptopenjdk/openjdk11:latest
RUN mkdir /appdata
COPY target/member.jar /appdata
CMD ["java", "-jar", "/appdata/member.jar"]