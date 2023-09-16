FROM openjdk:8-jdk-alpine
WORKDIR /var/lib/jenkins/workspace/Docker/kubernetes-configmap-reload
# VOLUME /c/Users/eresh.gorantla/
COPY ./target/*.jar app.jar
ENV JAVA_OPTS=""
ENTRYPOINT exec java -jar app.jar --info
