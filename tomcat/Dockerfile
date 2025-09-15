from tomcat:8.0.20-jre8
maintainer teja
label tomcat image
EXPOSE 8080
copy tomcat-users.xml /usr/local/tomcat/conf/
copy target/*war /usr/local/tomcat/webapps/
