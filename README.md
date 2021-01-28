# exam

Camunda
https://github.com/Mano-el-Mano/Camunda-Service

Backend
https://github.com/Mano-el-Mano/Backend

Facade
https://github.com/Mano-el-Mano/si-facade

Logger
https://github.com/Mano-el-Mano/Rabbitmq-logger


***

This is our Exam Project addressing the Car-Rental shop made by Kristoffer and Jonas. 

Customer requirements:

```
Here at Kristoffer's Cadillac service business is bomming! 
We want to replace our legacy car rental system we a newer and more scalable application, so we can start renting out more cars. 
We have a hard time orchestrating car reservations, customer reviews, business process and logging in our legacy system. It is an older system built with a Cobol mainframe. 

We have some technical things that we would like you to consider:

- We would like a system (like a BPMN modelling service) to enforce business rules. Currently we only have a simple rule, but we want to have a simple interface, where we can scale multiple events, and add more business processing. 

- We would like to have an asynchronous protocol for controlling our logs. We plan to have logs comming in from multiple services, and we plan to add more services as stakeholders and product owners add start to add more feature requirements. 

- We would like to store our data in both a relation data store (SQL based) and an object based data store (NoSQL). We have relational data inbetween our customers and cars, while we have object based data for our logs

```

[<img src="./SI_Diagram.jpg">]
According to the requirements from the customer we have tried to implement an application that matches the requirement of the user. 
