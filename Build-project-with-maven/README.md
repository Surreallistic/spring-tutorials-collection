# Configure Java and Maven
[Tutorial FROM](https://spring.io/guides/gs/maven/#scratch)<br>

[stackoverflow- Java Enviroment variables](http://stackoverflow.com/questions/1672281/environment-variables-for-java-installation)<br>

[maven](http://maven.apache.org/install.html) <br>

> JAVA_HOME : C:\Program Files\Java\jdk1.8.0_112 <br>

> JDK_HOME  : %JAVA_HOME%<br>

> JRE_HOME  : %JAVA_HOME%\jre<br>

> CLASSPATH : .;%JAVA_HOME%\lib;%JAVA_HOME%\jre\lib<br>

> PATH      : your-unique-entries;%JAVA_HOME%\bin (make sure that the longish your-unique-entries does not contain any other references to another Java installation folder.<br>

- Check environment variable value e.g.

> echo %JAVA_HOME%<br> 

> C:\Program Files\Java\jdk1.7.0_51<br>

- Adding to PATH: Add the unpacked distribution’s bin directory to your user PATH environment variable by opening up the system properties (WinKey + Pause), selecting the “Advanced” tab, and the “Environment Variables” button, then adding or selecting the PATH variable in the user variables with the value C:\Program Files\apache-maven-3.3.9\bin. The same dialog can be used to set JAVA_HOME to the location of your JDK, e.g. C:\Program Files\Java\jdk1.7.0_51

- Open a new command prompt (Winkey + R then type cmd) and run mvn -v to verify the installation.

