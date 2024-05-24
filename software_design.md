

# Software Design markdown 




## What do we mean by coupling and cohesion when discussing structured design?

Coupling and cohesion show the relationships between modules within a system.
> Coupling measures the degree of interdependence between modules, whereas low coupling shows loose connections and high coupling suggests tight connections. High coupling can make systems less maintainable but low coupling is easier for maintenance.

 Cohesion assesses how well the elements within a module are related. High cohesion means elements are strongly related and perform a single task. However, low cohesion means weak relationships and may lead to modules with multiple unrelated tasks, making them harder to understand/maintain. 
 
 ***Ideal situation: high cohesion within modules while minimising coupling between them (to balance modularity and maintainability)***




## What is the difference between top-down and bottom-up design? Which best describes a function oriented design?

**Functional orientated design is more closer to bottom up design.**

*Top-down design starts with the bigger picture of a system and breaks it into smaller parts.*
*Bottom-up design begins with individual components and builds them into a complete system.*

> Function-oriented design involves identifying and designing specific functions required by the system, then integrating them to create larger components. This approach highlights building from the ground up, starting with small, self-contained functions or operations and gradually combining them to achieve higher-level functionalities. Therefore, function-oriented design is best characterised by a bottom-up approach, emphasising its incremental and component-based development methodology.

## In which design methodology would a class diagram be most useful?

A class diagram is most useful in ***object-oriented design***,as classes represent blueprints for objects, encapsulating both data and behaviour. Class diagrams visually represent these classes, their attributes, methods, and relationships and make them needed for understanding system structure and facilitating communication.



## What are the four pillars of object oriented programming? Give a single-sentence description of each.


1. *Encapsulation* involves bundling data and methods within a class, protecting internal workings from external interferences. 
2. *Inheritance* allow code reuse by allowing new classes to inherit attributes/methods from existing ones to establish hierarchical relationships. 
3. *Polymorphism* enables objects to take on different forms, allowing flexibility and dynamic behaviour. 
4. *Abstraction* emphasises representing essential features while hiding implementation details,which simplfies complexity and provides a clear view of the system. 



## What is the strategy pattern? How would its implementation differ between a functional and object oriented system?

The Strategy Pattern allows defining a family of algorithms by encapsulating each one as an object/function and making them **interchangeable**. 
In an *object-oriented system*, it involves defining algorithm classes that implement a common interface. However in a *functional system,* it's achieved using higher-order functions. 

***Ultimately it is between using classes/interfaces vs functions.***

## Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.


> ***I will choose OOD.***

With **Encapsulation**, objects encapsulate payment functionalities, ensuring modularity and easy integration.

Using **Inheritance**, common payment features are inherited, reducing redundancy and promoting code reuse.

Also **Polymorphism** measn the system supports multiple payment methods and processing flows, ensuring compatibility and flexibility.

Lastly OOD allows for **scalability** to the evolving needs of different sectors.




















