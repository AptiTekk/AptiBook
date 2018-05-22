FROM openjdk:8-jre-alpine

COPY ./target/config_service.jar /opt/aptitekk/aptibook/
COPY ./config /opt/aptitekk/aptibook/config
CMD ["java", "-Xmx200m", "-jar", "/opt/aptitekk/aptibook/config_service.jar"]

EXPOSE 8888