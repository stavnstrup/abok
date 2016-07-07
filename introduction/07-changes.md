---
title: New Features and Important Changes in NAF
---

There are several new features in NAF, they include:

* The replacement of the Version 3 meta-model with the NATO version of MODEM.
* A Grid representation of viewpoints.
* An Architecture Methodology.

# Meta-Model

This replacement ensures that NAF development keeps pace with DoDAF and achieves alignment of MODAF with NAF. It resolves inconsistencies between Chapters, thus mitigating the need for tool developers to cherry-pick and interpret requirements to overcome incoherence.

# Grid Representation

The NAF is a two-dimensional classification scheme for descriptive representations of an Enterprise is called a Grid. The grid representation has been developed which organises the various viewpoints more logically and consistently to aid architects, as indicated below:


{%include naf4grid.html %}

**Figure Chapter‑3: NAF Viewpoints in a grid structure**

The grid approach presents the NAF viewpoints by Model Kind (horizontal axis) and by layers of abstraction (vertical). A Model Kind is defined in ISO42010 as “conventions for one type of modelling”. NAF identifies a set of broad Model Kinds:

> a. Classification/Ontology – taxonomies of concepts such as capabilities, services, etc.
>
> b. Structure – how elements are assembled (enterprises, nodes, resources, etc.).
>
> c. Connectivity – everything from high-level capability dependencies to detailed system connectivity.
>
> d. Behaviour – how things work.

-   Activities – process flows and decomposition.

-   States – allowable state transitions.

-   Sequences – how things interact and in what order.

> e. Information – what information/data is used, and how it is structured.
>
> f. Constraints – rules that govern the enterprise, nodes, resources, etc.
>
> g. Programme – project timelines and milestones affecting the elements in the architecture.

Each cell at the intersection of each row and model kinds is a Viewpoint (usually an existing NAF 3 Viewpoint). The new approach is information-centric. It divides the framework up into categories of architectural information rather than how the information is presented.


{%include figure.html url="../images/no-fig-yet.svg" description="Figure Chapter‑4: Architecture Workflows" %}

# Architecture Methodology

A new methodology is defined in Chapter 2 to provide:

*   Terms and concept for architecting,
*   A foundation for architecture activities,
*   Architecture principles,
*   Architecture activities at Enterprise and Project levels,
*   Architecture repositories and libraries to formalise architecture-based references, allow reuse and improve interoperability between communities,
*   NATO application of NAF V4 for Mission Threads and Capability Planning,
*   And a complete example of architecture development.
