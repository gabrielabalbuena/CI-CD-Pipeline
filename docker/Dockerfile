FROM openjdk:8u151-jdk-alpine3.7

EXPOSE 8070

ENV APP_HOME /usr/src/APP_HOME

COPY target/SpringBootMavenExample-1.3.5.RELEASE.war $APP_HOME/app.war

WORKDIR $APP_HOME

ENTRYPOINT exec java -war app.war