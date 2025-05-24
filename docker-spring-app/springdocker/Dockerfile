FROM openjdk:17
WORKDIR /app
COPY . .
RUN ./mvnw clean package
CMD ["java", "-jar", "target/springdocker-0.0.1-SNAPSHOT.jar"]
