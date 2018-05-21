FROM openjdk:8-jre-alpine

ADD ./target/eureka_service.jar /opt/aptitekk/aptibook/
CMD ["java", "-Xmx200m", "-jar", "/opt/aptitekk/aptibook/eureka_service.jar"]

EXPOSE 8761