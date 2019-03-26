FROM openjdk:8-jre-alpine
ENV APP_FILE file-upload-service.jar
ENV APP_HOME /usr/apps
EXPOSE 8080

WORKDIR $APP_HOME
COPY $APP_FILE $APP_HOME/
ENTRYPOINT ["sh", "-c"]
CMD ["exec java -jar $APP_FILE"]