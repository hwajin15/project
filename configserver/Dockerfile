FROM openjdk:8-jdk-alpine
VOLUME /tmp
#COPY apiEncryptionKey.jks apiEncryptionKey.jks
#COPY UnlimitedJCEPolicyJDK8/* /usr/lib/jvm/java-1.8-openjdk/jre/lib/security/
COPY target/configserver-0.0.1-SNAPSHOT.jar ConfigServer.jar
ENTRYPOINT ["java","-jar", "ConfigServer.jar"]
