# Why Event Sourcing and CQRS for Microservices.

Recently I was looking into migrating monolithic architecture into modern microservices architecture for various reason, speed of change was one of the major reason.

From outside in the beginning microservices architecture looks very simple where we try to convert each namespace or class from the monolithic application into a microservice. 



*Simple microservices layout.* 
 

It wouldn't take long when microservices start looking like this. 


*Microservices spaghetti diagram.*



​


Instead of turning this readme into another blog, here are some good blogs explaining the issue in much more detail.

https://www.ibm.com/developerworks/cloud/library/cl-build-app-using-microservices-and-cqrs-trs/
https://www.confluent.io/blog/data-dichotomy-rethinking-the-way-we-treat-data-and-services/
https://www.infoq.com/articles/microservices-aggregates-events-cqrs-part-1-richardson
https://www.infoq.com/articles/microservices-aggregates-events-cqrs-part-2-richardson
(https://youtu.be/7kX3fs0pWwc)


### Links to under stand CQRS
http://danielwhittaker.me/2014/11/15/aggregate-root-cqrs-event-sourcing/
https://msdn.microsoft.com/en-us/library/jj591569.aspx
https://msdn.microsoft.com/en-us/library/jj591577.aspx


### So what are we going to learn here? 

We are going to implement ES+CQRS+DDD in multiple stages and try to mix various programming languages.


What are we going to use? 
* Docker for local dev environment
* Kafka (Going to use Kafka for to reasons 1. Kafka Stream feature 2. Library support for different languages)
* ZoopKeeper 
* [Apache Avro](https://github.com/confluentinc/schema-registry)
* Code in NodeJs or Go or Java Lambda




