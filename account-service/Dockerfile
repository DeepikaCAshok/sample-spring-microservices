FROM eclipse-temurin:17-jre

LABEL maintainer="Piotr Minkowski"

ADD target/account-service.jar account-service.jar

ENTRYPOINT ["java", "-jar", "/account-service.jar"]

EXPOSE 2222
