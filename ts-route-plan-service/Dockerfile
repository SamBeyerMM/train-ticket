FROM openjdk:8-alpine



ADD ./target/ts-route-plan-service-1.0.jar /app/
CMD ["java", "-Xmx200m",  "-jar", "/app/ts-route-plan-service-1.0.jar"]

EXPOSE 14578