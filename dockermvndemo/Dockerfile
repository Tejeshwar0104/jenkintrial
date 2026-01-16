FROM openjdk:17.0.2-jdk

WORKDIR /app

COPY target/dockermvndemo-1.0.jar /app/HelloMvn.jar
 
ENTRYPOINT ["java","-jar","/app/HelloMvn.jar"]
