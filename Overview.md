# Overview

* We all talk about the way that we do things in our everyday work, hobbies, and home life and recognize repeating patterns all the time.

* these "patterns" can also happen in programming (when you write code you end up repeating yourself quite a bit. So when you repeat yourself these are patterns and if you're going to repeat yourself you can identify a really good common solution to these patterns.)

* Software engineers face common problems during the development of variou software programs (So software engineers face common problems during development of various software programs and you should know this as you're writing code. A lot of times you encounter the same problems. )
    * When we tell a colleague how we accomplish tricky bit of programming so that the colleague doesn't have to recreate it from scratch

* in the past, there were no standards to instruct them how to design and proceed
    * becomes a significant problem when a new member(experienced or unexperienced) joins a team and is assigned to do a task
    * takes a lot of effort to become familiar with the existing product

* design patterns are aimed towards Object-Oriented Programming languages
* designing object-oriented software is hard, and designing reusable object-oriented software is even harder
    * design patterns addresses the above issues and makes a common platform for all developers
    * they help provide a standard and give direction on how to solve common software problems


## Definitions

* "Design patterns" are recurring solutions to design problems you see over and over [Smalltalk Companion]
* "Design patterns constitute a set of rules describing how to accomplish certain tasks in the realm of software development." [Pree 1994].
* "Design patterns focus more on reuse of recurring architectural design themes, while frameworks focus on detailed design... and implementation." [Coplien and Schmidt, 1995] (this definition is kind of distinguishing between frameworks Versus specific design patterns design tend to solve smaller subsets of problems.)
* "A pattern addresses a recurring design problem that arises in specific design situations and presents a solution to it." [Buschmann and Meunier, et al., 1996]
* "Patterns identify and specify abstractions that are above the level of single classes and instances, or of components."[Gamma, Helm, Johnson, and Vlissides, 1993]

### Definitions (summary)

* design patterns represent the best practices used by experienced object-oriented software developers
    * solutions to general problems that software developers faced during software development
    * solutions are obtained by trial and error by numerous software developers over quite a substantial period of time

* design patterns are not just about the design of objects
    * also about interaction between objects
    * include strategies for object inheritance and vontainment
* design patterns can exist at many levels, from very low-level specific solutions to broadly generalized system issues

### History

* the concept of design patterns originated from Christopher Wolfgang Alexander (Austria) who was an architect
    * initially applied to architecture for buildings and towns, but, not computer programming for writing software
* "Each pattern describes a problem which occurs over and over again in our environment, and then describes the core of the solution to that problem, in such a way that you can use this solution a million times over, without ever doing it the same way twice" (Alexander)
* In 1994-95, the "Gang of four" applied Alexander's concept to software development
    * Erich Gamma, Richard Helm, Ralph Johnson and John Vlissides
    * solutions are expressed in terms of objects and interfaces instead of walls and doors
* gang of four published "Design Patterns -- Elements of Reusable Object-Oriented Software (Addison-Wesley, 1995)"
    * applied the idea of patterns to software design -- calling them design patterns
    * described a structure within which to catalog and describe design patterns
    * cataloged 23 such patterns
    * postulated object-oriented strategies and approaches based on these design patterns

* Gang of Four did not create the patterns described in the book
    * they identified patterns that already existed within the software community
    * patterns that reflected what had been learned about high-quality designs for specific problems

### Four Essential Elements

* a design pattern has 4 essential elements
* Pattern name
    * a handle we can use to describe a design problem, its solution, and consequences in a word or 2
    * lets us design at a higher level of abstraction
    * makes it easier to think about designs and to communicate them and their trade-offs to others

* problem
    * explains the problem and its context
    * might describe specific design problems such as how to represent algorithms as objects
    * might describe a class or object structures that are symptomatic of an inflexible design
    * sometimes the problem will include a list of conditions that must be met before it makes sense to apply the pettern

* solution
    * describes the elements that make up the design, theire relationships, responsibilities, and collaborations
    * does NOT describe a particular concrete design or implementaion
        * a pattern is like a template that can be applied in many different situations
        * the pattern provided an abstract description of design problem and how a general arrangement of elements (classes and objects) solves it

* consequences
    * the results and trade-offs of applying the pattern
    * critical for evaluating design alternatives and for understanding the costs and benefits of applying the pattern
    * often concern space and time trade-offs
    * may address language and implementation issues as well
    * includes its impact on a system's flexibility, extensibility, or portability regarding software reuse
