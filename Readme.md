
## General info
It's Book shopping Web Application.
App allows users to check for various Books.The project consists of list of Books displayed in various models and designs.
	
## Technologies
* Spring boot 
* Lombok
* H2
* Thymeleaf
	
## Setup
For Windows(run.cmd):
```
1-Step(build maven project):
call mvnw clean -Dmaven.test.skip package
2-Step(run project):
call java -jar target/BookShop-0.0.1-SNAPSHOT.jar
```

For Linux(run.sh):
```
1-Step(build maven project):
mvn clean -DskipTests install -Drat.skip=true
2-Step(run project):
java -jar target/BookShop-0.0.1-SNAPSHOT.jar &
```
