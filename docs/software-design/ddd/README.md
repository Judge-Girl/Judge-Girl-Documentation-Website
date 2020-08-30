# Domain Driven Design

For those who are not familiar with Judge Girl, see [Understand Judge Girl's Domain](domain/) to get much easier explanation.

Here we are focusing on the methodology applied in DDD.


## Domain Class Diagram


Our Judge Girl's domain can be directly mapped from the domain's language into the class diagram as below. 

![Class Diagram](https://i.imgur.com/48a5AIf.png)
> [View Class Diagram](https://i.imgur.com/48a5AIf.png)

<TODO add Judge-Spec to class diagram>

Note that I've grouped those classes by colors, where each color stands for a [bounded context](https://martinfowler.com/bliki/BoundedContext.html).
I also labeled the classes with stereotypes so as to emphasize that
which are [aggregates](https://martinfowler.com/bliki/DDD_Aggregate.html) or [entities](https://martinfowler.com/bliki/EvansClassification.html).


Since there are too many terminologies in an Online Judge System, 
DDD is a great approach to reduce the communication gap among those terms, 
because it practices [Ubiquitous Language](https://martinfowler.com/bliki/UbiquitousLanguage.html).
As you can see in the diagram, all the core terms are presented. All the codes should follow these terms.


---

Next: [System Architecture](software-design/system-architecture/)  






