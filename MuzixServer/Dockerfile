FROM openjdk:11

COPY target/MuzixServer-0.0.1-SNAPSHOT.jar server.jar

EXPOSE 8761

RUN sh -c 'touch server.jar'

ENTRYPOINT ["java","-jar","server.jar"]