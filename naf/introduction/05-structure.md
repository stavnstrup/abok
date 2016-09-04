---
title: The Structure of the NATO Architecture Framework
---


The Framework will ensure that architectures developed according to this framework
can be understood, compared[^ala] , justified and related across many organisations,
including NATO and other National Defence initiatives.

[^ala]: Chapter 2 explains analysis of alternatives, trade-off analysis and support for decision making

The traditional approach to development has often resulted in a collection of
disparate systems procured and provided by the Nations that perhaps could be
interconnected but were never interoperable such that the combination was aligned
with an organisation’s goal.

As a result of this situation systems failed to bring the expected benefits like
interoperability, speed of operation, cost reduction and flexibility to change.

The solution to this is to think strategically and understand an organisation’s overall
objectives. From these objectives the actual content and the structure of the systems
can be derived. The rules, constraints and guidelines on how to develop capabilities
and systems including information systems to support the business, is a central
element for architects.

Architectures have to transform strategy into the content of manageable and
executable change.

The NAF complements the ISO/IEC 42010 conceptual model to include enterprises
and phases of an enterprise. In this way Architectures can be used to show how they
develop and undergo change over time through a process of transformation.

NAF v4 introduces the concepts of Logical and Physical viewpoints or perspectives
on an architecture.

The NAF Viewpoints retain equivalence with the NAF v3 Views[^views3plus]  , albeit with names
that better describe their purpose, as indicated in Table 1-1: Mapping of NAF v3
Views to NAF v4 Viewpoints:

[^views3plus]: Post NAF v3, the term ‘View’ is used to refer to a populated Viewpoint within a particular architecture, in accordance with ISO/IEC/IEEE 42010.)


**Table : Mapping of NAF v3 Views to NAF v4 Viewpoints**

| **NAF v3 View**         | **NAF v4 Viewpoint**        |
|-------------------------|-----------------------------|
| Capability (NCV)        | Concepts (C)                |
| Service-Oriented (NSOV) | Service (S)                 |
| Operational (NOV)       | Logical (L)                 |
| Systems (NSV)           | Physical Resource (P)       |
| All Views (NAV)         | Architecture Management (A) |


Note: This table must not be read as a strict mapping between NAF v3 views
and NAF v4 viewpoints.

* A Logical viewpoint the logical components of the architecture without
  specifying their physical type – that is it leaves the implementation
  options open, even to the level of allowing human or machine solutions
  to a particular problem. It may also be used to present a view of an
  existing system to allow stakeholders to understand the structure and
  behaviours free of the physical complexity.

* Physical viewpoints are used to describe patterns or provide a detailed
  view of a system.

It is worth noting that the terms Logical and Physical have different meanings in other
engineering domains.

In NAF v4 the term Logical is used to denote the realisation of capabilities (defined in
the Concepts viewpoint) that is still independent of a solution. The Logical viewpoint
(still and partly) describes the problem space.

The term Physical is used to denote the realisation of logical entities (defined in the
Logical viewpoint) by a solution. Thus, the Physical viewpoint describes the solution
space.

In some engineering domains, the solution space is defined by two levels:

* a Logical level defining the principle of the solution

* a Physical level defining the concrete / detailed solution

# Definition of Viewpoint

ISO42010 defines an Architecture Viewpoint as “An architecture view expresses the
architecture of the system-of-interest in accordance with an architecture viewpoint (or
simply, viewpoint). There are two aspects to a viewpoint: the concerns it frames for
stakeholders and the conventions it establishes on views”. The NAF represents a
number of views according to the following viewpoints:

* Concepts viewpoint – enterprises and their capabilities.

* Logical viewpoint – solution-independent specifications of how
  capabilities and services are orchestrated for particular scenarios.

* Service viewpoint – how capabilities are packaged for re-use across the
  enterprise.

* Physical Resource viewpoint – high-level design, specifying the
  required structure and interactions between systems, people and
  organisations.

* Architecture Management viewpoint – who produced the architecture,
  when and for whom? Also specifies how the Viewpoints fit together and
  what concerns they address.

These are described in Chapter 3 along with the Ontology and View Taxonomy.

The viewpoints describe the problem and/or a solution with regards to several
concerns or perspectives:

1. The Concepts and Service viewpoints are used to describe capabilities
   and services that are then re-used throughout the architecture.

2. The Logical viewpoint specifies how capabilities and services are
   needed to meet a given requirement or scenario.

3. The Physical viewpoint describes how those capabilities and services
   are implemented and how they interact.

4. The Architecture Management viewpoint specifies how the other
   viewpoints fit together and what concerns they address.
{: type="a"}
