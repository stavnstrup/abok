---
title: The Structure of the NATO Architecture Framework
---

The Framework will ensure that the architectures can be compared (Note: Chapter
2 explains analysis of alternatives, trade-off analysis and support for decision
making) and related across many organisations, including NATO and other National
Defence initiatives.

The traditional approach to development has often resulted in a collection of
disparate systems procured and provided by the Nations that perhaps could be
interconnected but were never interoperable such that the combination was
aligned with an organisation’s goal.

As a result of this situation systems failed to bring the expected benefits like
speed of operation, cost reduction and flexibility to change.

The solution to this is to think strategically and understand an organisation’s
overall objectives. From these objectives the actual content and the structure
of the systems can be derived. The rules, constraints and guidelines on how to
develop capabilities and systems including information systems to support the
business, is a central element for architects.

Architectures have to transform strategy into the content of manageable and executable change.

The NAF complements the ISO/IEC 42010 conceptual model to include enterprises
and phases of an enterprise. In this way Architectures can be used to show how
they develop and undergo change over time through a process of transformation.

NAF v4 introduces the concepts of Logical and Physical architectures.

The NAF Viewpoints retain equivalence with the NAF v3 Views[2], albeit with names that better describe their purpose, as indicated in Table INTRODUCTION-1: Mapping of NAF v3 Views to NAF v4 Viewpoints:

**Table Chapter‑1: Mapping of NAF v3 Views to NAF v4 Viewpoints**

|                         |                             |
|-------------------------|-----------------------------|
| **NAF v3 View**         | **NAF v4 Viewpoint**        |
| Capability (NCV)        | Concepts (C)                |
| Service-Oriented (NSOV) | Service (S)                 |
| Operational (NOV)       | Logical (L)                 |
| Systems (NSV)           | Physical Resource (P)       |
| All Views (NAV)         | Architecture Management (A) |


* A Logical Architecture specifies the logical components of the architecture
  without specifying their physical type – that is it leaves the implementation
  options open, even to the level of allowing human or machine solutions to a
  particular problem. It may also be used to present a view of an existing
  system to allow stakeholders to understand the structure and behaviours free
  of the physical complexity.
* Physical Architectures are used to describe generic solution patterns or provide a detailed view of an
  existing system.

The figure below reflects the main architectural concepts used in the NAF:

{%include figure.html url="../images/no-fig-yet.svg" description="High-Level Representation of NAF Meta-Model" %}

This figure has used ISO 42010 has a starting point but also includes the extensions required to incorporate projects and the enterprise and their relation to stakeholders, as well as the life-cycle relationship with architecture.

### Definition of Viewpoint

ISO42010 defines an Architecture Viewpoint as “An architecture view expresses the architecture of the system-of-interest in accordance with an architecture viewpoint (or simply, viewpoint). There are two aspects to a viewpoint: the concerns it frames for stakeholders and the conventions it establishes on views”. The NAF represents a number of views within a Grid construct that is made up of:

* Concepts – enterprises and their capabilities.
* Logical Specifications – solution-independent specifications of how capabilities and services are
  orchestrated for particular scenarios.
* Service Specifications – how capabilities are packaged for re-use across the enterprise.
* Physical Resource Specifications – high-level design, specifying the required structure and interactions
  between systems, people and organisations.
* Architecture Management – who produced the architecture, when and for whom? Also specifies how the
  Viewpoints fit together and what concerns they address.

These are described in Chapter 3 along with the Ontology and View Taxonomy.

The Viewpoints describe the problem in different levels of abstraction:

1. The Capability, Concepts and Service rows are used to describe capabilities and services that are then
   re-used throughout the architecture.
2. The Logical row specifies how capabilities and services are assembled and orchestrated to meet a given
   requirement or scenario.
3. The Physical row describes how those capabilities and services are implemented and how they interact.
4. The Architecture Management row specifies how the viewpoints fit together and what concerns they
   address.
