---
title: Architecting activity
---

# Architecting Stages

Figure ‎2‑11 describes architecting activities in an architecting
organisation. They are organised in 8 stages, as follows:

  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Stages**                      **Description**
  ------------------------------- -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Architecture Landscape (AL)     Describes the overall context and defines the capabilities and means to develop an architecture.

  Architecture Vision\            Defines the architecture vision taking into account the landscape, stakes and time to market (or time to Customer).
  (AV)                            

  Architecture Description (AD)   Describes architecture from stakeholders’ viewpoints according to landscape, and identify a set of alternatives of architectures for evaluation.

  Architecture Evaluation (AE)    Updates architecture evaluation criteria set in motivation data to evaluate each alternative, identify the best ones, and elaborate change requests allowing to build the best trade-off from approved best alternatives.

  Plan Migration\                 Updates architecture migration plan and provides rationale for application.
  (PM)                            

  Architecture Governance\        Checks the application the best architecture trade-off according to the migration plan and provide guidance to resolve dependency conflicts.
  (AG)                            

  Architecture Changes (AC)       Elaborate and get approval on requests for architecture change.

  Motivation & Dashboard (MD)     Manages architecture context, constraints and drivers and provide views on architecture progress status and dependencies to other architectures and building blocks, through a dashboard aligning products with landscape (reference libraries and repositories).
  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

The method is inspired by the architecture description method of The
Open Group Architecture Framework (TOGAF/ADM), however it is different,
in order to:

-   Comply with evolving architecture standards (ISO/IEC/IEEE 42010,
    draft of ISO/IEC 42020 and 42030).

-   Ease its deployment within various contexts, not only
    information technology.

-   Allow flexibility in the navigation through architecting stages.

Figure ‎2‑11: Architecting stages

The method:

-   Allows the use of any number of viewpoint(s) and views per
    architecting stage.

-   Aims to capture and manage architecture motivation data, i.e. any
    element that will steer architecting activities from architecture
    vision to architecture baseline. This will extend the traditional
    requirement baseline with goals, expectations, constraints,
    drivers, risks, costs, value and opportunities. Therefore, while
    requirements are at the core of the TOGAF/ADM, the NAF v4 method
    extends the TOGAF/ADM requirement management stage and includes
    traceability of architecture products. This is used for defining
    and maintaining an architecture dashboard.

-   Allows more emphasis on the decision to change architecture and
    re-orientate the architecture due to a major evolution of
    motivation data.

-   Provides guidance on architecture assessment and trade-offs analyses
    using motivation data (stakes, objectives, constraints) which can
    lead to different criteria and techniques for identification and
    comparison of alternatives.

Each alternative of architecture is described by artefacts (architecture
products) of benefit to the stakeholders, which are aligned to
architecture requirements. This includes functional and non-functional
requirements and an architecture roadmap aligning with capability
increments.

Evaluation of architecture alternatives by cost, operational
effectiveness, system performances, system qualities and time to
capability milestones, expressed by customers or deduced from market
analyses.

The six steps can be mapped to following stages of the NAF v4
methodology:

-   Establish project architecture landscape.

-   Manage architecture motivation data (scope, objectives, policies,
    requirements, etc.).

-   Establish architecture vision.

-   Describe alternatives of architecture.

-   Evaluate alternatives of architecture.

The NAF v4 methodology defines 7 stages, visited iteratively to support
architecture decision making to deliver an architecture baseline. Each
stage has objectives. It refines architecture and creates artefacts
based on artefacts created from previous iterations, and from any source
of problem and solution contexts. Prerequisite of any iteration of the
NATO Architecture Methodology for architecting is to agree on:

-   Scope and level of abstraction.

-   Timeline, milestones (progress, validation).

-   Stop criteria.

-   Acceptance criteria.

The method is compliant with the 6-step process for architecting
introduced by DoDAF (See Figure ‎2‑12). It extends this process to
establish migration plans towards new architecture reference and
candidate target architectures, and govern implementation projects in
consistency with enterprise portfolios (e.g. product portfolios and
libraries of standards).

Figure ‎2‑12: 6-steps architecture process \[DoDAF v2.0\]

# Architecting dynamics and tailoring principles

Along architecture life cycle, architecting activities are grouped in
consistent stages that can be orchestrated in different schemes: some
activities can be repeated and a number of iterations involving specific
stages may be necessary to reach architecture goals.

Objectives and plan of each phase are key inputs to the dashboard.
Architects plan stages and define success criteria to complete
motivation data. The architecture management plan captures justified
cycles, iterations and synchronisations with other tiers architectures.

Figure ‎2‑13: Architecting cycles & iterations

Figure ‎2‑13 depicts architecting principles:

-   Iteration around stages: The completion of a whole cycle of
    architecture work may be necessary to set rapidly a broad scene of
    architecture changes and impacts, to refine through
    further iterations.

-   Iterating between stages: The neighbours of a given stage may be
    revisited to refine the findings of preceding stages as depicted in
    Figure ‎2‑13, e.g. returning to ‘Description of Architecture’ on
    completion of ‘Evaluation of Enterprise Architecture’ to describe a
    trade-off between the most promising alternatives). Two other kinds
    of iterations may be noted:

    -   Between ‘Migration planning’ and ‘Governance of application of
        architecture’

    -   Between ‘Architecture change’ and ‘Architecture vision’.

-   Iteration around a single phase: Stage description supports repeated
    execution of the activities within a single stage, e.g. a number of
    iterations of architecture description of architecture to establish
    consistent architecture products from multiple viewpoints.

At each stage, activities can use and update motivation data (see
iteration around motivation data). Approved updated are used to update
the dashboard where necessary.

There are many drivers for tailoring the method: maturity, policies and
complexity:

-   The vision can be agreed by stakeholders at first iteration when
    business is not new for them. Otherwise, more iteration may be
    necessary to reconcile stakeholders’ expectations in the vision.

-   The level of maturity of product/technical architecture can call for
    enforcement or lightening of activities at architecture
    description stage.

-   Enterprise principles such as product-line policies may shorten the
    space of possible alternatives to reach business goals.

-   The status (evolution, diversity, lack) of standards and norms may
    lead to more or less alternatives, whether to sustain architecture
    with regards to standards forecast or to reduce the space of
    alternatives for non-compliance of the product line to the
    target business.

-   Complexity of organisation as established at landscape (interleaving
    projects, architecture critical dependencies) can call for more or
    less complex principles to maintain a coherent
    architecture dashboard.

# Multi-tier architecting

Architecture activities can be run by different tiers: the enterprise,
domains within the enterprise, programmes in enterprise domains,
projects, belonging to or shared by programmes or portfolios.

Landscapes have to consider therefore target markets, customers and
shareholders policies, as depicted in Figure ‎2‑14. Architecture changes
driven by markets and or customers trigger vision updates at enterprise
tier, whilst transformation will be managed and checked at different
domains, starting from updates to their vision. Program and project
visions are impacted accordingly.

Landscapes are updated from general down to projects, and from projects
up to domains, to enable overall governance of enterprise
transformation.

Figure ‎2‑14: Multi-tiered Architecting
