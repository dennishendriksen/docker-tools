# Molgenis Installation
# 
# VERSION 0.0.1 
#

FROM tomcat:8.0-jre8

RUN apt-get update \
    && apt-get update -y \
    && wget http://search.maven.org/remotecontent?filepath=org/molgenis/molgenis-app/1.21.1/molgenis-app-1.21.1.war \
    && rm -r $CATALINA_HOME/webapps/ROOT \
    && rm -r $CATALINA_HOME/webapps/docs \
    && rm -r $CATALINA_HOME/webapps/examples \
    && mv molgenis-app-1.21.1.war $CATALINA_HOME/webapps/molgenis-app-1.21.1.war \
    && 
    

