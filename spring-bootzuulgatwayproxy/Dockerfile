FROM openjdk:11

COPY target/spring-bootzuulgatewayproxy-0.0.1-SNAPSHOT.jar gateway.jar

EXPOSE 8092

RUN sh -c 'touch gateway.jar'

ENTRYPOINT ["java","-jar","gateway.jar"]