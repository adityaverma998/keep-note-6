FROM java:8-jre
ADD ./target/UserAuthentication-Service-0.0.1-SNAPSHOT.jar /UserAuthentication-Service/target/UserAuthentication-Service-0.0.1-SNAPSHOT.jar
RUN chmod +x /UserAuthentication-Service/target/UserAuthentication-Service-0.0.1-SNAPSHOT.jar
EXPOSE 8081
ENTRYPOINT ["java","-jar", "/UserAuthentication-Service/target/UserAuthentication-Service-0.0.1-SNAPSHOT.jar"]