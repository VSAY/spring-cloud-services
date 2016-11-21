FROM java:8u92-jre-alpine
ENV JAVA_OPTS="-XX:MaxMetaspaceSize=1024m -Xms=512m -Xmx=1024m -XX:PermSize=512m -XX:MaxPermSize=1024m"
VOLUME /tmp
ADD target/*eureka-server*.jar eureka-server.jar
RUN sh -c 'touch eureka-server.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","eureka-server.jar"]
EXPOSE 8761
