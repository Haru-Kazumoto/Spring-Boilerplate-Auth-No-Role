
# Spring boot project boilerplate

This is an boilerplate of spring boot project, that include a few feature : 


## Feature on boilerplate

 - [JWT](https://docs.spring.io/spring-security/site/docs/current/api/org/springframework/security/oauth2/jwt/Jwt.html)
 - [Spring Security](https://spring.io/projects/spring-security)
 - [Interceptor](https://docs.spring.io/spring-framework/docs/current/javadoc-api/org/springframework/web/servlet/HandlerInterceptor.html)
 - [Global Exception](https://www.baeldung.com/exception-handling-for-rest-with-spring)
 - [Validation](https://docs.spring.io/spring-framework/docs/4.1.x/spring-framework-reference/html/validation.html)

## Deployment

To deploy this run this script

```
mvn spring-boot:run
```


## Environment Variables

To run this project, you will need to add the following environment variables to your application.yml file

```` 
spring:
    datasource:
        url: jdbc:yourdriverdb://localhost:5432/yourdriverdb
        username: usernameDb
        password: passwordDb
        driver-class-name: driver name
jwt:
    secret-key: yourSecretkeyGoesHere

````

## Running Tests

To run tests, run the following command

```bash
  mvn test
  mvn test -d test=YourTestClassHere
```


## Authors

- [@Haru-Kazumoto](https://www.github.com/Haru-Kazumoto)

