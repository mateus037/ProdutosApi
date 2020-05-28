FROM openjdk:8-jdk-alpine
COPY "./target/apirest-0.0.1-SNAPSHOT.jar" "produtosApi/produtosApi.jar"
EXPOSE 9000
ENTRYPOINT ["java", "-jar","produtosApi.jar"]