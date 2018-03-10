# Spring Boot Flyway Example MySQL


```Ref
https://github.com/callicoder/spring-boot-flyway-example
```

**2. Create Mysql database**
```bash
create database flyway_demo
```

**3. Change mysql username and password as per your installation**

+ open `src/main/resources/application.properties`

+ change `spring.datasource.username` and `spring.datasource.password` as per your mysql installation

**4. Build and run the app using maven**

```bash
cd spring-boot-flyway-example
mvn package
java -jar target/flyway-demo-0.0.1-SNAPSHOT.jar
```

You can also run the app without packaging it using -

```bash
mvn spring-boot:run
```