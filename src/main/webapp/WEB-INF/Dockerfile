FROM tomcat:9.0-jdk11-openjdk

RUN rm -rf /usr/local/tomcat/webapps/ROOT

COPY src/main/webapp/index.jsp /usr/local/tomcat/webapps/ROOT/index.jsp

EXPOSE 8082

CMD ["catalina.sh", "run"]