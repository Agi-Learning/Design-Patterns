# Advantages of Design Patterns

## Why use design patterns?

* the most commonly stated reasons for studying and utilizing design patterns are because they enable us to do the following:

* use the best solutions for certain problems faced during software development
    * make it easier to reuse successful designs and architectures (Software reuse)
    * solution have been evolved over a long period of time
    * learning these patterns helps unexperienced developers to learn software design in an easy and faster way
        * get the benefit of learning from the experience of others
        * can get a head start on my problems and avoid gotchas
    * help you to avoid reinventing the wheel

* understand basic object-oriented principles that acheive high quality deisgn
    * keep classes separated and prevent them from having to know too much about one another
    * encapsulation, inheritance, and polymorphism

* improve team communications and individual learning by establishing a common platform
    * design patterns provide a common point of reference during the analysis and design phase of a project
    * allow you to describe your programming approach succinctly in terms that other programmers can easily understand
        * for ex, programmers can refer to a program that uses a single object as the singleton pattern
    * more junior team memebers see that the senior developers who know design patterns have something of value and useful to the junior memebers
        * provides motivation for them to learn some of these powerful concepts

* design patterns give a higher perspective on the problem and on the process of design adn object orientation analysis and design
    * frees you from dealing with the details too early
    * help a designer get a design "right" faster

* improve modifiability and maintainability of code
    * time-tested solutions have evolved into structures that can handle change more readily than what often first comes to mind as a solution
    * easier to understand code -- making easier to maintain
    * Improved documentation resulting from common terminology

## Problems addressed by design patterns

* design patterns solve many of the day-to-day problems object-oriented designers face, and in many different ways

* how to identify the appropriate objects to utilize/create
    * Object-oriented programs are made up of objects
    * object packages both data and the procedures that operate on the data

* how to specify object interfaces
    * every operation declared by an object specifies the operation's name, the objects it takes as parameters, and the operation's return value
    * an object's interface characterizes the complete set of requests that can be sent to the object

    * how to specify object Implementations
        * an object's implementation is defined by its class
        * the class specifies the object's internal data and representation and defines the operations the object can perform

* determining object granularity
    * Objects can vary tremendously in size number
    * can represent everything down to the hardware or all the way up to entire applications
    * design patterns address the above issue
        * the facade pattern describes how to represent complete subsystems as objects
        * the flyweight pattern describes how to support huge numbers of objects at the finest granularities
        * abstract factory and builder yield objects whose only responsibilities are creating other objects
        * visitor and command yield objects whose only responsisbilities are to implement a request on another object or group of objects

## Summary

* reuse existing, high-quality solutions to commonly recurring problems
* establish common terminology to improve communications within teams
* shift the level of thinking to a higher perspective
* decide whether I have the right design, not just one that work
* improve individual learning and team learning
* improve the modifiability/quality of code
* facilitate adoption of improved design alternatives, even when patterns are not used explicitly
* discover alternatives to large inheritance hierarchies