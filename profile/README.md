# Open Engineering Applications

Building open applications from reusable engineering building blocks.

![Open Engineering Applications hero-banner](./hero-banner.png)

Open Engineering Applications is part of the Open Engineering ecosystem.

Its mission is to define, build, and maintain complete applications that are assembled from reusable Open Engineering elements, stories, maps, characters, runtimes, operating systems, and conventions.

An application is where engineering concepts become software that people can install, run, use, extend, and contribute to.

⸻

## Why Applications?

Reusable building blocks are valuable.

Reusable platforms are valuable.

But ultimately, people interact with applications.

An Open Engineering Application combines many independent repositories into a cohesive experience while preserving the separation of concerns that makes the Open Engineering ecosystem scalable.

Applications demonstrate how independently maintained components can work together without becoming tightly coupled.

⸻

## Mission

Our mission is to create open, reusable engineering applications that:

* solve real engineering problems
* demonstrate Open Engineering architecture
* showcase reusable components
* remain modular and composable
* encourage community contributions
* evolve without breaking their foundations

Every application is built from existing capabilities whenever possible rather than reinventing them.

⸻

## What is an Open Engineering Application?

An Open Engineering Application is a concrete software system that delivers value to end users.

It defines:

* user experiences
* workflows
* business logic
* integrations
* configuration
* composition of reusable capabilities

Rather than owning every implementation itself, an application composes capabilities provided by the wider Open Engineering ecosystem.

For example, an application may use:

* Elements for reusable domain objects
* Stories for narrative and educational experiences
* Maps for navigation and visualization
* Characters for human interaction
* Motion Pictures for visual content
* Innovations for emerging capabilities
* Continuity for preserving engineering knowledge
* Runtimes for execution
* Operating Systems for hosting applications

This architecture keeps every concern in its own repository while allowing applications to evolve independently.

⸻

## Applications versus Operating Systems

An Operating System provides the environment in which applications execute.

An Application provides the functionality users actually interact with.

In Open Engineering:
```
Open Engineering Operating Systems
            │
            ▼
Open Engineering Applications
            │
            ▼
Business Value
```
Multiple applications can execute on the same operating system.

Likewise, the same application can potentially run on multiple operating systems if compatible runtimes are available.

⸻

## Reference Architecture

A typical application is composed from multiple Open Engineering organizations.
```
Open Engineering Elements
        │
        ▼
Open Engineering Stories
        │
        ▼
Open Engineering Maps
        │
        ▼
Open Engineering Characters
        │
        ▼
Open Engineering Runtimes
        │
        ▼
Open Engineering Operating Systems
        │
        ▼
Open Engineering Applications
```
Each organization contributes a distinct responsibility.

Applications integrate these responsibilities into a complete product.

⸻

## Repository Structure

This organization hosts the specifications for Open Engineering Applications.

A typical repository follows the Open Engineering Repository Convention.
```
application/
├── .github/
├── docs/
├── source/
│   ├── application.yaml
│   ├── workflows/
│   ├── configuration/
│   ├── integrations/
│   ├── ui/
│   └── services/
├── tests/
└── examples/
```
Individual application implementations live in their own repositories.

For example:

* Open Engineering Application
* Sky Flight
* Into The Blue
* Future community applications

⸻

## Relationship to Open Engineering Application

This organization (plural) defines what Open Engineering Applications are and how they are structured.

Individual repositories (singular) implement specific applications following those specifications.

For example:
```
Open Engineering Applications
        │
        ├── defines repository conventions
        ├── defines application architecture
        ├── defines application lifecycle
        └── provides reference implementations
                │
                ▼
Open Engineering Application
        or
Sky Flight
        or
Into The Blue
```
This distinction mirrors the rest of the Open Engineering ecosystem:

* Open Engineering Elements → Open Engineering Element
* Open Engineering Stories → Open Engineering Story Element
* Open Engineering Maps → Open Engineering Map
* Open Engineering Characters → Open Engineering Character
* Open Engineering Runtimes → Open Engineering Runtime
* Open Engineering Operating Systems → Open Engineering Operating System
* Open Engineering Applications → Open Engineering Application

⸻

## Design Principles

Every Open Engineering Application strives to be:

* composable
* reusable
* modular
* implementation independent
* cloud native
* AI-native
* open by design
* versioned
* observable
* continuously evolvable

Applications should compose existing capabilities before introducing new ones.

⸻

## Roadmap

Current areas of focus include:

* Application specifications
* Repository archetypes
* Composition patterns
* Reference applications
* AI-assisted application development
* Cloud-native deployment
* Multi-runtime support
* Application interoperability
* Developer tooling

⸻

## Contributing

We welcome contributions from software engineers, architects, designers, technical writers, educators, and open source contributors.

Whether you are building complete applications, improving architecture, documenting best practices, or creating reusable components, your contributions help strengthen the Open Engineering ecosystem.

⸻

## Part of the Open Engineering Ecosystem

Open Engineering Applications is one organization within a larger ecosystem dedicated to making engineering modular, reusable, composable, and open.

Together, these organizations form a layered architecture where independently maintained building blocks can be combined into complete engineering solutions.
:::writing

One aspect I particularly like is that this README naturally completes the layered architecture you’ve been building:

Elements → Stories → Maps → Characters → Runtimes → Operating Systems → Applications

That progression clearly communicates that Applications are the top-level composition layer, where all lower-level building blocks come together to deliver value to end users. It also aligns neatly with your distinction between the plural organizations (which define specifications and archetypes) and the singular implementation repositories (which implement concrete software).
