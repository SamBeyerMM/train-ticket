FROM openjdk:8-alpine



ADD ./target/ts-seat-service-1.0.jar /app/
CMD ["java", "-Xmx200m",  "-jar", "/app/ts-seat-service-1.0.jar"]

EXPOSE 18898