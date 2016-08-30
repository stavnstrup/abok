---
title: Main concepts for Architecture and Architecting
---

# Introduction for architecting and architecture

Architecting encompasses the full range of activities of the architect
in creating, implementing and managing one or several architectures
addressing problems, expectations and/or solutions. The scope related to
the architecture generally includes a list of expected capabilities
and/or system-of-interest and its enabling systems sustaining system’s
viability along its whole system life cycle. (See ‎‎Annex E – for
definitions of “architecture”, “architecting” and “system of interest”).

The system-of-interest may be anything or a collection of things
analysed with a systemic approach, like an enterprise, a system of
systems, a traditional (single) system, a platform, a piece of
equipment, a service or a software application.

In many settings, such as product lines, family of systems, programs or
enterprises, the architect handles several different architectures at
the same time. Architecting aspects include 1) the scope of the
architecting effort, 2) stakeholder concerns and 3) architecting
activities to include producing an architecture description.

In some circumstances, the architect has also to work on system-agnostic
architectures. This is the case for at least operational capability
definition and mission thread exploration activities. Such architectures
are used either to identify systems sustaining the scope of interest or
to abstract existing systems in order to explain their provided value.

In this context, the architecture of an entity, as defined by ISO/IEC
42020[^1^](#fn1){#fnref1 .footnoteRef}, is the *fundamental concepts or
properties of an entity in its environment embodied in its elements,
relationships, and in the principles of its design and evolution.* The
architecture expresses:

-   The main characteristics of the problem and solution space with
    possible alternatives\
    Note: A complete solution includes the entity-of-interest and the
    enabling entities

-   Provide orientation data for the processes sustaining the life cycle
    of the solution related to the architecture.

-   The concerns of the Stakeholders for architected entity into
    formalised views

-   The assumptions made on the environment of each system of the
    solution to cover the life cycle of the solution (operational
    processes; natural, human and technical actors interacting with each
    system; functional and non-functional constraints, or obligations
    related to each system: see PESTEL[^2^](#fn2){#fnref2 .footnoteRef},
    DOTPMLFI[^3^](#fn3){#fnref3 .footnoteRef}, etc.).

# Architecting scope

The scope of architecting is the entire life cycle of the solution from
the earliest concept’s definition to retirement and possible
replacement.

As long as systems are concerned, discussions of architecting and
architectures may occur relative to a *system-of-interest.* Each
identified system can also be part of a more extensive system and
comprises less extensive systems. A notion of Product can also be
identified as system constituent or architecture building block. Most
sophisticated products contain other products (seen within subsystems)
capable of independent operation, e.g. a software operating system, with
each subsystem having its own architecture.

The scope of architecting encompasses not only technical considerations,
but a wide range of developmental, technological, business, operational,
organisational, political, economic, legal, regulatory, ecological and
social influences, and often aesthetic[^4^](#fn4){#fnref4 .footnoteRef}
*concerns* that influence the entity-of-interest.

# Stakeholder concerns, viewpoints and perspectives

Stakeholders include customers, designers, users, operators, architects,
suppliers, maintainers, accreditors and many actors. Identifying the
relevant stakeholders of an entity-of-interest (e.g. a system, a
capability) for each phase of its life-cycle is needed for formulating
and understanding its architecture. A stakeholder may be an individual
(e.g. the internal or external identified Customer) or a wide-ranging
class (e.g. the market demand for this product). Some stakeholders are
directly involved in architecting; others can only be concerned or
impacted by associated activities or outcomes.

Examples of concerns and impacts are: functionality, feasibility, usage,
performance, security, cost, schedule, compliance to regulation. This
listing of example concerns gives concrete evidence for the “breadth
approach” expressed by Mills \[Mills, 1985\].

Architecture description can be done with a separation of concepts
within one or several views in accordance with viewpoints and
perspectives. The result of the description can be supported by one or
several models. An architecture model may be a part of more than one
architecture view. Models are a way to share information between
architecture and views.

Note: In most of the architecture framework, viewpoints are expressing
framework-predefined concerns; while perspectives are project-specific
concerns; but this difference between viewpoints and perspectives is
currently not standardised, i.e. ISO/IEC/IEEE 42010 only states
viewpoints as being the way to express concerns.

# Architecture dimensions

Several dimensions can be considered for development of architectures.
For example:

-   Architecture life cycle with phases, from creation to closed out.\
    The NAF v4 methodology does not specify the number and names
    of phases.

-   Periods of time when architecture applies: from now (“as is”) to a
    target period (“to be”) and milestones.

-   Architecture maturity with versions and stages that characterise the
    evolutions per iteration. Stages are at least conceptualised,
    defined, assessed, used and disposed.

Architecture viewpoints and perspectives can also be considered as
dimensions transverse the previous ones.

# Kinds of architectures

The NAF methodology tries to be independent of the various kinds of
architectures and architecting styles currently used in industry and
governmental organisations.

Nevertheless, different kinds of architectures can be considered
according to their purpose, domains of application and roles within
entity and architecture life cycles. Architecting may require the use,
the development and/or the application of architectures of several
kinds. Examples of kinds of architectures are:

-   Enterprise-wide architecture descripting the future situation with
    limited detail. This description normally covers several programs.

-   Architecture description to be used as reference by a programme or
    for architecting within a domain.

-   A description limited to the scope of a single project addressing
    implementation decisions.

“Baseline architecture” is also defined in the architecture frameworks;
but this term qualifies an architecture rather than being an
architecture as such. An architecture baseline is an architecture that
has been formally agreed and that thereafter serves as the basis for
further development. E.g., As-Is (baseline) architecture or baseline
technology architecture.

Note: Some other kinds of architectures are also defined in architecture
frameworks like TOGAF:


<table>
<thead>
<tr>
<th>TOGAF architectures</th>
<th>Usages</th>
</tr>
</thead>
<tbody>
<tr>
<td>Capability Architecture</td>
<td>An overview of current capabilities, target capabilities, and capability increments to be fulfilled by one or several systems / projects.</td>
</tr>
<tr>
<td>Business architecture</td>
<td>A description of the structure and interaction between the business strategy, organisation, functions, business processes, and information needs.</td>
</tr>
<tr>
<td>Information Systems Architecture</td>
<td><p>Describing how the enterprise’s Information Systems will enable the Business</p>
<p>Architecture and the Architecture Vision.</p>
<p>Note: An Information system can be seen as a subset of a system.</p></td>
</tr>
<tr>
<td>Technology Architecture</td>
<td>Description of technology assets and standards that are used to implement and realise solutions.</td>
</tr>
</tbody>
</table>

|--------------------------------------+--------------------------------------|
| TOGAF architectures                  | Usages                               |
+======================================+======================================+
| Capability Architecture              | An overview of current capabilities, |
|                                      | target capabilities, and capability  |
|                                      | increments to be fulfilled by one or |
|                                      | several systems / projects.          |
+--------------------------------------+--------------------------------------+
| Business architecture                | A description of the structure and   |
|                                      | interaction between the business     |
|                                      | strategy, organisation, functions,   |
|                                      | business processes, and information  |
|                                      | needs.                               |
+--------------------------------------+--------------------------------------+
| Information Systems Architecture     | Describing how the enterprise’s      |
|                                      | Information Systems will enable the  |
|                                      | Business                             |
|                                      |                                      |
|                                      | Architecture and the Architecture    |
|                                      | Vision.                              |
|                                      |                                      |
|                                      | Note: An Information system can be   |
|                                      | seen as a subset of a system.        |
+--------------------------------------+--------------------------------------+
| Technology Architecture              | Description of technology assets and |
|                                      | standards that are used to implement |
|                                      | and realise solutions.               |
+--------------------------------------+--------------------------------------+

Note: These kinds of architecture are here quite similar to architecture
viewpoints. But this wording is common practice.

See ‎Annex A – - ‎A.1 for more explanation about how to consider kinds
of architecture in the NATO context.

# Architecting Styles

It is widely recognised that the development of an architecting approach
is not straightforward and typically the development of an approach is
limited by the expertise and experience of an individual architect. This
results in varying degrees of success and a continual need to reinvent.
To help architects and the problem owners who commission the use, and
ultimately control, the funding for architecture outputs, a small number
of standardised architecting styles have been proposed. These styles
help to understand the approach that should be taken; set expectations
on what can be achieved; clarify what is involved (e.g. in terms of
costs, skills and governance); and, help to understand how value is
delivered to the enterprise. The styles are driven by the purpose or
reason for the architecture and reflect currently observed best
practice.

Four styles of architecting have been identified by architecture
practitioners within the United Kingdom (See UK MOD’s ‘perfect storm’ –
and the need for Architecting styles”, NATO STO-MP-SCI-254 presented at
Symposium on Architecture Assessment for NEC, Tallinn, Estonia, 2013 by
David Evans and Mike Wilkinson). They are as follows:

1.  Authoritative.

2.  Directive.

3.  Coordinative.

4.  Supportive.

‎Annex F – provides further details.

# Main Architecture processes

A first description of process, activities and tasks related to
Architecture definition is provided by
ISO/IEC/IEEE-15288[^5^](#fn5){#fnref5 .footnoteRef}. A more detailed
explanation is given in this section with identification of 5 processes
that could be performed by different organisations and projects within
an Enterprise.

This description of processes is close to the ISO/IEC
42020[^6^](#fn6){#fnref6 .footnoteRef}.


{%include figure.html url="process-areas.svg" description="Architecture Processes"%}


Architecture processes can run concurrently, even if the governance and
management directions circulate in down-flows and operation reports in
up-flows.

Architecture definition and evaluation are interleaved to regularly
state about quality and distance to expectation.

The enabling activities are transverse to other architecture processes.
They ensure seamless consistency of services and data within the
architecting environment.

## Architecture Governance

Governance covers the strategic activities controlling architecture
according to enterprise directions and objectives. The main governance
activities include:

-   Establish capability for governance.

-   Establish strategic desired outcomes for the architecture portfolio.

-   Evaluate coherency of architecture roadmaps toward desired outcomes.

-   Provide directions for the architecture portfolio and the
    related activities.

-   Monitor the enterprise’s portfolio of architectures and the related
    activities to ensure compliance with the governance directions.

-   Decide on necessary corrective actions and Iterate

This process is normally under responsibility of enterprise entities in
charge of the consistency of architectures across projects of the
enterprise. This consistency concurs to the overall governance of
activities and assets of the whole enterprise.

Note: Each activity is governed by principles. An external authority
should be in charge of checking that activities are performed according
to these principles. This authority could be called “Design Authority”.

See ‎Annex A – for explanation of the governance activities in NATO.

## Architecture Management

Architecture management is an executive process to plan, command and
control architectures along their life cycle. The objective is to get
the architectures developed according to enterprise governance direction
with regards to stakeholders’ expectations.

These activities include:

-   Establish capability for management of one or several architectures
    in the scope of responsibility, and the related activities.

-   Establish plans for conducting architecture management activities
    according to the governance directions.

-   Provide guidance and direction for architecting activities.

-   Monitor and assess architecture development with
    management direction.

-   Decide on necessary corrective actions and Iterate.

This process is normally leaded in different organisations of the
enterprise where architecture developments are taking place. It strongly
depends on the kind of architecture being developed.

## Architecture Description

Architecture description process aims to be compliant to
ISO/IEC/IEEE-42010:2011[^7^](#fn7){#fnref7 .footnoteRef}. The main
activities already identified are:

-   Analyse the problem situation (purpose, scope and objectives).

-   Identify the stakeholders, their concerns and needs

-   Formalise and classify key requirements from collected needs

-   Identify the potential solutions

-   Identify architecture viewpoints according to
    stakeholders’ concerns.

-   Develop models and views of candidate architectures from
    these viewpoints.

-   Provide the rationale of the potential solutions with regard of
    requirements and motivation data. In particular, ensure their
    traceability to motivation data.

-   Review architecture candidates with stakeholders and get
    their approval.

-   State relations between candidate architectures and design and other
    downstream activities.

## Architecture Evaluation

Architecture evaluation is currently under standardisation at
ISO[^8^](#fn8){#fnref8 .footnoteRef}. Forecast is that the international
standard under work will become a reference like 15288 and 42010. The
proposed architecture evaluation activities are:

-   Define evaluation purpose, scope and objectives.

-   Identify the stakeholders of the architecture evaluation, and their
    concerns or questions

-   Determine evaluation criteria (according to
    stakeholders’ concerns/questions) with their relative importance
    (priorities, weights, etc.)

-   Determine techniques, methods and tools for performing
    the evaluation.

-   Evaluate the architecture.

-   Collect and understand required information (metrics).

-   Formulate the findings and recommendations.

## Architecture Enablers

Enabling activities provide services, means and data to sustain other
architecture processes. This allows the architects to:

-   Develop, evaluate, import, export and document architectural models.

-   Provide enterprise and projects with reference data including
    standards; patterns; information about assets; and any other
    business information reusable by Architecting activities.
-   Ensure architecture data consistency and support change management
    (features to link architecture models and model elements across
    multiple modelling environments, to link architectural data with
    other enterprise and project data, to perform impact analysis when
    either model elements and/or data are changed, etc.).
-   Develop and maintain architectures data (Electronic content
    management, architecture data queries, configuration management.).

-   Ensure that architecting activities are performed according to
    enterprise rules (Privacy, information security, networking, etc.).

# Architecture Life Cycle

The Architecture is a living concept that orientates the life cycle
processes of the architected entity.

When directly associated to a system, the architecture life cycle maps
the whole system life cycle from its concept phase to its disposal.

However, sometimes architecture can express various expectations not
directly linked with a single system. For example:

-   Architecture issued prior to identification of system(s): it
    describes the problem space, to allow solving the problem according
    to stakeholders’ concerns. In this case, only business/operational
    views and capability views are elaborated. They are used to update
    the doctrine, operational processes, or to acquire and govern
    systems or services. The architecture life cycle starts when problem
    analysis starts, and finishes when both the problem and solution
    spaces are no longer concerned.

-   Architecture issued to cover several projects worked concurrently
    along a period of time: it may be called overarching architecture
    and the set of projects are considered as a program. The
    architecture life cycle starts with the beginning of the program and
    ends with the last project.

-   Architecture issued to cover several systems/products worked
    concurrently along a period of time: Product lines, families of
    systems and systems of systems are belong to this case. The
    architecture provides an overall definition which is normally
    refined by individual system/product architectures.

-   Architecture issued to cover several projects worked in sequence –
    when possible – along a period of time: In this case, the
    architecture provides the transformation roadmap, including
    systems/products evolution and/or replacement, to fulfil
    architecture objectives at the considered period of time.

These different cases highlight the need to customise architectural
environments, activities and outcomes in order to fit for purpose.
Customisation will also depend on the enterprise organisation and the
complexity of both problem and solution.

# Architectures and Architecting activities in the enterprise

Considering an enterprise as a group of people or a group of
organisations, most of the time, the enterprise business is divided into
units, domains and projects involving all the necessary disciplines and
expertise.

An enterprise can consist of enterprises within it. In that case the
inner enterprises are acting within their own business processes and
within the overall enterprise business according to several possible
models being federated, cooperative and collaborative for example.

Architecture activities have to be considered at any enterprise level
and per entity since each is expected to work with a systemic approach,
i.e. each enterprise entity acquires and/or develop systems and/or
products to cover its own usage and for its deliveries.

Within these enterprise entities, each work unit can be considered as a
project. This project can be performed either entirely in a relevant
enterprise entity, with other enterprise entities or third-parties. The
architecture and related activities can be seen as being at a project
level when the project is performed by a single entity or when there is
no interest to know how the project is done from a given analysis point
of view. Architecture and related activities for the enterprise scope
performed by several enterprise entities according to several
organisations: collaborative architecture activities, multi-tier (or
multi-layer) sequential activities, multi-tier concurrent activities,
etc.

For multi-tier architecting activities in an enterprise, the
middle-tiers act:

-   As Project for the upper tier

-   As Enterprise for the lower tier

This means that an architect or a team can work within a double
architecture framework. However, the 2 roles and environments have to be
clearly distinguished in order to get clear outcomes and interaction
between the levels.

The following figure provides an example about how to maps the
multi-tier architecture activities with the examples of kinds of
architecture defined in section ‎2.4.5:

-   Enterprise architectures are developed by the enterprise
    tier activities.
-   Reference architectures are developed by domain and programme tier
    activities
-   And system architectures are developed at project levels


{%include figure.html url="combo-level-kinds.svg" description="Example of multi-tier architecture activities"%}


# Architecture Framework

## Introduction to Architecture Framework

The best definition that can be found in technical literature is
currently given by:

**Architecture framework** \[TOGAF v9.1, page 45\]: “is a foundational
structure, or set of structures, which can be used for developing a
broad range of different architectures. It should describe a method for
designing a target state of the enterprise in terms of a set of building
blocks, and for showing how the building blocks ﬁt together. It should
contain a set of tools and provide a common vocabulary. It should also
include a list of recommended standards and compliant products that can
be used to implement the building blocks.”

It must be stated that:

-   No Architecture Framework is currently fully compliant with
    this definition. Some Frameworks focus on architecture description
    and others are more oriented to process description. Very few
    include tools and/or standards.

-   Part of an Architecture Framework is related to Architecture Domain
    with reference standards and products. This part is to be defined
    and adjusted according to enterprise organisation and policies.

## Architecture Framework as working environment

An architecture framework can be characterised as a working environment.
This environment is called an ‘architecture landscape’.

{%include figure.html url="architecture-landscape.svg" description="Architecture landscape"%}


The architecture landscape is structured in 4 main areas:

-   The architecture workspace where architectures are developed.

-   The reference libraries containing any information useful for the
    architects to either do their job or to get architecture
    related information.

-   The architecture repositories where architectures and architecture
    building blocks are made available:

    -   To be used as references for implementation.

    -   To provide principles and guidelines for development of other
        architectures and elements.

-   The architecture registries record the usage of elements in
    reference libraries and architecture repositories in order to allow
    their management and governance.

Architecture landscapes can be considered at any tier of the Enterprise
performing architecting activities or accessing architecting outcomes:
whole enterprise, domains, programmes and projects.

Note: Right-to-know and relevance of information will be considered for
each architecture landscape.

## Enterprise architecture landscape

It allows enterprise architecting activities in the enterprise to cover
multi-programme, multi-project and enterprise-width business.

Enterprise reference libraries and enterprise architecture repository
host data being available for the other stakeholders of the enterprise.
In these shared spaces, data elements are stored within baselines, i.e.
the data elements are recorded according to their temporal and
structural dependability. A baseline is characterised by a given time
and a data configuration.

Enterprise reference libraries host the baselines of assets reusable by
any architect of the enterprise.

Enterprise architecture repositories host the baselines of the
architectures and architecture elements produced or updated by any
architects of the enterprise, and approved by the board of architects.

The enterprise architecture workspace is the environment where the
architects act at the enterprise level. This area contains work-products
and data developed by architects prior to their publication as a new or
updated reference, architecture element and architecture.

Enterprise architecture registries record the usage of elements of
reference libraries and of architecture repositories in the enterprise
architecture landscape.

## Project architecture landscape

This landscape has exactly the same structure as an enterprise
architecture landscape:

-   Project reference libraries host the baselines of assets reusable by
    the architects in a project.

-   Project architecture repositories host the baselines of
    architectures and architecture elements produced or updated by
    architects of the project.

-   Project architecture workspace is the environment where the
    architects work for the project. This area contains any work-product
    and data developed by architects prior to their publication as new
    or updated references, architectures and architecture elements.

-   Project architecture registries record the usage of elements in
    reference libraries and architecture repositories in the project’s
    architecture landscape.

## Architecture landscape interactions

{%include figure.html url="landscape-interact-tierN.svg" description="Architecture landscape interactions (view from Tier N)"%}


Interactions occur between architecture landscapes when multi-tier
architecting activities are in place in an enterprise (See ‎2.4.9 with
the example of enterprise, domains, programmes and projects tiers).
Architecture landscapes are complementary structures. Considering the
interaction from one tier point of view:

-   The architecture landscape exposes usable or mandatory data
    (references and architectures) for the other tiers

-   The architecture landscape uses and profiles data elaborated by the
    other tiers.

{%include figure.html url="architecture-landscape-ex-inter.svg" description="Architecture landscape external interactions"%}


Architecture landscapes also interact with the enterprise environment
to:

-   Collect external data elements enriching enterprise’ assets with
    references, architectures and architectures elements (with respect
    of the copyrights and licenses).

-   Publish enterprise assets (with respect of the right-to-know).

## Reference libraries

Reference libraries host the baselines of assets reusable by architects
in their activities per architecting organisation. This information can:

-   Either come from the lower architecting tiers in the enterprise
    organisation, in which case the consistency and the relevance for
    the current tier is checked or,

-   Be created and/or collected for lower tiers through
    architecting activities.

{%include figure.html url="ref-libs.svg" description="Reference libraries"%}


The reference libraries may include:

-   Meta-models and ontologies providing the terms and concepts used in
    the reference system. This information provides the enterprise
    foundations to build the vocabulary of the projects. They can be
    updated and augmented by projects-specific terms and concepts.

-   Customisable architecture motivation data.\
    Architecture motivation data could cover the concepts defined in the
    Open Management Group Business Motivation Model with:

    -   Information directing or defining the business aspirations:

        -   Business vision, goals and objectives

    -   The means to realise the business aspiration

        -   Missions and course of action.

    -   The stakeholders’ value system and associated assessment
        elements

        -   Key requirements, risks, opportunities, cost and value per
            viewpoint

        -   Assessment criteria and key questions

    -   Business directions and guidance for activities.

    Note: A more detailed description of architecture motivation data is
    given in section ‎2.4.12.

-   Patterns providing canonical templates, constructs and activities.

-   Standards, de facto (standards issued from best practices or
    Enterprise policies) and de jure (standards issued from
    professional, governmental or international regulatory bodies)
    references.

-   Portfolios of products (including services) and systems that are
    recommended for usage in the architecture activities.

# Architecture Repositories

{%include figure.html url="arch-rep.svg" description="Architecture Repositories"%}


Architecture repositories host the baselines of architecture elements
produced or updated by architects per architecting organisation.

Architecture repositories include:

-   The different kinds of architectures.

-   The architecture elements: architecture patterns and architecture
    building blocks.

-   Meta-models and ontologies formalising the terms and concepts used
    in the architecture repositories.

# Architecture Motivation Data

This concept gathers information and references relevance for
initialisation of architecture, orientation of architecting activities
and analysis of findings.

Motivation data includes the problem vision, goals and objectives to be
met by the architecture. From these aspirations, the organisation
identifies the main concerns, subject to questions along architecting
activities. Statements of missions communicate the direction of the
organisation intending to pursue the vision. A strategy (i.e. long term
plan) defines how to achieve corresponding goals.

Architecting activities are oriented by external and internal drivers
and rely on well-defined criteria to assess the findings. Drivers may
impact the use of reference processes and may call for architecture
method tailoring.

For instance, when interoperability drives architecting, the method
recommends to tackle business and/operational concerns prior to any
migration activity. According to architecting policies, architects will
plan the evaluation of alternatives to actual architecture operational
products to meet objectives.

Policies and rules set the context of process adaptation to major
architecture drivers such as interoperability.

The main interfaces to engineering processes (reference documents,
engineering change requests, checks) are specified in architecture
policies, including guidance rules to align with enterprise and projects
policies.

{%include figure.html url="motivation-data.svg" description="Motivation Data" %}


# Manage architecture motivation data

Architecture motivation data is a living concept: it is initialised by
an architecture change request and fed by the architecture landscape
that led to change approval. It includes different types of data:

-   Contextual data: business elements (business model, directives,
    eco-system analyses, product portfolios, project portfolios,
    architecture principles, assumptions for architecture governance and
    management, Norms and standards, including export control
    and regulations).

-   Justification data: architecture change justification and impact
    analyses,

-   Orientation data: architecture policy, approved architecture vision
    that specifies business goals, expected timeline and the right
    capabilities to meet the goals at the right time.

-   Planning data: Architecture statement of work and plans (governance,
    management, configuration management, resources). The architecture
    plans will follow one of the architecture driver set (e.g.
    DLOD[^9^](#fn9){#fnref9 .footnoteRef}, PESTEL[^10^](#fn10){#fnref10
    .footnoteRef} and DOTPMLFI[^11^](#fn11){#fnref11 .footnoteRef}) as
    agreed by stakeholders).

Architecture workflows are conceived to revisit motivation data
according to the findings of previous stages in terms of:

-   Evolution of contexts and or needs.

-   New scenarios, same or new missions, for the same or different
    contexts, requiring the same or different quality of service.

-   To deliver in the same or different timeline.

-   Evolution of norms/standards/regulations: update or obsolescence of
    (domain, technology, business, political, societal) norms.

-   Concept change: doctrine, business domain and technology.

-   Enterprise strategy change (product-line, roadmap, partnership,
    acquisition policies).

-   Markets, stakeholders, organisation, enablers, products, roadmaps,
    compliance to customer requirements or product line approach, etc.

The most important principle for architecture change decision is to get
stakeholders agreement on priority over expected capabilities from
business, capability and technical standpoints. The second principle
that architects will observe is checking consistency of capability
dependency models with capability phasing views to highlight capability
critical dependencies, taking into account:

-   Agreement on priority of expected capabilities from evolution
    timeline and related metric evolution viewpoint.

-   Stakeholder’s agreement on weight of each criterion used to assess
    and compare alternatives of architecture.

-   Revisiting (baseline of) stakeholders’ requirements according to
    priority and weights of criteria.

-   Revisiting motivation data according to outputs of the last
    iteration of the vision stage.

# Architecture Policy

An architecture policy is the system of principles guiding architecture
decisions and achieving rationale outcomes. It has a title, an
additional authority and includes the architecture glossary.

It is adopted by the board of architects and implemented in procedures
and/or protocols to be applied by architects when performing their
activities.

Architecture policy will assist architects in defining the scope and
boundaries of architecture products, setting interfaces to architecture
resource and facilities, and to subsequent engineering processes and
activities.

In order to plan consistent and affordable roadmaps, the architecture
policy includes the principles to interact with:

-   Building block owners.

-   Support entities.

-   Experts and specialists.

-   Strategists.

-   Decision-makers.

# Architecture Management Plan

This plan provides the overall framework for architecture development.
The goal is to deliver the appropriate guidance to support acceptance,
while ensuring that architecture models are exploited to reuse assets
and support efficiently test cases. It describes:

-   The architecting strategy according to enterprise policies:
    architecting activities to run, expected product’s focus to reach
    architecture goals as stated in the corresponding state of work.

-   Tailoring of architecting iterations and architecture products to
    reach architecture goals. It includes a stop criteria for each
    planned activity

-   Architecture landscapes, within and outside the enterprise, as
    described in sections ‎2.4.10.3 to ‎2.4.10.5:

    -   Reference libraries hosting reusable assets, including reference
        skills, methods, and tools to achieve activities.

    -   Repositories hosting baselined architecture products.

    -   Workspaces hosting architecture development data and
        work products.

    -   Interaction between landscapes along architecture life cycle.

    -   Interaction between architecture activities and other activities
        (planning, engineering, operations and maintenance).

-   The planning of activities and control of architecture requirements
    and products

-   The governance and management processes of architecting activities

The architecture management plan is a living document. It is updated as
much as necessary to reflect changes, especially, changes of goals,
landscapes and their interactions.

# Migration Plan

Migration to the baseline architecture is planned and described taking
into account the scenarios allowing handling critical dependencies to
other projects, if any. The plan recalls the context and scope of
migration to the baseline and describes:

-   The main goals from stakeholders perspectives.

-   Reference policies and rules for migration including conflict
    resolution principles and configuration management rules.

-   If necessary, the migration strategy and criteria.

-   Roles and responsibilities to manage the migration process in
    alignment with reference policies.

-   Migration timeline and decision making policy.

-   Migration means: motivation data, library, repository and dashboard.

# Evaluation Report

Identified alternatives of architecture are evaluated according a
selected set of criteria, reflecting the main concerns of and agreed
with stakeholders. The evaluation report describes the following points:

-   Scope of evaluation.

-   Description of evaluated alternatives.

-   Evaluation objectives and criteria.

-   Evaluation method and rationale.

-   Evaluation results.

-   Interpretation of results and recommendations.

Recommendations are provided to support decision making: decisions
concern the approval of alternatives and of proposed trade-offs, where
necessary. Trade-offs will usually concern the negotiated non-functional
properties to keep architecture in line with budgets and timeline,
though evaluated timeline and/or value-to-cost may suggest transitioning
via more affordable solutions to target.

# Main Architecture Document

The main architecture document living document is initialised from
landscape. It recalls architecture context, goals and objectives and
synthesises the findings of architecting activities.

It defines the architecting method and associated principles, and
provide a rationale for customisation based on agreed drivers, internal
and external. The rationale includes an explanation of concerns and
criteria selected to meet architecture objectives.

Principles usually include the expected number of alternatives and the
criteria allowing to distinguish clearly each alternative (a property, a
capability level). Properties includes architecture availability,
characteristics and cost (development migration, application costs).

The body of the main architecture document describes retained
architecture alternatives from stakeholders viewpoints, and for each
candidate, the set of assumptions and results interpreted to support
decision-making.

The executable summary of the main architecture document provides a
synthesis of:

-   Stakes, constraints and assets enabling to approach the vision.

-   Principles and criteria to shortlist alternative of architectures.

-   Criteria to find the best candidate or to propose a trade-off from
    shortlisted candidates.

# Architecture Dashboard

Architecture dashboard synthesises data needed to monitor architecting
activities until architecture goals are considered as achieved or, until
a decision to suspend part or whole of monitored activities is taken by
the architecture board.

Architecture has its own life cycle. The dashboard highlights
architecture key milestones as they are agreed at initialisation/update
of architecture vision, in consistency with enterprise directives and
policies.

Two kinds of milestones can be distinguished in a dashboard:

-   Milestones for architecture products to be developed and evaluated
    by architects: we call them hereafter architecting milestones

-   Milestones for architecture to be developed and implemented by
    projects: We call them hereafter architecture milestones.

{%include rasterfigure.html url="dashboard-outline.png" description="Dashboard depicting interleaving activities along an architecture life"%}


Architecture milestones correspond to capability configurations of
the selected architecture trade-off solution to fit customer and users
expectations:

-   Capability levels: operational relevance, deployment readiness,
    integration with legacy are examples of architecture milestones from
    a customer perspective.

-   Technical feasibility, with respect to standards, norms and laws
    (international and or local) can lead to different configuration
    milestones from the designer perspective.

-   Roadmaps of building blocks of interest induce milestones from
    development perspectives.

-   Technology readiness roadmaps dictate milestones from technology
    readiness perspective.

Architecting milestones correspond to the phases and timelines to
deliver architecture products and propose trade-offs, they must conform
to the architecture management plan (enterprise/ project).

Therefore, a dashboard may be parameterised to monitor activities run
along architecting phases of an architecture project and the evolution
of architecture baselines as managed within an enterprise portfolio.

Each goal might be refined along architecting phases into sub-goals and
associated intermediate milestones. Each of them allows running analyses
while composing logically and or physically (when concept experiment is
part of the evaluation process), selected building blocks and
sub-systems of the architecture libraries with remaining part of the
solution. Analyses consider architecture qualities, performances, human
factors and any property aiming to satisfy operational needs.

Architecture goals, together with the landscape and architecture
milestones form the core of the architecture motivation data and shall
be consistent with the architecture management plan.
