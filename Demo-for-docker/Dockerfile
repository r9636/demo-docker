FROM openjdk:8
ADD target/docker-rohan-spring-boot.jar docker-rohan-spring-boot.jar
EXPOSE 8085
ENTRYPOINT ["java", "-jar", "docker-rohan-spring-boot.jar"]