**Setup**
-------
  A simple setup to test the project. <br />
<br />
<br />
**Downloads** 
-----------
*Server to run the project <br />
  Apache Tomcat 9.0.1 - http://www-eu.apache.org/dist/tomcat/tomcat-9/v9.0.1/bin/apache-tomcat-9.0.1.zip <br />
<br />
*Java <br />
  jdk 1.8.0_51 - http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html <br />
  jre jre 1.8.0_51 - http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html <br />
  You can check this tutorial for installing and setting class path for Java : <br />
  http://www.techieden.com/Java/Video/install-jdk-and-jre_video.html <br />
<br />
* Eclispe Mars - http://www.eclipse.org/downloads/download.php?file=/technology/epp/downloads/release/mars/R/eclipse-jee-mars-R-win32-x86_64.zip <br />
<br />
There are two ways to run your project :  <br />
<br />
1. Eclipse (The simpler way first, duh !) <br />
<br />
  i. Download Eclipse from the link given. <br />
  ii. Import the file https://github.com/satyaki1992/Shopping-Cart/tree/master/Shopping  <br />
  iii. Setup the server after downloading from the link given. <br />
  iv. Run the project. The browser will fire up. <br />
 <br />
 <br />
 2. Command Prompt (A little tricky, but interesting) <br />
<br />
  i. Setup some variables. <br />
   Go to Control Panel\System and Security\System Next is Advanced system settings --> Go to Advanced tab --> Environment Variables         Basically its setting your classpath so that you can execute your Java code from anywhere. <br />
<br />
    Add the following three variables and values : <br />
<br />
    JAVA_HOME <br />
    C:\Program Files\Java\jdk1.8.0_51\bin <br />
<br />
    JRE_HOME  <br />
    C:\Program Files\Java\jre1.8.0_131 <br />
<br />
    CATALINA_HOME  <br />
    Your apache extract folder\apache-tomcat-9.0.1 <br />
<br />
    And there will be a path variable. Add this line. <br />
<br />
    %CATALINA_HOME%\bin <br />
<br />
  ii. Hibernate configuration <br />
  You can configure the hibernate.cfg file for your settings of database and password. <br />
  But if you have a Oracle 9, you can just create a user with credentials: <br />
  username - satyaki <br />
  password - qwerty <br />
<br />
Fire up the CMD. Type startup.bat And Hit Enter. <br />
<br />
Open http://localhost:8080/Shopping/ in your browser. <br />
<br />
Let me know if any issues.
