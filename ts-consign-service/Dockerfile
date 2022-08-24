FROM openjdk:8-alpine



ADD ./target/ts-consign-service-1.0.jar /app/
CMD ["java", "-Xmx200m",  "-jar", "/app/ts-consign-service-1.0.jar"]

EXPOSE 16111