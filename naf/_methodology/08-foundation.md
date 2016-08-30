---
title: Foundation for Architecting
---

This section describes the common methodological elements necessary to
elaborate either Enterprise or project Architecture Frameworks.

These elements are related to activities and architecture data:

-   Architecture principles

-   Architecture capabilities

-   Architecture patterns

-   Architecture assets

-   Organisation for architecting

# Architecting principles (foundation for best practices)

The approach described in this section for establishing architecture
principles is significantly based on the book written by Danny
Greefhorst and Erik Proper \[Greefhorst, 2011\].

## Overview

![](./media/image16.jpeg){width="459" height="332"}

Figure ‎2‑15: Architecture principles definition and management activities

-   The process starts with the determination of the drivers, which are
    the foundation for architecture principles;

-   In subsequent sub-processes the architecture principles themselves
    are determined, specified, classified, validated and applied;

-   The next sub-process is using architecture principles to determine
    whether activities comply with the architecture;

-   The final sub-process intends to handle changes to the architecture,
    which may restart the initial sub-process.

## Definitions for architecture principles

-   NORMATIVE PRINCIPLE: A declarative statement that normatively
    prescribes a property of something.

-   CREDO: A normative principle expressing a fundamental belief.

-   DESIGN PRINCIPLE: A normative principle on the design of
    an artefact. As such, it is a declarative statement that normatively
    restricts design freedom.

-   ARCHITECTURE PRINCIPLE: A normative principle on the orientation
    towards an effective artefact.

## Description of sub-processes

a.  Define drivers where the relevant inputs for determining
    architecture principles are collected from the enterprise and
    project motivation data, such as the goals and objectives,
    opportunities, issues and risks.

    -   Drivers are ideally defined outside the scope of the
        architecture activities (ideally need to be gathered explicitly
        before architecture principles can be identified);

    -   Drivers that are not explicitly documented may have to be
        elicited from stakeholders.

    -   Architects have to ensure that the definitions of these drivers
        are current, and to clarify any areas of ambiguity.

    -   The exact nature of the goals depends on the exact scope and
        context of the architecture engagement.

    -   The goals and issues are the basic drivers that should
        be addressed. Others may be added in later iterations.

    -   Having identified the types of drivers, the next step is to
        determine which information on these drivers is needed in order
        to determine the architecture principles.

    -   Validate the drivers with the stakeholders (What may seem a
        driver for one stakeholder, may seem irrelevant for
        someone else).

    -   The final step in the determination of drivers is their explicit
        specification in the form of an architectural requirement. This
        results in a list of statements with a unique identification
        that is the basis for the determination of
        architecture principles. It thereby enables traceability from
        drivers to architecture principles, as well as requirements
        management of these drivers.

b.  Determine principles where the drivers are translated to a list
    of (candidate) architecture principles. At this stage the
    architecture principles can be considered credos.

    -   Generate candidate principles: generates a list of candidate
        architecture principles that address the drivers.

    -   Select relevant principles: selects those architecture
        principles that are relevant to the specific architectures.

    -   Formulate principle statements: specialises or generalises the
        candidate architecture principle statements into the proper
        abstraction level.

c.  Specify principles where the candidate principles are specified in
    detail, including their rationale and implications. This
    sub-process translates architecture principles from credos
    to norms.

    After the architecture principles have been determined they need to be
    specified in more detail. Further detailing of the architecture
    principle is a prerequisite for actually using it to restrict design
    freedom.

d.  Classify principles where architecture principles are classified in
    a number of dimensions to increase their accessibility.

    -   After the architecture principles have been specified it is
        useful to classify them along the dimensions that were described
        in the previous sub-process to ease their accessibility
        and maintainability.

    -   The dimensions proposed are type of information, scope,
        genericity, details level, stakeholder, transformation, quality
        attribute, meta-level and representation.

e.  Validate and accept principles where architecture principles, their
    specifications and classifications are validated with relevant
    stakeholders and formally accepted.

    Quality criteria that can be used to determine the quality of the
    architecture principles. The quality criteria generally proposed are:
    specific, measurable, achievable, relevant and time framed. For sets
    of architecture principles the quality criteria are: representative,
    accessible and consistent. The review process as well as the criteria
    should, however, be customised and refined to the organisational
    ontext.

f.  Apply principles where architecture principles are applied to
    construct models and derive decisions in downstream architectures,
    requirements and applications.

    Using architecture principles requires a good understanding on the
    artefacts that are impacted by them.

g.  Manage compliance where architects ensure that the architecture
    principles are applied properly, and dispensations for deviations
    may be given.

    -   Every architecture principle can be scored on a scale, that
        could look like:

        i.  Non conformant: some part of the specification of the
            artefact is not in accordance with the
            architecture principle.

        ii. Potentially compliant: there is not enough specified in the
            artefact in order to determine whether it is in accordance
            with the architecture principle.

        iii. Compliant: everything specified in the artefact is in
             accordance with the architecture principle, but some
             relevant implications of the architecture principle are
             missing in the artefact.

        iv. Potentially conformant: everything specified in the artefact
            is in accordance with the architecture principle, but there
            is not enough specified in order to determine that all
            relevant implications of the architecture principle are
            embedded in the artefact.

        v.  Fully conformant: everything specified in the artefact is in
            accordance with the architecture principle, and all relevant
            implications of the architecture principle are embedded in
            the artefact.

