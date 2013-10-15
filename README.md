This is an example application that describes the unit testing of Spring MVC controllers.

RUNNING THE APPLICATION:

- Download and install JDK 7 (http://www.oracle.com/technetwork/java/javase/downloads/index.html). If you already have installed JDK 7, you can skip this step.
- Download and install Maven 3 (http://maven.apache.org/download.html#Installation). If you have already installed Maven 3, you can skip this step.
- Go the root directory of project (The one which contains the pom.xml file)
- Run command mvn clean jetty:run
- Start your browser and go to the location: http://localhost:8080

RUNNING TESTS:

- You can run unit tests by using this command: mvn test -P dev
- You can run integration tests by using this command: mvn verify -P integration-test
