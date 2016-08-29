---
title: New Features and Important Changes in NAF
---

There are several new features in NAF, they include:

* The replacement of the Version 3 meta-model with the NATO version of MODEM.
* A Grid representation of viewpoints.
* An Architecture Methodology.

# Meta-Model Replacement

This replacement ensures that NAF development keeps pace with DoDAF and achieves alignment of MODAF with NAF. It resolves inconsistencies between Chapters within NAF v3, thus mitigating the need for tool developers to cherry-pick and interpret requirements to overcome incoherence.

# Grid Representation

The NAF v4 formalism is presented as a grid representation to organise the various
viewpoints (rows) and perspectives (columns), logically and consistently to aid
architects, as shown below:

{%include figure.html url="naf4-grid.svg"  description="NAF Viewpoints in a grid structure" %}


The grid approach presents the NAF view types (cells) by viewpoints (rows) and by perspectives (columns).

Table 1.1 lists the NAF v4 viewpoints. The perspectives as shown in the grid are as
follows:

1. Classification/Ontology - taxonomies of concepts such as capabilities, services, etc.

2. Structure - how elements are assembled (enterprises, nodes, resources, etc.).

3. Connectivity - everything from high-level capability dependencies to detailed system connectivity.

4. Behaviour - how things work.

   -   Processes - processes, activities, functions flows and decomposition.

   -   States - allowable state transitions.

   -   Sequences - how things interact and in what order.

5. Information - what information/data is used, and how it is structured.

6. Constraints - rules that govern the enterprise, nodes, resources, etc.

7. Programme - Programme, project timelines and milestones affecting the elements in the architecture.
{: type="a"}


The new approach is information-centric.

# Architecture Methodology

A new methodology is defined in Chapter 2 to provide:

*   Terms and concept for architecting,

*   A foundation for architecture activities,

*   Architecture principles,

*   Architecture activities at Enterprise and Project levels,

*   Architecture repositories and libraries to formalise architecture-based
    references, allow reuse and improve interoperability between communities,

*   The application of NAF V4 for Mission Threads and Capability Planning, for
    NATO (described in Annex C to chapter 2)

*   A complete example of architecture development.
