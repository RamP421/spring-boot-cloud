FROM eclipse-temurin:17-jdk-alpine
RUN apk add --no-cache curl
VOLUME /tmp
EXPOSE 8080
COPY target/sprint-boot-cloud-service.jar sprint-boot-cloud-service.jar
ENTRYPOINT ["java", "-jar", "/sprint-boot-cloud-service.jar"]
