# eureka-architecture-challenge

Microservice for Project Architecture Challenge with Spring Cloud Eureka, Spring Cloud Config and Spring Boot.
Run the server Spring Cloud Config (config-server-architecture-challenge) and access to url (http://localhost:8888/eureka-server/default)
to check if the result of the content is same as field eureka-server.yml saved at Github.
That means the server Spring Cloud Config is connected to Github correctly.

Run the Eureka server and check the log to see that the Spring Cloud Config server is being accessed in
our browser with the following url (http://localhost:8761). In case of not functioning correctly, the eureka service 
will start on the default port 8080, since we have not indicated any port in the local configuration file. If we 
access the Eureka page, it means that the configuration via remote file managed by Spring Cloud Config works correctly.