# Backend Toolbox
## whatever a backend developer needs to know

###  What is CQRS
    CQRS is about segregating the command and query side of the application architecture. CQRS is based on the Command Query Separation (CQS) principle which was suggested by Bertrand Meyer. CQS suggests! that we divide the operations on domain objects into two distinct categories: Queries and Commands:

![Alt text](media/cqrs-vs-cqs.png)

    Queries return a result and do not change the observable state of a system. Commands change the state of the system but do not necessarily return a value.  

[CQRS and Event Sourcing in Java](https://https://www.baeldung.com/cqrs-event-sourcing-java) 
