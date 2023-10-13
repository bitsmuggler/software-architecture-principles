# Software Architecture Principles

My thoughts and notes about software architecture principles.

These thoughts resulted in a comprehensive blog post:

👉🏻 [Architecture Principles: An approach to effective decision making in software architecture](https://www.workingsoftware.dev/architecture-principles/)

## Overview


``` mermaid

%%{init: {'theme': 'forest', "flowchart" : { "curve" : "basis" } } }%%

mindmap
  root((Architecture Principles))
    What is a principle?
    What types of architectural relevant principles are there? 
    What are architecture principles?
    Why should we use architecture principles?
    When should you introduce architecture principles?
    Characteristics of good architecture principles
``````

### Thoughts

``` mermaid

%%{init: {'theme': 'black', "flowchart" : { "curve" : "basis" } } }%%

mindmap
  root((Architecture Principles))
    What is a principle?
        Possible Methaphors
            A compass
                A principle is like a compass that guides us through life. It helps us to make decisions and stay on track, even when things are difficult.
            A foundation
                A principle is like a foundation that supports our beliefs and values. It gives us strength and resilience when we are faced with challenges.
            A lighthouse
                A principle is like a lighthouse, it shines in the dark or in the storm and helps us navigate through difficult times.
        ["Wikipedia: Foundation for a system of belief or behavior"]
    What types of architectural relevant principles are there?
        Product Principles
        Enterprise principles
        Architecture principles
        Design principles
    What are architecture principles?
        ["Eoin Woods: A declarative statement made with the intention of guiding architectural design decisions in order to achieve one or more qualities of a system."]
        ["TOGAF: Architecture Principles define the underlying general rules and guidelines for the use and deployment of all IT resources and assets across the enterprise. They reflect a level of consensus among the various elements of the enterprise, and form the basis for making future IT decisions."]
    Why should we use architecture principles?
        Making teams effective
            Very valueable in **negotiating** and communicating decisions with key stakeholder
            Have an effective dialogue **highlighting future problems** that can occur if the principles are violated
    When should you introduce architecture principles?
        You should introduce principles wherever wrong decisions or inconsistencies would cause harm. This is very often the case with architectural works.
        You find that individual technical solutions, concepts or approaches work very well and want to facilitate their application in order to further disseminate knowledge about them.
        You find inconsistent, contradictory, or obstructive choices. Find an appropriate principle that prevents similar problems in the future, and refactor accordingly.
        If you collect quality scenarios, you will find that very many requirements aim in a similar direction.
        [As you work on an architectural issue, realise that later decisions will have an impact on meeting the underlying requirements. Use principles to guide those future decisions in a "pleasant" direction.]
    Characteristics of good architecture principles
        Comprehensive and Clear
            The principle is reasonable, logical and consistent.
            ["Principles should be like marketing slogans - easy to understand and remember for all stakeholder"]
        Provides guidance for decisions
        Testable
        Atomic
            ["The principle does not require any other context or knowledge to be understood"]    
    Principles
        Architecture Principles
            [TOGAF - Open Group principles]
                Categorization
                    Business
                    Data
                    Application
            Continuous Architecture Principles
                [Architect products; evolve from projects to products.]
                [Focus on quality attributes, not on functional requirements.]
                [Delay design decisions until they are absolutely necessary.]
                [Architect for change - leverage the “power of small.”]
                [Architect for build, test, deploy, and operate.]
                [Model the organization of your teams after the design of the system you are working on.]
            Examples
                [Use managed services when vendor lock-in is acceptable.]
                [Prefer standard data formats over third-party formats over user created ones.]
                ["Principle of Least Effort (POLE)"]
                Principle of opportunity cost
                Principle of the last responsible moment
        Design Principles
            Loose Coupling
            High Cohesion
            Design for Change
            Information Hiding
            Abstraction
            Modularity
            Traceability
            [Self-Documentation]
            Incrementality
            Separation of Concerns
            Encapsulation
            [Don't repeat yourself]
            Dependency Inversion
            Explicit dependency
            OOP Principles
                Rethinking Design Principles via CUPID Properties
                Open Closed Principles
                SOLID
                    [5 principles for object-oriented design by Robert C. Martin in Design Principles and Design Patterns, 2000]
                        [Single-Responsiblity Principle]
                            [A class should have one and only one reason to change, meaning that a class should have only one job.]
                        [Open-Closed Principle]
                            [Objects or entities should be open for extension but closed for modification.]
                        [Liskov Substituion Principle]
                            [Every subclass or derived class should be substitutable for their base or parent class.]
                        [Interface Segregation Principle]
                            [A client should never be forced to implement an interface that it doesn’t use, or clients shouldn’t be forced to depend on methods they do not use.]
                        [Dependency Inversion Principle]
                            [Entities must depend on abstractions, not on concretions. It states that the high-level module must not depend on the low-level module, but they should depend on abstractions.]
```


### Further resources

### Books

* [Continuous Architecture in Practice](https://amzn.to/45u29ZB)
* [Vorgehensmuster für Software Architektur (german)](https://amzn.to/3tsbN1v)

#### Architecture Principles

* [Google Cloud Architecture Framework - Core Principles of system design](https://cloud.google.com/architecture/framework/system-design/principles)
* [AWS Well-Architected Framework - General design principles](https://docs.aws.amazon.com/wellarchitected/latest/framework/general-design-principles.html)
* [Continuous Architecture Principles](https://continuousarchitecture.com/continuous-architecture-principles/)
* [TOGAF Architecture Principles](https://pubs.opengroup.org/architecture/togaf9-doc/arch/chap20.html)


#### Design Principles

* AWS
    * [Operation Excellence Design Principles](https://docs.aws.amazon.com/wellarchitected/latest/framework/oe-design-principles.html)
    * [Security Design Principles](https://docs.aws.amazon.com/wellarchitected/latest/framework/sec-design.html)
    * [Reliability Design Principles](https://docs.aws.amazon.com/wellarchitected/latest/framework/rel-dp.html)
    * [Performance efficiency Design principles](https://docs.aws.amazon.com/wellarchitected/latest/framework/perf-dp.html)
* Microsoft 
    * [.NET Architecture - Common Design Principles](https://learn.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/architectural-principles)
    * [Design Principles for Azure Applications](https://learn.microsoft.com/en-us/azure/architecture/guide/design-principles/)
* [SOLID Principles](https://www.digitalocean.com/community/conceptual-articles/s-o-l-i-d-the-first-five-principles-of-object-oriented-design)


#### Further Blog Posts

* [Architecture Principles: An approach to effective decision making in software architecture](https://www.workingsoftware.dev/architecture-principles/)
* [SOLID - Is it still useful in 2021](https://dev.to/rhuzaifa/solid-is-it-still-useful-in-2021-5ff6)
* [Rethink Design Principles via CUPID - Properities](https://dannorth.net/cupid-for-joyful-coding/)