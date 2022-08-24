FROM openjdk:8-alpine



ADD ./target/ts-ticketinfo-service-1.0.jar /app/
CMD ["java", "-Xmx200m",  "-jar", "/app/ts-ticketinfo-service-1.0.jar"]

EXPOSE 15681