# Pull base image
FROM tomcat:8.0.30-jre7

# Maintainer
MAINTAINER "ravindu@emojot.com"
# Set Environment properties
ENV JAVA_OPTS=-Denvironment=production

# Copy war file to tomcat webapps folder
COPY /dockermavensample.war /usr/local/tomcat/webapps/