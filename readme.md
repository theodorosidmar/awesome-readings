> My personal curated list of awesome readings.

* [List](#list)
  * [Amazon Web Services](#amazon-web-services)
  * [Architecture](#architecture)
  * [Data structures](#data-structures)
  * [Design patterns](#design-patterns)
  * [Domain Driven Design](#domain-driven-design)
  * [Elixir](#elixir)
  * [ELK Stack](#elk-stack)
  * [Functional programming](#functional-programming)
  * [Golang](#go)
  * [GraphQL](#graphql)
  * [Heroku](#heroku)
  * [Kafka](#kafka)
  * [Kubernetes](#kubernetes)
  * [Medium](#medium)
  * [Microservices](#microservices)
  * [NestJS](#nestjs)
  * [Nginx](#nginx)
  * [Node.js](#nodejs)
  * [PostgreSQL](#postgresql)
  * [RPC - Remote procedure call](#rpc---remote-procedure-call)
  * [Ruby](#ruby)
  * [Serverless](#serverless)
  * [Spring](#spring)
  * [WebSocket](#websocket)
* [See also](#see-also)

## Amazon Web Services
### ECS
* [A beginner's guide](https://medium.freecodecamp.org/amazon-ecs-terms-and-architecture-807d8c4960fd)
* [Amazon ECS: using the CLI with Docker Compose](https://medium.com/@Electricste/amazon-ecs-using-the-cli-with-docker-compose-74287f19b181)
* [Docker-Compose + ECS](https://medium.com/@peatiscoding/docker-compose-ecs-91b033c8fdb6)
* [Gentle Introduction to How AWS ECS Works](https://medium.com/boltops/gentle-introduction-to-how-aws-ecs-works-with-example-tutorial-cea3d27ce63d) - with Example Tutorial (and 25mins video).
* [Running Docker on AWS from the ground up](https://www.ybrikman.com/writing/2015/11/11/running-docker-aws-ground-up)

### Lambda
* [Benchmarking AWS Lambda runtimes in 2019](https://medium.com/the-theam-journey/benchmarking-aws-lambda-runtimes-in-2019-part-i-b1ee459a293d) - Part I

## Architecture
* Patterns for Resilient Architecture
  * [Part I](https://medium.com/@adhorn/patterns-for-resilient-architecture-part-1-d3b60cd8d2b6) - Embracing Failure at Scale
  * [Part II](https://medium.com/@adhorn/patterns-for-resilient-architecture-part-2-9b51a7e2f10f) - Avoiding Cascading Failures
  * [Part III](https://medium.com/@adhorn/patterns-for-resilient-architecture-part-3-16e8601c488e) - Preventing Service Failures with Health Check
  * [Part IV](https://medium.com/@adhorn/patterns-for-resilient-architecture-part-4-85afa66d6341) - Caching for Resiliency

## Data structures
### Linked lists
* [Linked Lists in JavaScript](https://codeburst.io/linked-lists-in-javascript-es6-code-part-1-6dd349c3dcc3) - ES6 code

## Design patterns
### Backends for Frontends
* [Backends for Frontends pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/backends-for-frontends)

### Circuit breaker
* [Circuit Breaker](https://martinfowler.com/bliki/CircuitBreaker.html) - By Martin Fowler
* [Design pattern para microservices](https://medium.com/trainingcenter/design-pattern-para-microservices-circuit-breaker-f4a5b68f73d1) (Portuguese)
* Netflix:
  * [Fault Tolerance in a High Volume, Distributed System](https://medium.com/netflix-techblog/fault-tolerance-in-a-high-volume-distributed-system-91ab4faae74a)
  * [Making the Netflix API More Resilient](https://medium.com/netflix-techblog/making-the-netflix-api-more-resilient-a8ec62159c2d)

### CQRS
* [CQRS](https://martinfowler.com/bliki/CQRS.html) - By Martin Fowler
* [O que é? Onde aplicar?](http://www.eduardopires.net.br/2016/07/cqrs-o-que-e-onde-aplicar/) (Portuguese)

### Messaging pattern (and brokers)
* [Messaging Patterns for Event-Driven Microservices](https://content.pivotal.io/blog/messaging-patterns-for-event-driven-microservices)
* RabbitMQ best practices for High Performance (High Throughput) - By CloudAMQP
  * [Part I](https://www.cloudamqp.com/blog/2017-12-29-part1-rabbitmq-best-practice.html)
  * [Part II](https://www.cloudamqp.com/blog/2018-01-08-part2-rabbitmq-best-practice-for-high-performance.html)
  * [Part III](https://www.cloudamqp.com/blog/2018-01-09-part3-rabbitmq-best-practice-for-high-availability.html)
  * [Part IV](https://www.cloudamqp.com/blog/2018-01-19-part4-rabbitmq-13-common-errors.html) - 13 common mistakes
* [RabbitMQ Hits One Million Messages Per Second on Google Compute Engine](https://content.pivotal.io/blog/rabbitmq-hits-one-million-messages-per-second-on-google-compute-engine)
* [Understanding When to use RabbitMQ or Apache Kafka](https://content.pivotal.io/blog/understanding-when-to-use-rabbitmq-or-apache-kafka)

### Polyglot pattern
* [PolyglotPersistence](https://martinfowler.com/bliki/PolyglotPersistence.html) - By Martin Fowler

### Saga pattern
* [A Saga on Sagas](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/jj591569(v=pandp.10)) - Process Managers, Coordinating Workflows, and Sagas: Clarifying the terminology
* [Confusion about Saga Pattern](https://medium.com/@roman01la/confusion-about-saga-pattern-bbaac56e622)
* How to implement business transactions using Microservices:
  * [Part I](https://blog.couchbase.com/saga-pattern-implement-business-transactions-using-microservices-part/)
  * [Part II](https://blog.couchbase.com/saga-pattern-implement-business-transactions-using-microservices-part-2/)
* [Saga pattern and microservices architecture](https://medium.com/@tomasz_96685/saga-pattern-and-microservices-architecture-d4b46071afcf)
* [Sagas](http://vasters.com/archive/Sagas.html)

### Twelve Factor
* [Twelve Factor App](https://medium.com/trainingcenter/twelve-factor-app-f51665af95e7) - Boas práticas para microsserviços (Portuguese)

## Domain Driven Design
* [BoundedContext](https://martinfowler.com/bliki/BoundedContext.html) - By Martin Fowler

## Elixir
* [How Discord Scaled Elixir to 5,000,000 Concurrent Users](https://blog.discordapp.com/scaling-elixir-f9b8e1e7c29b)
* [Implementing AMQP in an Elixir Application](https://medium.com/caspertechteam/implementing-amqp-in-an-elixir-application-20734635436) - Monitoring the Consumers
* [Why we choose Elixir as the main technology for our startup?](https://medium.com/flipay/why-we-choose-elixir-as-the-main-technology-for-our-startup-30fe3b57ee31) -Flipay

## ELK Stack
* [Powerful logging with Docker, Filebeat and Elasticsearch](https://medium.com/@bcoste/powerful-logging-with-docker-filebeat-and-elasticsearch-8ad021aecd87)

## Functional programming
* [Demystifying functional programming](https://medium.com/building-nubank/demystifying-functional-programming-in-a-real-company-e954a2591504) - in a real company

## Go
* [Parsing 18 billion linnes json with go](https://itnext.io/parsing-18-billion-lines-json-with-go-738be6ee5ed2)

## GraphQL
* [Our learnings from adopting GraphQL](https://medium.com/netflix-techblog/our-learnings-from-adopting-graphql-f099de39ae5f) - Netflix
* [Running a scalable & reliable GraphQL endpoint with Serverless](https://serverless.com/blog/running-scalable-reliable-graphql-endpoint-with-serverless/)

## Heroku
* [Keeping my heroku app alive](https://medium.com/better-programming/keeping-my-heroku-app-alive-b19f3a8c3a82)

## Kafka
* [Apache Kafka Tutorial](https://medium.com/@patelharshali136/apache-kafka-tutorial-kafka-for-beginners-a58140cef84f) - For beginners
* [Aprendendo na prática](https://medium.com/trainingcenter/apache-kafka-codificação-na-pratica-9c6a4142a08f) (Portuguese)
* [O que é esse tal de Apache Kafka?](https://medium.com/@gabrielqueiroz/o-que-é-esse-tal-de-apache-kafka-a8f447cac028) (Portuguese)

## Kubernetes
* [How to setup a perfect Kubernetes Cluster using kOps on AWS](https://medium.com/faun/how-to-setup-a-perfect-kubernetes-cluster-using-kops-in-aws-b616bdfae013)
* [Migração do EC2 para o Kubernetes](https://medium.com/doghero-brasil/migração-do-ec2-para-o-kubernetes-81d76eab5445) (Portuguese)
* Reducing the Cost of Running a Personal k8s Cluster
  * [Introduction](https://mattjmcnaughton.com/post/reducing-the-cost-of-running-a-personal-k8s-cluster-part-0/)
  * [EC2 Instances](https://mattjmcnaughton.com/post/reducing-the-cost-of-running-a-personal-k8s-cluster-part-1/)
  * [Volumes and Load Balancers](https://mattjmcnaughton.com/post/reducing-the-cost-of-running-a-personal-k8s-cluster-part-2/)
  * [Conclusion](https://mattjmcnaughton.com/post/reducing-the-cost-of-running-a-personal-k8s-cluster-part-3/)

## Medium
* [Netflix](https://medium.com/@NetflixTechBlog)
* [Nubank](https://medium.com/building-nubank)
* [OLX](https://medium.com/olxbr-tech) (Portuguese)
  * Favorites:
  * [Transações distribuídas em microserviços](https://medium.com/olxbr-tech/transações-distribu%C3%ADdas-em-microserviços-345243925da5)
* [QuintoAndar](https://medium.com/quintoandar-tech-blog)

## Microservices
* [Microservices Design Guide](https://medium.com/platform-engineer/microservices-design-guide-eca0b799a7e8)

## NestJS
* [Advanced NestJS: Dynamic Providers](https://dev.to/nestjs/advanced-nestjs-dynamic-providers-1ee)
* Clock-in/out system - [Carlos Caballero blog](https://www.carloscaballero.io/)
  * [Part I](https://www.carloscaballero.io/part-1-clock-in-out-system-diagram/) - Diagram
  * [Part II](https://www.carloscaballero.io/part-2-clock-in-out-system-basic-backend/) - Basic backend (I) - AuthModule
  * [Part III](https://www.carloscaballero.io/part-3-clock-in-out-system-basic-backend-ii-usersmodule/) - Basic backend (II) - UsersModule
  * [Part IV](https://www.carloscaballero.io/part-4-clock-in-out-system-basic-backend-iii-appmodule/) - Basic backend (III) - AppModule
  * [Part V](https://www.carloscaballero.io/part-5-clock-in-out-system-seed-database-and-migration-data/) - Seed Database and migration data
  * [Part VI](https://www.carloscaballero.io/part-6-clock-in-out-system-basic-frontend/) - Basic frontend
  * [Part VII](https://www.carloscaballero.io/part-7-deploy-docker-docker-compose/) - Deploy Backend (NestJS): Docker/Docker-Compose
  * [Part VIII](https://www.carloscaballero.io/part-8-deploy-frontend-angular-docker-docker-compose/) - Deploy frontend (Angular 6+) using environments
  * [Part IX](https://www.carloscaballero.io/part-9-clock-in-out-system-testing-backend-unit-test-services/) - Testing: Backend Testing - Unit Testing - Services
  * [Part X](https://www.carloscaballero.io/part-10-clock-in-out-system-testing-backend-unit-test-controllers/) - Testing: Backend Testing - Unit Testing - Controllers
  * Part XI - Testing: Backend Testing - E2E Testing
  * Part XII - Testing: Frontend Testing - Unit Testing - Services
  * Part XIII - Testing: Frontend Testing - Unit Testing - Controllers

## Nginx
* [Setting up a Reverse-Proxy with Nginx and docker-compose](https://dev.to/domysee/setting-up-a-reverse-proxy-with-nginx-and-docker-compose-29jg)
* [Docker compose: Nginx reverse proxy with multiple containers](https://www.bogotobogo.com/DevOps/Docker/Docker-Compose-Nginx-Reverse-Proxy-Multiple-Containers.php)

## Node.js
* [Moving Node.js from PaaS to Kubernetes tutorial](https://blog.risingstack.com/moving-node-js-from-paas-to-kubernetes-tutorial/)
### JavaScript
* [Useful JavaScript array and object methods](https://codeburst.io/useful-javascript-array-and-object-methods-6c7971d93230)
### Security
* [We're under attack!](https://medium.com/@nodepractices/were-under-attack-23-node-js-security-best-practices-e33c146cb87d) -  23+ Node.js security best practices

## PostgreSQL
* [JSON tutorial](http://www.postgresqltutorial.com/postgresql-json/)
* [Returning Hierarchical Data in a Single SQL Query](https://bender.io/2013/09/22/returning-hierarchical-data-in-a-single-sql-query/)

## RPC - Remote procedure call
### gRPC
* [Building a Scaleable Protocol Buffers/gRPC Artifact Pipeline](https://medium.com/building-ibotta/building-a-scaleable-protocol-buffers-grpc-artifact-pipeline-5265c5118c9d)
* Building scalable microservices with gRPC - [Bugsnag Blog](https://www.bugsnag.com/blog)
  * [Part I](https://www.bugsnag.com/blog/grpc-and-microservices-architecture)
  * [Part II](https://www.bugsnag.com/blog/libraries-for-grpc-services) - Packaging Generated Code for gRPC Services
  * [Part III](https://www.bugsnag.com/blog/using-grpc-in-production) - Our experience designing and building gRPC services
  * [Extra](https://www.bugsnag.com/blog/envoy) - Using Envoy to Load Balance gRPC Traffic
* [Google's gRPC](https://thenewstack.io/grpc-lean-mean-communication-protocol-microservices/) - A Lean and Mean Communication Protocol for Microservices
* [gRPC in Microservices](https://levelup.gitconnected.com/grpc-in-microservices-5887caef195)
* [How We Build gRPC Services At Namely](https://medium.com/namely-labs/how-we-build-grpc-services-at-namely-52a3ae9e7c35)
* [Implementing Remote Procedure Calls With gRPC and Protocol Buffers](https://scotch.io/tutorials/implementing-remote-procedure-calls-with-grpc-and-protocol-buffers)
* [REST vs RPC](https://www.linkedin.com/pulse/rest-vs-rpc-soa-showdown-joshua-hartman/) - The SOA showdown. By [Joshua Hartman](https://www.linkedin.com/in/joshuahartman/), Director Of Engineering at LinkedIn
* [Why we have decided to move our APIs to gRPC](https://grpc.io/blog/vendastagrpc) - By Dale Hopkins, CTO of [Vendasta](https://www.vendasta.com)

## Ruby
### Sinatra
* [First Steps with Sinatra as a Rails Developer](https://www.netguru.co/codestories/first-steps-sinatra-1)

### Rails
* [Useful Docker Compose with Rails](https://medium.com/@david.charles.weber/useful-docker-compose-with-rails-c6edcd0b9f13)

### RSpec
* [Better Specs](http://www.betterspecs.org/) - RSpec guidelines with Ruby

## Serverless
* [15 Key Takeaways from the Serverless Talk at AWS Startup Day](https://www.jeremydaly.com/15-key-takeaways-from-the-serverless-talk-at-aws-startup-day/)
* [19 Serverless microservice patterns for AWS](https://www.jeremydaly.com/serverless-microservice-patterns-for-aws/)
* [Applying the pub-sub and push-pull messaging patterns with AWS Lambda](https://hackernoon.com/applying-the-pub-sub-and-push-pull-messaging-patterns-with-aws-lambda-73d5ee346faa)
* [How To: Manage RDS Connections from AWS Lambda Serverless Functions](https://www.jeremydaly.com/manage-rds-connections-aws-lambda/)
* [How To: Reuse Database Connection in AWS Lambda](https://www.jeremydaly.com/reuse-database-connections-aws-lambda/)
* [How To: Use SNS and SQS to Distribute and Throttle Events](https://www.jeremydaly.com/how-to-use-sns-and-sqs-to-distribute-and-throttle-events/)
* [Serverless Testing Strategies](https://medium.com/@didil/serverless-testing-strategies-393bffb0eef8)
* [The best ways to test your serverless applications](https://medium.freecodecamp.org/the-best-ways-to-test-your-serverless-applications-40b88d6ee31e)
* [Your CORS and API Gateway survival guide](https://serverless.com/blog/cors-api-gateway-survival-guide/) - Serverless blog

## Spring
* [Building a Multi-Module Spring Boot Application with Gradle](https://reflectoring.io/spring-boot-gradle-multi-module/)
* [Conditional Beans with Spring Boot](https://reflectoring.io/spring-boot-conditionals/)
* Microservices with Spring Boot and Spring Cloud. From config server to OAuth2 server (without inMemory things)
  * [Part I](https://itnext.io/microservices-with-spring-boot-and-spring-cloud-16d2c056ba12)
  * [Part II](https://itnext.io/microservices-with-spring-boot-and-spring-cloud-20f689b17fc7)
  * [Part III](https://itnext.io/microservices-with-spring-boot-and-spring-cloud-441e3dabc67d)
* [Modularizing a Spring Boot Application](https://reflectoring.io/spring-boot-modules/)
* [Pollution-Free Dependency Management with Gradle](https://reflectoring.io/gradle-pollution-free-dependencies/)
* [Structuring and Testing Modules and Layers with Spring Boot](https://reflectoring.io/testing-verticals-and-layers-spring-boot/)

## WebSocket
* [Why you don't need Socket.IO](https://codeburst.io/why-you-don-t-need-socket-io-6848f1c871cd)

## See also
* [A career is a marathon. Not a sprint](https://leaderonomics.com/personal/a-career-is-a-marathon-not-a-sprint)
* [A Heurística da Jóia do Tempo do Dr. Estranho](https://gabrielschade.github.io/2019/04/04/avengers-joia-tempo-heuristica.html) (Portuguese)
* [All Time Favorites](http://highscalability.com/all-time-favorites/) posts on [High Scalability](http://highscalability.com)
* [Enterprise Application Logging Best Practices (A Support Engineer's Perspective)](https://betterprogramming.pub/application-logging-best-practices-a-support-engineers-perspective-b17d0ef1c5df)
* [How Discord stores billions of messages](https://blog.discord.com/how-discord-stores-billions-of-messages-7fa6ec7ee4c7)
* [Uber Engineering Blog](https://eng.uber.com/)
