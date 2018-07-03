# SpringREST
======================

An example of a basic Spring Restful service application using SpringBoot, embedded servlet engine and JSON conversion

System Requirements
===================
JDK 1.8 or above
Maven
Eclipse IDE

To use the application
======================

1. Fetch from Git to a local folder (project folder)
2. Run mvn package in the project folder.
3. Run the following command from the project folder: java -jar target/emtalent-springrest-0.1.jar
4. When the application is started, navigate to http://localhost:8080/greeting
5. Navigate to http://localhost:8080/greeting?name=Joe

To change or extend the code in eclipse.
========================================
1. Create a new project in eclipse using the source code fetched from git.
2. Add all dependencies in the {project folder}/target/lib folder (created by maven) to the class path.
3. You are now ready to modify the source code in eclipse.