h.  Handle changes where the impact of all sorts of changes on the
    architecture principles is determined and new method iterations
    may be initiated.

    A change management process is needed to guide the organisation in
    handling all these drivers for change. The most important part of such
    a process is a classification scheme of types of changes that provides
    guidance on the appropriate steps to take. Also, there should be a
    standard periodic architecture refreshment cycle in which changes can
    be incorporated. See the “Decide on architecture change stage of the
    NAV v4.

## Architecture Principles in NAF v4

The Architecture activities for both enterprise and projects consist of 8 stages. These
stages are all concerned with architecture principles.

They are first architecture principles to be applied in the stage
dealing with establishment of the architecture landscape (AL), reviewed
and extended in the architecture vision (AV) and checked during the
architecture description and evaluation stages (AD & AE).

Changes to them are handled during the stage dealing with the decisions
on the architecture change (AC).

The establishment of the architecture landscape builds the foundation
for the architecture and is where the main architecture principles are
described.

Architecture principles are positioned as derivatives of enterprise
principles, which should be defined outside the architecture processes.

However, depending on how such principles are defined and promulgated
within the enterprise, it may be possible for the set of architecture
principles to also restate, or cross-refer to a set of enterprise
principles, enterprise goals, and strategic enterprise drivers defined
elsewhere within the enterprise.

These principles are derived and adapted for the architecture activities
in the projects according to the architecture motivation data in these
projects.

The architect normally needs to ensure that the definitions of these
enterprise and project principles, goals and strategic drivers are
current, and to clarify any areas of ambiguity.

The architecture principles are identified and established after the
organisational context is understood and a tailored architecture
framework is in place in the enterprise and in the projects.

Architecture principles should have a name, statement, rationale and
implications.

The architecture description and architecture evaluation stages can work
on separate viewpoints for definition and evaluation of views according
to stakeholder concerns. For example:

-   Operational views,

-   System views and

-   Technical views.

Architecture activities will use the architecture principles that were
defined and maintained during the establishment of the architecture
landscape and architecture vision elaboration to build the specific
architecture domains upon.

Also, it may work upon architecture principles that are specific to the
architecture perspectives like: business architecture principles and
data architecture principles.

# Architecture capabilities

Architecture capabilities comprise any
necessary resource, capacity and ability necessary to perform
architecture activities at Enterprise or project level:

-   Human capabilities: the ability to perform roles and manage
    responsibilities, as of disciplines and specialties, with the right
    skills & competencies, and

-   Technical capabilities: the ability to support human capabilities
    and automate partly of entirely their activities and outcomes (ex.
    tooling capabilities)

A capability life cycle spans needs, requirements, acquisition,
in-service and disposal phases. A capability has attributes and measure
of effectiveness (e.g. effect, scale, time) and is defined independently
from implementation means.

Architecture capabilities are used in various combinations to achieve
outcomes. A capability is usually described as one or more sequences of
activities (called operational threads). The ability to execute an
activity depends on many factors identified at landscape establishment
and enriched throughout architecture stages.

# Recommended patterns for architecture and architecting

An architecture pattern records decisions taken by many architects in
many projects and organisations over many years in order to answer to a
recurring architecture questions through different drivers and involving
multiple concerns.

An architecture pattern is a reusable description of an architecture
view as described in the NAF v4 grid. The problem to solve may concern a
roadmap, the modes and states of a system, a recurring a course of
operations in a well-known operational domain. Therefore, a
multi-viewpoints problem may need many patterns in combination to meet
architecture objectives.

Patterns are managed as assets: they are documented in reference
libraries and may be found classified in catalogues. They have an owner
and are subject to approval by a board of architects.

# Architecture assets

Architecture assets are any architecture element that can be considered
in the Enterprise. These assets are either used at enterprise level or
shared between projects.

The architecture assets basically include deliverable and building
blocks. Architecture patterns can also be considered as assets to some
extent. However assets cannot structured without consideration of:

-   Requirements, architecture training courses, architecture training
    facilities,

-   Viewpoints, Models, Views, Diagrams, patterns and other artefacts

-   Catalogues (synonyms are portfolios and libraries) of : patterns,
    architecture projects, architecture views, main architecture
    documents for instance.

-   and associated baselines: reference requirements baseline, patterns
    baseline, architecture model and views baseline, architecture
    project catalog baseline.

A real ontology is needed here to describe formally the Architecture
Data.

Some examples at this point are:

-   A set of services exposes a Catalogue of Services.

-   An architecture View considered as a Solution Building Block.

-   A diagram considered as a Requirement (I.e. an expectation).
