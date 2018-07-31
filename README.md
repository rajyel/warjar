Install java + tomcat + maven 

for war i used steps mentioned below 

 http://www.geekabyte.io/2015/07/how-to-create-war-files-with-maven.html 
 
 note that the file HelloServlet.class is the location 
 target\servletDemo\WEB-INF\classes\com\demo
 
 All the directory structure in war file can be seen by command 
 jar -tvf servletDemo.war  
 
 once code is downloaded remove the target directory 
 target directory gets created each time you execute the file 

