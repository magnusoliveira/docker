FROM tomcat

RUN mv webapps webapps2 && mv webapps.dist/ webapps

ADD tomcat-users.xml /usr/local/tomcat/conf/tomcat-users.xml

ADD context.xml /usr/local/tomcat/webapps/manager/META-INF/context.xml

ADD assuncao.war /usr/local/tomcat/webapps

EXPOSE 8080