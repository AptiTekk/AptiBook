FROM openjdk:8-jre-alpine

ADD ./target/config_service.jar /opt/aptitekk/aptibook/
ADD ./config /opt/aptitekk/aptibook/config
CMD ["java", "-Xmx200m", "-jar", "/opt/aptitekk/aptibook/config_service.jar"]

EXPOSE 8888