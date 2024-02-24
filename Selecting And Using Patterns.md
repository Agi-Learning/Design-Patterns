# Selecting and Using Design Patterns

## Overview (Software Design Approaches)

* designing software is normally thought of as a process of putting things together
    * a common approach is to look immediately for objects and classes and components and then think about how they should fit together
* a better approach is to use one that is based on design patterns
* start out with a conceptual understanding of the whole in order to understand what needs to be accomplished
* Identify the patterns that are present in the whole
    * think about your problem in terms of the patterns that are present
    * the purpose of the pattern is to define relationship among entities
* start with those patterns that create the context for the others
    * Identify these patterns
* work inward from the context
    * look at the remaining patterns and at any other patterns that you might have uncoverd
    * pick the patterns that define the context for the patterns that would remain
    * Repeat
* finally, refine the design and implement within the context created by applying these patterns one at a time
    * as you refine, always consider the context implied by the patterns
    * the implementation incorporates the details dictated by the patterns
* designing by adding concepts within the context of previously presented concepts is attainable
    * many patterns create robust software because they define contexts within which the classes that implement them can work

### Choosing a Pattern

* with more than 20 design patterns in the catalog to choose from, it might be hard to find the one that addresses a particular design problem
* here are several different approaches to finding the design pattern that is right for your problem
* consider how design patterns solve design problems
    * determine object granularity
    * specify object interface
    * understanding these concepts can help guide your search for the right pattern
* understand the design patterns intent
    * provided with the pattern
    * identify if intent is relevant to your problem
    * you can use the classification scheme (creational, structural, behavioral) to narrow your search
* study how patterns interrelate
    * understanding relationships between design patterns can help direct you to the right pattern or group of patterns
* study patterns of like purpose
    * understand the similarities and differences between patterns of like purpose
* examine a cause of redesign
    * find any issues in your problem that may cause a redesign
    * look at the patterns that help you avoid the causes of redesign
* consider what should be variable in your design
    * the opposite of focusing on the causes of redesign
    * consider what you want to be able to change without redesign
    * the focus here is on encapsulating the concept that varies, a theme of many design patterns

### Using and applying a pattern

* once you have picked a design pattern, how do you use it?
* read the pattern once through for an overview
    * pay particular attention to the applicability and consequences of a pattern to ensure the pattern is right for your problem
* go back and study the structure, participants, and collaborations of the pattern
    * make sure you understand the classes and objects in the pattern and how they relate to one another
* look at sample code to see a concrete example of the pattern in code
    * studying the code helps you learn how to implement the pattern
* define the classes
    * declare their interfaces
    * establish their inheritance relationships
    * define the instance variable that represent data and object references
    * identify existing classes in your application that the pattern will affect, and modify them accordingly
* choose names for pattern participants that are meaningful in the application context
    * useful to incorporate the participant name into the name that appears in the application
    * helps make the pattern more explicit in the implementation
    * e.g. If you use the Strategy pattern for a text composing algorithm, then you might have classes SimpleLayoutStrategy or TextLayoutStrategy
* define application specific names for operations in the pattern
    * use the responsibility and collaborations associated with each operation as guide
    * be consistent in your naming conventions
        * e.g. you might use the "Create" prefix consistently to denote a factory method
* implement the operations to carry out the responsibility and collaborations in the pattern
    * again, look at coding examples

### How not to use a design pattern

* design patterns should not be applied indiscriminately
* often they achieve flexibility and variability by introducing additional levels of indirection
    * can complicate a design and/or cost you some performance
    * a design pattern should only be applied when the flexibility it affords is actually needed
    * the consequences of the design pattern are most helpful when evaluating a pattern's benefits and liabilities