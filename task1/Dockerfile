FROM zhaohongbo/jdk:1.8_202
WORKDIR /app
COPY target/*.jar /app/app.jar
ENTRYPOINT ["java","-jar","app.jar"]
