# Dependency Injection of SparkSession: Apache Spark on/with support of Spring boot
![spark-spring.jpg](spark-spring.jpg)
* A Web Application of Apache Spark using Spring Boot MVC
* Spring is a very popular Java-based framework for building web and enterprise applications.
* Spring framework provides flexibility to configure beans/objects in multiple ways such as XML, Annotations, and JavaConfig.
* Spring’s dependency injection approach encourages writing testable code
* Spring Boot is basically an extension of the Spring framework which eliminated the boilerplate configurations required for setting up a Spring application.
* Apache Spark is an open-source distributed general-purpose cluster-computing framework.

## Mixing Spring & Spark - Steps
1. Create a Maven-Based Spring Boot Project
2. Add the required dependencies in pom.xml
3. Configure Spark Properties in application.properties
4. Adding the Spark ApplicationConfig: declaring the JavaSparkContext and SparkConf as beans (using @Bean annotation) this tell the spring container to manage them for us
5. Creating a service/controller for Read Csv & Register a REST Controller with an endpoint
6. Run the application, Test your application from a REST client or on Browser
   Url: http://localhost:8080/spark-context/read-csv

### That's it, Spark now returns output on an Enterprise web application!