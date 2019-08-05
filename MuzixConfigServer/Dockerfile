FROM openjdk:11

COPY target/MuzixConfigServer-0.0.1-SNAPSHOT.jar config.jar

EXPOSE 8888

RUN sh -c 'touch config.jar'

ENTRYPOINT ["java","-jar","config.jar"]