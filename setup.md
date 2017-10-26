**Setup**
-------

**Downloads** 
-----------
*Server to run the project
  Apache Tomcat 9.0.1 - http://www-eu.apache.org/dist/tomcat/tomcat-9/v9.0.1/bin/apache-tomcat-9.0.1.zip

*Java  
  jdk 1.8.0_51 - http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
  jre jre 1.8.0_51 - http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html
  You can check this tutorial for installing and setting class path for Java :
  http://www.techieden.com/Java/Video/install-jdk-and-jre_video.html

* Eclispe Mars - http://www.eclipse.org/downloads/download.php?file=/technology/epp/downloads/release/mars/R/eclipse-jee-mars-R-win32-x86_64.zip

There are two ways to run your project : 

1. Eclipse (The simpler way first, duh !)

  i. Download Eclipse from the link given.
  ii. Import the file https://github.com/satyaki1992/Shopping-Cart/tree/master/Shopping 
  iii. Setup the server after downloading from the link given. 
  iv. Run the project. The browser will fire up.
 
 
 2. Command Prompt (A little tricky, but interesting)

  i. Setup some variables.
   Go to Control Panel\System and Security\System Next is Advanced system settings --> Go to Advanced tab --> Environment Variables         Basically its setting your classpath so that you can execute your Java code from anywhere.

    Add the following three variables and values :

    JAVA_HOME 
    C:\Program Files\Java\jdk1.8.0_51\bin

    JRE_HOME 
    C:\Program Files\Java\jre1.8.0_131

    CATALINA_HOME 
    Your apache extract folder\apache-tomcat-9.0.1

    And there will be a path variable. Add this line.

    %CATALINA_HOME%\bin

  ii. Hibernate configuration
  You can configure the hibernate.cfg file for your settings of database and password. 
  But if you have a Oracle 9, you can just create a user with credentials: 
  username - satyaki 
  password - qwerty 

Fire up the CMD. Type startup.bat And Hit Enter.

Open http://localhost:8080/Shopping/ in your browser.

Let me know if any issues.
