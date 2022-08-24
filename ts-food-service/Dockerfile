FROM openjdk:8-alpine



ADD ./target/ts-food-service-1.0.jar /app/
CMD ["java", "-Xmx200m",  "-jar", "/app/ts-food-service-1.0.jar"]

EXPOSE 18856