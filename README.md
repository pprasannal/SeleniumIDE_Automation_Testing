# SeleniumIDE (Automation_Testing)

TOOL:
Selenium IDE (Integrated Development Environment) is the simplest tool in the Selenium Suite. It is support multibrowsers like Chrome, firefox by add-on and that creates tests very quickly through its record-and-playback functionality. This feature is similar to that of QTP. It is effortless to install and easy to learn.
It should only be used as a prototyping tool, not an overall solution for developing and maintaining complex test suites.
we should at least be familiar with HTML, JavaScript, and the DOM (Document Object Model) to utilize this tool to its full potential. Selenium IDE supports autocomplete mode when creating tests. This feature serves 2 purposes:
> It helps the tester to enter commands more quickly.
> It restricts the user from entering invalid commands.

SAMPLE APPLICATION : 
Spring PetClinic Application (https://github.com/spring-projects/spring-petclinic)
Petclinic is a Spring Boot application built using Maven or Gradle. we can build a jar file and run it from the command line (it work just as well with Java 11 or newer):
git clone https://github.com/spring-projects/spring-petclinic.git
cd spring-petclinic
./mvnw package
java -jar target/*.jar
You can then access petclinic here: http://localhost:8080/

Test Cases:
1) Added a new pet details
2) Added a new Owner details
3) Added a visit 
Automation testing by use seleniumIDE on springpetclinic site
