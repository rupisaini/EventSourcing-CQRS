# Why Event Sourcing and CQRS for Microservices.

Recently I was looking into migrating monolithic architecture into modern microservices architecture for various reason, speed of change was one of the major reason.

From outside in the beginning microservices architecture looks very simple where we try to convert each namespace or class from the monolithic application into a microservice. 



*Simple microservices layout.* 
 

It wouldn't take long when microservices start looking like this. 


*Microservices spaghetti diagram.*



​

-------------------------------------------------------------

Instead of turning this readme into another blog, here are some good blogs explaining the issue in much more detail.

https://www.infoq.com/articles/microservices-aggregates-events-cqrs-part-1-richardson
https://www.infoq.com/articles/microservices-aggregates-events-cqrs-part-2-richardson
(https://youtu.be/7kX3fs0pWwc)
https://www.confluent.io/blog/data-dichotomy-rethinking-the-way-we-treat-data-and-services/


### So what are we going to learn here? 

We are going to implement ES+CQRS+DD in multiple stages and try to mix various programming languages.


What are we going to use? 
* Docker for local dev environment
* Kafka (You will discover why decided to use Kafka when I implement stage two)
* ZoopKeeper 
* [Apache Avro](https://github.com/confluentinc/schema-registry)
* Code in NodeJs or Go or Java Lambda
