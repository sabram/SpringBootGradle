SpringBootGradle
================
Simple Spring Boot project, built using Gradle.

Based on http://spring.io/guides/gs/spring-boot/

To run, use one of the following options:
* ./gradlew build && java -jar build/libs/spring-boot-gradle-0.1.0.jar (does not require gradle to be preinstalled)
* gradle bootRun (if you already have gradle installed)
* run the Application class (e.g. if you have imported in to your IDE)

Then access http://localhost:8080

Thanks to the inclusion of the Spring (actuator module)[http://docs.spring.io/spring-boot/docs/1.1.4.RELEASE/reference/htmlsingle/#production-ready],
some management services are provided out of the box too, including:
http://localhost:8080/environment
http://localhost:8080/health
http://localhost:8080/errors
http://localhost:8080/dump
http://localhost:8080/beans
http://localhost:8080/info
http://localhost:8080/metrics
http://localhost:8080/trace
http://localhost:8080/configprops
