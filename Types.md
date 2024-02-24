# Types of Design Patterns

## Overview

* design patterns vary in their granularity, level of abstraction and how they relate to one another
* some patterns are often used together
    * composite is often used with iterator or visitor
* some patterns are alternatives
    * prototype is often an alternative to Abstract Factory
* some patterns result in similar designs even though the patterns have different intents
    * the structures diagrams of composite and decorator are similar
* the 23 design patterns that we will study all have several known applications and are on a middle level of generality
    * they are divided into three types(gang of four)
        * organized by purpose (reflects what a pattern does)
    * creational - concern the process of object creation.
    * structural - deal with teh composition of classes or objects
    * behavioral - charaterize the ways in which classes or objects interact and distribute responsibility
* design patterns can also be organized by scope (Whether the pattern applies primarily to classes or to objects)
    * class patterns deal with relationships between classes and their subclass
        * these relationships are established through inheritance
    * object patterns deal with object relationships, which can be changed at run-time and are more dynamic
        * describe how objects can be composed into large structures using object composition or by including objects within other objects

### Creational Patterns

* a program should no depend on how objects are created and arranged
* creational design patterns provide a way to create objects
* in Java, the simplest way to create an instance of an object is by using the new operator
    * fred = new Fred(); // instance of Fred class
* creational design patterns abstract the instanctiation process
    * the creation logic is hidden
    * encapsulates knowledge about which concrete classes the system uses.
    * programmer may call a method or use another object, rather than instantiating objects directly using the new operator.
* all the system at loge knows about the objects is their interfaces as defined by abstract classes
    * gives the programmer a lot of flexibility in what gets created it, how it gets created, and when
    * lets you congigure a system with "product" objects that vary widely in structure and functionality
    * configuration can be static (compile-time) or dynamic (at run-time)
* sometimes creational patterns are competitors
    * there are cases when either Prototype or Abstract Factory could be used profitably
* sometimes creational pattern are complementrary
    * builder can use one of the other patterns to implement which components get built
    * prototype can use Singleton in its implementation
* creational class patterns defer some part of object creation to subclasses
* creational object patterns defer it to another object
* there are 5 creational patterns that we will study
    * will highlight their similarities and differences

### Structural patterns

* describes how classes and objects can be combined to form larger structures
    * utilizes inheritance to compose interfaces or implementations
    * structural object patterns decribe ways to assembles objects
    * e.g. complex user inheritance and accounting data
* these design patterns concern class and object composition
* the composite design pattern
    * describes how to build a class hierarchy made up of classes for 2 kinds of objects
* the proxy design pattern acts as a convenient surrogate or placeholder for another object.
    * provide a level of indirection to specific properties of objects
* there are seven structural patterns that we will study
    * will highlight their similarities and differences

### Behavioral Patterns

* these design patterns are specifically concerned with communication objects
    * characterize complex control flow that is difficult to follow at run-time
    * Shift the focus away from of control to let you concentrate just on the way objects are interconnected
* these patterns increase flexibility in carrying out this communication
* provide solutions on how to segregate objects to be both dependent and independent
* concerned with algorithms and the assignment of responsibilities between objects
* behavioral class patterns use inheritance to describe algorithms and flow of control
    * the template method is an abstract definition of an algorithm
        * defines an algorithm step by step
        * a subclass fleshes outs the algorithm by defining the abstract operations
* behavioral object patterns describe how a group of objects cooperate to perform a task that no single object can carry out alone
    * Uses object composition rather than inheritance
    * the mediator pattern uses a mediator object for peer object communication
        * mediator provides the indirection needed for loose coupling(coupling all about dependencies, tightly coupled systems are maintained u change 1 class another class effected u wanna avoid tightly coupled systems or tightly coupled objects related to co-eshoins types responsibility focus of an object, High co-iesion mean that object highly focused its not all over the place, that object would be too many responsibility and again its related to the maintainence fixing bugs adding new code its much harder to do that and the system that tightly coupled in very local )
* there are eleven behavioral patterns that we will study the command the interpretter many more behaviour for us 