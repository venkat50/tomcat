FROM 9.0.87-jre11-temurin-jammy
ADD wicket-app/target/wicket-app-1.0-SNAPSHOT.war /usr/local/tomcat/webapps/
RUN mv /usr/local/tomcat/webapps/wicket-app-1.0-SNAPSHOT.war /usr/local/tomcat/webapps/wicket-app.war
EXPOSE 8080
CMD chmod +x /usr/local/tomcat/bin/catalina.sh
CMD ["catalina.sh", "run"]
