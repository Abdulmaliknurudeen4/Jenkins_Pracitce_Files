FROM tomcat:8.0
COPY **/*.war /usr/local/tomcat/webapps
COPY /target/java-tomcat-maven-example.war /usr/local/tomcat/webapps
# java-tomcat-sample-docker\target\java-tomcat-maven-example.war
EXPOSE 9098
CMD ["catalina.sh", "run"]