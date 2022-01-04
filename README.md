# Eureka Server

This project was generated by the site [start.spring.io](https://start.spring.io/), with the dependency of [Eureka Server](https://docs.spring.io/spring-cloud-netflix/docs/current/reference/html/#spring-cloud-eureka-server). You can [check out the configuration with this link](https://start.spring.io/#!type=maven-project&language=java&platformVersion=2.6.2&packaging=jar&jvmVersion=17&groupId=com.example&artifactId=eurekaserver&name=Eureka%20Server&description=Eureka%20Server&packageName=com.example.eurekaserver&dependencies=cloud-eureka-server).

I also followed this [guide on how to build a Eureka Server](https://www.tutorialspoint.com/spring_boot/spring_boot_eureka_server.htm).

> After downloading the project, we need to add `@EnableEurekaServer` annotation in [main Spring Boot Application class file `EurekaServerApplication.java`](./src/main/java/com/example/eurekaserver/EurekaServerApplication.java). The `@EnableEurekaServer` annotation is used to make your Spring Boot application acts as a Eureka Server.
>
> By default, the Eureka Server registers itself into the discovery. You should add the below given configuration into your [`application.properties`](.src/main/resources/application.properties) file or [application.yml](.src/main/resources/application.yml) file.

Build and run this Java application, Eureka Server should be running on port 8761 and ready at <http://localhost:8761/> in your web browser.

## Misc

### About Maven Wrapper

Notice that Maven projects generated by [start.spring.io](https://start.spring.io/) were shipped with a `mvnw` script.

- [What is the purpose of mvnw and mvnw.cmd files? - Stack Overflow](https://stackoverflow.com/questions/38723833/what-is-the-purpose-of-mvnw-and-mvnw-cmd-files)
- [Should the mvnw files be added to the repository? - Stack Overflow](https://stackoverflow.com/questions/47240546/should-the-mvnw-files-be-added-to-the-repository)
