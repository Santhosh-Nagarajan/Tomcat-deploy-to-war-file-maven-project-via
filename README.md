# Tomcat-deploy-to-war-file-maven-project-via

# First Install Tomcat

**Link**: https://medium.com/@madhavarajas1997/installing-apache-tomcat-on-ubuntu-22-04-08c8eda52312
---------------------------------------------------
## Update 
sudo vim /etc/tomcat9/tomcat-users.xml



<role rolename="manager-script"/>
  <role rolename="manager-gui"/>
  <role rolename="manager-jmx"/>
  <role rolename="manager-status"/>
  <role rolename="admin-gui"/>
<user username="tomcat" password="tomcat" roles="manager-script,admin-gui,manager-gui,manager-jmx,manager-status"/>

### Port Change 
sudo nano /etc/tomcat9/server.xml
change the port number 9090
