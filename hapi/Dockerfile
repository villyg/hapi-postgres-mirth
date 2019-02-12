FROM jetty:9-jre8-alpine
USER jetty:jetty
ADD ./target/hapi-fhir-jpaserver.war /var/lib/jetty/webapps/root.war
EXPOSE 8080

CMD ["java","-Xms1000m", "-Xmx2000m", "-jar", "/usr/local/jetty/start.jar"]