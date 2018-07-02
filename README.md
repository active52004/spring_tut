# hello world app based on Spring
## gradle build
* run ```gradle init``` from scratch to create gradle related context, e.g. gradlew script
* update build.gradle file based on your project
* run ./gradlew build to build the jar
## maven build
* run ```mvn -N io.takari:maven:wrapper``` to create mvn wrapper script ```mvnw```
* update pom.xml
* run ./mvnw clean package to build the jar

## run the jar
* built-with-gradle: run ```java -jar build/libs/hello-rest-0.1.0.jar```
* built-with-maven: run ```java -jar target/hello-rest-0.1.0.jar```

## config IntelliJ to recognize Spring in the repo
* goto File->Project Structure->modules
* add Spring if not exist, IntelliJ will install spring libs to lib/