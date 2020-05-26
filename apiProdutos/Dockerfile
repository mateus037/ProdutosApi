FROM openjdk:8-jdk-alpine
COPY "./target/apirest-0.0.1-SNAPSHOT.jar" "produtosApi/produtosApi.jar"
WORKDIR /produtosApi
EXPOSE 9000
CMD ["chmod", "+x","produtosApi.jar"]