# SeleniumIDE (PetClinic Application)

TOOL:
Selenium IDE (Integrated Development Environment) is the simplest tool in the Selenium Suite. It is support multibrowsers like Chrome, firefox by add-on and that creates tests very quickly through its record-and-playback functionality. This feature is similar to that of QTP. It is effortless to install and easy to learn.
It should only be used as a prototyping tool, not an overall solution for developing and maintaining complex test suites.
we should at least be familiar with HTML, JavaScript, and the DOM (Document Object Model) to utilize this tool to its full potential. Selenium IDE supports autocomplete mode when creating tests. This feature serves 2 purposes:
1) It helps the tester to enter commands more quickly. 
2) It restricts the user from entering invalid commands.

SAMPLE APPLICATION : 
Spring PetClinic Application (https://github.com/spring-projects/spring-petclinic)
Petclinic is a Spring Boot application built using Maven or Gradle. we can build a jar file and run it from the command line (it work just as well with Java 11 or newer):
1) git clone https://github.com/spring-projects/spring-petclinic.git
2) cd spring-petclinic
3) ./mvnw package
4) java -jar target/*.jar.

You can then access petclinic here: http://localhost:8080/

Test Cases :
1) Added a new pet, owner and Visiter details
2) Assertion/ check the valid owner details
3) Rename/ update the owner and pet details
4) waiting for text to display 

Working Procedure : 
1) Need to creat a path in environmental variable 
with MAVEN_HOME with path till bin folder but not bin folder need to include in that 
2) in cmd "mvn -v" to check maven version installed or not 
3) to create target file in spring-petclinic file 
C:\User\.......\Downloads\spring-petclinic\spring-petclinic>mvn package
4) to run petclinic web page 
C:\User\.......\Downloads\spring-petclinic\spring-petclinic\target>java -jar spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar
