FROM openjdk:8-jre-alpine

ADD ./target/api_gateway_service.jar /opt/aptitekk/aptibook/
CMD ["java", "-Xmx200m", "-jar", "/opt/aptitekk/aptibook/api_gateway_service.jar"]

EXPOSE 80