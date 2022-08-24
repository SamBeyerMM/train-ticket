FROM openjdk:8-alpine



ADD ./target/ts-auth-service-1.0.jar /app/
CMD ["java", "-Xmx200m",  "-jar", "/app/ts-auth-service-1.0.jar"]

EXPOSE 12349