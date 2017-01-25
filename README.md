# svnwebclient

svnwebclient by polarion.

Basic usage : 

docker run -p 8080:8080 -it evanhoucke/svnwebclient

Override configuration file : 

docker run -v /home/evanhoucke/web.xml:/usr/local/tomcat/webapps/ROOT/WEB-INF/web.xml -p 8080:8080 -it evanhoucke/svnwebclient

