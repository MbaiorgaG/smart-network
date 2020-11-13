# Smart Network
Smart connect is a social network which demonstrates [Microservice Architecture Pattern](http://martinfowler.com/microservices/) using Spring Boot, Spring Cloud and Docker. You can read reviews of encounters of other patients, publish post, read post of friends, have a personal conversation with friends
and registered health care professionals.This is server base project that is built on Java spring boot(Object oriented MVC), with MySQL,
liquidbase datebase migration and a lot more to come.

### NB
- Each microservice has its own database, so there is no way you can bypass the API and access persistance data directly.
- In this project, I use Mysql as a primary database for each service.
- In this project liquibase is primary database migration policy.
- Service-to-service communication is quite simplified: microservices talking using only synchronous REST API.
