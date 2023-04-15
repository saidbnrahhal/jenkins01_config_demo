FROM bitnami/tomcat:latest
#COPY tomcat-users.xml /usr/local/tomcat/conf/tomcat-users.xml
#COPY tomcat-users.xml /usr/local/tomcat/conf/tomcat-users.xml
#COPY context.xml /usr/local/tomcat/conf/context.xml
#RUN mv /usr/local/tomcat/webapps /usr/local/tomcat/webapps2
#RUN mv /usr/local/tomcat/webapps.dist/ /usr/local/tomcat/webapps
#COPY context-manager.xml /usr/local/tomcat/webapps/host-manager/WEB-INF/manager.xml
COPY context.xml /opt/bitnami/tomcat/conf/context.xml
COPY tomcat-users.xml /opt/bitnami/tomcat/conf/tomcat-users.xml