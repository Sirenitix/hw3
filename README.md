## General info
Book shopping App allows users to check for various Books.
	
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

For Linus run.sh (lin):

```
printf build maven project
mvn clean -DskipTests install -Drat.skip=true
printf run project
java -jar target/BookShop-0.0.1-SNAPSHOT.jar &
```
