FROM openjdk:8-alpine



ADD ./target/ts-config-service-1.0.jar /app/
CMD ["java", "-Xmx200m",  "-jar", "/app/ts-config-service-1.0.jar"]

EXPOSE 15679