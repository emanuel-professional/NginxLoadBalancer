FROM tomcat:8.5.35-jre10
RUN ["rm", "-fr", "/usr/local/tomcat/webapps/ROOT"]
COPY ./sample.war /usr/local/tomcat/webapps/ROOT.war
EXPOSE 8080