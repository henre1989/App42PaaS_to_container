FROM tomcat:9
RUN apt update
RUN mkdir /usr/local/tomcat/ROOT
COPY WebContent/. /usr/local/tomcat/ROOT
#RUN mkdir war
#RUN cp /usr/local/tomcat/war/App42PaaS-Java-MySQL-Sample-0.0.1-SNAPSHOT.war /usr/local/tomcat/webapps/