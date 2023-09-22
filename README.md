# Architecture Principles

My thoughts and notes about architecture principles.

```mermaid
mindmap
  root((Architecture Principles))
    What is a principles?
        ["Foundation for a system of belief or behavior"]
    What are architecture principles?
        ["Eoin Woods: A declarative statement made with the intention of guiding architectural design decisions in order to achieve one or more qualities of a system."]
        ["TOGAF: Architecture Principles define the underlying general rules and guidelines for the use and deployment of all IT resources and assets across the enterprise. They reflect a level of consensus among the various elements of the enterprise, and form the basis for making future IT decisions."]
    Why should we use architecture principles?
        Making teams effective
            Very valueable in **negotiating** and communicating decisions with key stakeholder
            Have an effective dialogue **highlighting future problems** that can occur if the principles are violated
    Characteristics of good architecture principles
        Comprehensive and Clear
            The principle is reasonable, logical and consistent.
            ["Principles should be like marketing slogans - easy to understand and remember for all stakeholder"]
        Provides guidance for decisions
        Testable
        Atomic
            ["The principle does not require any other context or knowledge to be understood"]    
    Architecture Principes
        Architecture Principles
            ["Principle of Least Effort (POLE)"]
            Principle of Opportunity Cost
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
        Design Principles
            SOLID
            Separation of Concerns
            Encapsulation
            DRY Don't repeat yourself
            Dependency Inversion
            Explicit dependency
            Single responsibility
            Open Closed
```


### Further resources

* [Continuous Architecture Principles](https://continuousarchitecture.com/continuous-architecture-principles/)
* [TOGAF Architecture Principles](https://pubs.opengroup.org/architecture/togaf9-doc/arch/chap20.html)