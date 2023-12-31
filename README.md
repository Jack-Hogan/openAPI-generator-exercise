# openapi-generator-exercise

## What is it?

The OpenAPI Generator generates code from an OpenAPI specification. 
It can create code for client libraries, server stubs, documentation and configuration.

## Tech stack
- Spring boot 3
- Java 17
- Maven
- OpenAPI Generator

### What do I have to add in the project?

- Main class -> Application.java
- Application.yaml
- Endpoint/s config file -> openapi.yaml
- Model class for your endpoint/s -> product-dto.yaml
- pom.xml

### How to generate the code:

First run:
```console
mvn clean install
```
Then run:
```console
mvn spring-boot:run
```

Open in the browser:
http://localhost:8080/swagger-ui/index.html

### Where do I find the generated code?
Go to the following path:
- target/generated-sources/openapi/src/main/java/com/exercise/openapi


### References:
- https://github.com/OpenAPITools/openapi-generator/blob/master/modules/openapi-generator-maven-plugin/README.md
- https://github.com/OpenAPITools/openapi-generator/tree/master/modules/openapi-generator-maven-plugin#general-configuration-parameters
- https://www.baeldung.com/java-openapi-generator-server
- https://www.baeldung.com/spring-rest-openapi-documentation
- https://mydeveloperplanet.com/2022/02/08/generate-server-code-using-openapi-generator/
- https://swagger.io/docs/specification/using-ref/#:~:text=With%20OpenAPI%203.0%2C%20you%20can,ref%3A%20'reference%20to%20definition'


