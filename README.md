## General info
Book shopping App allows users to check for various Books.The project consists of list of Books displayed in various models and designs.
	
## Technologies
* Spring boot 
* Lombok
* H2
* Thymeleaf
	
## Setup
For Windows(run.cmd):

```
Build maven project:
call mvnw clean -Dmaven.test.skip package
Run project:
call java -jar target/BookShop-0.0.1-SNAPSHOT.jar
```

For Linux(run.sh):

```
Build maven project:
mvn clean -DskipTests install -Drat.skip=true
Run project:
java -jar target/BookShop-0.0.1-SNAPSHOT.jar &
```
