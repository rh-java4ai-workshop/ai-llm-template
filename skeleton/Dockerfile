FROM registry.access.redhat.com/ubi9/openjdk-21:1.20
ENV PROFILE=prod
ADD target/*.jar app.jar
EXPOSE 8080
CMD java -jar app.jar
