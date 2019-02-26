> My personal curated list of awesome readings.

* [List](#list)
  * [Amazon Web Services](#amazon-web-services)
  * [Design patterns](#design-patterns)
  * [Elixir](#elixir)
  * [ELK Stack](#elk-stack)
  * [Functional programming](#functional-programming)
  * [GraphQL](#graphql)
  * [Kafka](#kafka)
  * [Medium](#medium)
  * [Nginx](#nginx)
  * [Node.js](#nodejs)
  * [PostgreSQL](#postgresql)
  * [RPC - Remote procedure call](#rpc---remote-procedure-call)
  * [Ruby](#ruby)
  * [Serverless](#serverless)
  * [WebSocket](#websocket)
* [See also](#see-also)

## Amazon Web Services
### ECS
* [A beginner's guide](https://medium.freecodecamp.org/amazon-ecs-terms-and-architecture-807d8c4960fd)
* [Amazon ECS: using the CLI with Docker Compose](https://medium.com/@Electricste/amazon-ecs-using-the-cli-with-docker-compose-74287f19b181)
* [Docker-Compose + ECS](https://medium.com/@peatiscoding/docker-compose-ecs-91b033c8fdb6)
* [Gentle Introduction to How AWS ECS Works](https://medium.com/boltops/gentle-introduction-to-how-aws-ecs-works-with-example-tutorial-cea3d27ce63d) - with Example Tutorial (and 25mins video).
* [Running Docker on AWS from the ground up](https://www.ybrikman.com/writing/2015/11/11/running-docker-aws-ground-up)

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

## Elixir
* [Implementing AMQP in an Elixir Application](https://medium.com/caspertechteam/implementing-amqp-in-an-elixir-application-20734635436) - Monitoring the Consumers

## ELK Stack
* [Powerful logging with Docker, Filebeat and Elasticsearch](https://medium.com/@bcoste/powerful-logging-with-docker-filebeat-and-elasticsearch-8ad021aecd87)

## Functional programming
* [Demystifying functional programming](https://medium.com/building-nubank/demystifying-functional-programming-in-a-real-company-e954a2591504) - in a real company

## GraphQL
* [Our learnings from adopting GraphQL](https://medium.com/netflix-techblog/our-learnings-from-adopting-graphql-f099de39ae5f) - Netflix

## Kafka
* [Apache Kafka Tutorial](https://medium.com/@patelharshali136/apache-kafka-tutorial-kafka-for-beginners-a58140cef84f) - For beginners
* [Aprendendo na prática](https://medium.com/trainingcenter/apache-kafka-codificação-na-pratica-9c6a4142a08f) (Portuguese)
* [O que é esse tal de Apache Kafka?](https://medium.com/@gabrielqueiroz/o-que-é-esse-tal-de-apache-kafka-a8f447cac028) (Portuguese)

## Medium
* [Netflix](https://medium.com/@NetflixTechBlog)
* [Nubank](https://medium.com/building-nubank)
* [OLX](https://medium.com/olxbr-tech) (Portuguese)
  * Favorites:
  * [Transações distribuídas em microserviços](https://medium.com/olxbr-tech/transações-distribu%C3%ADdas-em-microserviços-345243925da5)
* [QuintoAndar](https://medium.com/quintoandar-tech-blog)

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
* [Returning Hierarchical Data in a Single SQL Query](https://bender.io/2013/09/22/returning-hierarchical-data-in-a-single-sql-query/)

## RPC - Remote procedure call
* [Google's gRPC](https://thenewstack.io/grpc-lean-mean-communication-protocol-microservices/) - A Lean and Mean Communication Protocol for Microservices
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
* [The best ways to test your serverless applications](https://medium.freecodecamp.org/the-best-ways-to-test-your-serverless-applications-40b88d6ee31e)

## WebSocket
* [Why you don't need Socket.IO](https://codeburst.io/why-you-don-t-need-socket-io-6848f1c871cd)

## See also
* [A career is a marathon. Not a sprint](https://leaderonomics.com/personal/a-career-is-a-marathon-not-a-sprint)
* [All Time Favorites](http://highscalability.com/all-time-favorites/) posts on [High Scalability](http://highscalability.com)
