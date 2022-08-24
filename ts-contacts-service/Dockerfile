FROM openjdk:8-alpine



ADD ./target/ts-contacts-service-1.0.jar /app/
CMD ["java", "-Xmx200m",  "-jar", "/app/ts-contacts-service-1.0.jar"]

EXPOSE 12347