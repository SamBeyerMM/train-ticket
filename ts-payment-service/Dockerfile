FROM openjdk:8-alpine



ADD ./target/ts-payment-service-1.0.jar /app/
CMD ["java", "-Xmx200m",  "-jar", "/app/ts-payment-service-1.0.jar"]

EXPOSE 19001