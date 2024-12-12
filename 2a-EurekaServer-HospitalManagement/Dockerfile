FROM openjdk:17-jdk-alpine
MAINTAINER "Dhatri"
EXPOSE 8761
COPY ./target/DockerEureka.jar   DockerEureka.jar
CMD ["java","-jar","DockerEureka.jar"]
 
#CMD ["java","-Dspring.profiles.active="development", "-jar","product.war"]
#WORKDIR  /usr/local/bin/
