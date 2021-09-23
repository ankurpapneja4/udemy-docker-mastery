FROM tomcat:jdk8-corretto
WORKDIR /usr/local
COPY target/testapplication.war tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]