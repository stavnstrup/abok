---
title: Architecting in a project
---

# Overview of Project architecting activities

Project architecture defines the rationale for architecture moving from
the “As-is” to a “To-be” architecture. Starting from the overall
context, and applying enterprise directives and policies, the project
vision is set according to the concerns of stakeholders and associated
priorities. The latter are used to initialise key architecture
requirements as part of the motivation data. During architecting
activities, the motivation data is enriched consistently with the
rationale associated to identified architecture alternatives, evaluation
criteria and trade-offs when necessary.

Evaluation criteria are initialised from vision elements, namely
architecture objectives.

The description stage identifies and describes alternatives of
architectures which satisfy key architecture requirements and known
constraints.

The evaluation stage provides support to decision-making, using criteria
agreed by stakeholders.

# Project architecting activities

## Project: Architecture Landscape (AL)

**Objectives**

* Establish the architecting capability according to expectations and context, scope and target.
* Tailor and get stakeholders’ agreement on the data that will guide architecture activities.
  * Enterprise directives on architecture
  * Enterprise principles applicable to architecting.
  * Infrastructure, methods, tools and principles enabling activities from
    architecture Vision to architecture definition.
  * Enterprise principles monitoring progress of architecture.


**Tasks**

* Confirm enterprise expectations, map to project motivation data and set
  corresponding indicators in the   dashboard.
* Define architecture team members, their personal and collective roles objectives
  to fulfil the architecture capability
* Per identified role: collect, analyse and mark architecture inputs to feed the
  motivation data & dashboard.
* Define architecture workflows: link main roles, outcomes and communication
  policies. In particular, specify roles and workflows defining the interface to
* Enterprise Architecture level (Architecture governance board).
* Set infrastructure, select and adapt tools and method supporting architecture
  capability.
* Initialise architecture repositories to manage architecture
* Set architecture principles to apply by architecture project actors.
* Define architecture dashboard to monitor architecture progress.
* Check consistency of project rules with enterprise principles.

**Inputs**


* Context, drivers and constraints calling for architecture capability
  * Business strategy, product-line strategy, portfolios, partnerships and
    contract agreements.
* Architecture scope and expectations, in terms of business objectives and timeframes.
* Resources plan to sustain architecture capability along the agreed architecting
  timeframe (i.e., from vision to new baseline).
* Principles and constraints from enterprise business motivation data.
* Architecture State of work.
* Architecture documents of legacy systems: interfaces, life cycles, known constraints.
* Architecture management plan outline.

**Outputs**

* Organisation of architecture team: architecture OBS and agreed workflow
  from vision to architecture baseline.
* Tailoring of the architecting process to enable the workflow.
* Definition of resources, skills and roles according to the tailored architecting
  process.
* Definition of key interfaces to complementary architecture frameworks
  if any (i.e. dedicated architecture framework).
* Definition and statement of work for customisation & initialisation of
  architecture support tools, including interfaces to complementary tools &
  repositories if any.
* Agreement on architecture principles applicable from vision to baseline.
* Agreed principles (or links to) are initialised within the architecture
  repositories at kick-off.
* Architecture management plan Outline.

**Stakeholders**

* Architect, project manager.
* Representatives (plan, operations, legacy systems, standard, technology watch,
  regulations and laws).
* Specialists (security, safety, human factors, etc.).
* Sponsors.


**Input views**

* NAF v3 formalism:
  * NOV-2, NOV-3,
  * NOV-5, NSV-1,
  * NSV-5, NSV-7,
  * NTV-1.
* NAF v4 grid:
  * L2, L3, L4, P3, P4,
  * P8, Pr, A8.

**Output Views**

* NAF v3 formalism:
  * NAV-1 with reference to input views.
* NAF v4 grid:
  * A1 to 8 (i.e. metadata, architecture plan and architecture Summary
    documentation with references to input views.

## Project: Manage architecture motivation data & dashboard

**Purpose**

* Set and maintain architecture up-to-date motivation data.
* Monitor architecture progress and stop activities according to enterprise
  policy and stakeholders’ expectations.

**Tasks**

* Initialise motivation data starting from project landscape.
* Check consistency of architecture principles with enterprise directives.
* Check consistency of constraints with enterprise directives: economic (cost,
  value, risk), missions, physical (weather, electromagnetism compatibility, terrain,
  human factors, security & safety, export and regulation, skills.
* Identify the effective drivers of architecting activities: choose DLOD,
  PESTEL, DOTMPLFI, etc. according to the analysis of stakeholders needs.
* Check the joint impact of pre-cited factors, on the current baseline, whether
  implemented or on the way to be. Hint: the impact may be described using NAF
  views, to be completed by top level customer, user or technology related
  requirements.
* Set principles for architecture change decision.
* Revisit motivation data according to outputs of the last iteration of the vision
  stage, in terms of evolution of contexts and needs, evolution of norms, standards
  and regulations, release, update or obsolescence of domain, technology,
  business, political, and societal conditions, changes to doctrine,
  business, technology and enterprise strategy.
* Agree on priority over expected capabilities from business viewpoint.
* Use capability dependency and capability phasing to highlight critical milestones.
* Agree on weight of criteria selected to evaluate and alternatives of architecture.
* Revisit stakeholder requirements according to priority and weighted criteria.
* Initialise architecture dashboard with agreed data (weights, dependencies,
  priorities, criteria, objectives, roadmaps).
* Log the context of architecture assessment and trade-offs at each decision point.
* Update dashboard, check and manage alerts.
* Mark selected/discarded/changed artefacts at each decision point.
* Trace towards inputs and document rationale of each decision.

**Inputs**

* Architecture management plan
* Elements from project architecture landscape.
* Elements of Architecture vision: planning of architecting phases, initial
  milestones for synchronisation with enterprise, initial milestones for
  synchronisation between project phases.

**Outputs**

* Architecture management plan update.
* Dashboard featuring: key architecture milestones: Phase milestone,
  synchronisation milestones (inter-phases, enterprise to project), stop criteria,
  progress of each phase of architecting vs. project milestones, alert icons (on
  phases, synchronisation between phases and/or with enterprise milestone),
  decision points, marked artefacts.
* Vision models and documentation published in the architecture repositories.


**Stakeholders**

* Architect, project manager.
* Representatives (plan, operations, legacy systems, standard, technology watch, regulations and laws).
* Specialists (security, safety, human factors, etc.)
* Managers of implementation projects
* Sponsors.


**Input views**

* NAFv3 formalism:
* NAV-1 Chapters: Capability phasing, capability dependencies, system evolution,
  system technology evolution, technology forecast, assumptions and
  constraints.
* NAFv4 grid:
  * C1 to 3, C2, Cr, Lr, A1 to 8.


**Output views**

* NAFv3 formalism:
  * NAV-1 updates to chapters: phasing of capability, system
    evolution, system technology evolution, technology forecast,
    updates to assumptions and constraints.
* NAFv4 grid:
  * Updates of C1 to 3, A1 to 8, Ar, Cr, Sr, Lr, Pr.

## Project: Establish Architecture vision

**Objectives**

* Set Project objectives from strategic goals.
* Scope architecture sustaining business objectives: for target market, within
  key timeframes and milestones allowing the right effects /profits/savings and
  respecting local constraints & policies.
* Define architecture outcome with regards to enterprise principles.
* Identify architecture risks and define mitigation actions.

**Tasks**

* Get stakeholder commitment on architecture work.
* Validate stakeholder high level requirements.
* Get stakeholders agreement on: enterprise motivation data setting and
  usage, architecture principles, architecture goals & drivers with regards
  to timeframes.
* Analyse existing architecture baselines if any.
* Validate architecture goals and drivers with regards to timeframes.
* Identify interleaving with other projects with focus on critical milestones and
  interfaces.
* Establish a statement of architecture work: initialise architectures comparison
  criteria, tailor the architecture development process (outcomes of each
  phase, synchronisation, iterations and milestones).
* Update architecture dashboard.

**Inputs**

* Architecture management plan outline.
* Request for architecture work including references to existing architecture baselines.
* Committed architecture Stakeholders.
* (Identified) business goals and drivers.
* Architecture principles.
* Common architecture framework.
* Initial Architecture dashboard.


**Outputs**

* (Updated) architecture management plan.
* Updated state of architecture work.
* Preliminary architecture management plan, including architecture deliveries and
  reviews taking into account synchronisation with related architecture
  projects.
* Updated project motivation data (including top level requirements when
  necessary).
* Initial architecture risk & mitigation plan
* Updated architecture dashboard.

**Stakeholders**

* Architect, project manager.
* Representative of plan.
* Representative of Ops.
* Representative of legacy systems.
* Representative of standards & technology.


**Input Views**

* NAFv3 formalism
  * AV-1 chapters on constraints (e.g. description of legacy status); Objectives
    (e.g. interoperability, availability, other qualities and performances),
    architecture drivers (for instance: DOTPLMFI) and views on legacy systems NSV-1,
    NSV-8, NTV-1.
* NAF V4 grid:
  * A1 to 8, Ar.
  * C1 to C8, Cr.
  * Si, Sr, Li, Lr, Pi, Pr (of legacy).

**Output Views**

* NAFv3 formalism :
  * AV-1 chapters on scope and objectives, constraints, stakeholders, drivers,
    and views: NCV3, NOV-1, NOV-2, NSV-1, NSV-8, NSV-9, NTV-1, NTV-2.
* NAF V4 grid:
  - A1 to 8, Ar.
  - C1 to 8, Cr.
  - Si, Sr, Li, Lr, Pi, Pr.


## Project: Describe Alternatives of Architecture

**Objectives**

Describe, starting from <em>as is</em> architecture and, in consistency with
enterprise architecture principles, alternatives of solution architectures that
meet project’s architecture vision.

**Tasks**

* Validate stakeholders’ key expectations and constraints.
* Confirm shared vision on architecture objectives, stakes, constraints and
  timeframes.
* Get agreement on projects architecture drivers in consistency with enterprise
  drivers.
* Describe identified architecture alternatives, using drivers to orient view
  selection and mappings.
* Review consistency of each alternative (i.e. described by a set of views) using
  audit matrixes.
* Update architecture dashboard.

**Inputs**

* Enterprise portfolios and reference architectures.
* Enterprise motivation data: including drivers.
* Project architecture motivation data: shared architecture vision, stakeholders
  needs / high level requirements and constraints and architecture
  drivers (DLODs, TEPIDOIL, PESTEL, DOTMLPFI).
* Initialised architecture description framework & principles: selected
  description views, selected mapping views, traceability to customer
  requirements and max & minimum number of alternatives.

**Outputs**

Report on architecture description and findings:

* Identified and named architecture alternatives.
* Description of each alternative according to selected views and mappings.
* Gap analysis of each alternative with regards to expectations: milestone shift,
  capability metric, quality factor, technology maturity, etc.
* List of drivers used and justification for unused drivers.
* Updates architecture risk file and fall- back actions.
* Recommendations for trade-off and impacted drivers.
* Up to date architecture dashboard.


**Stakeholders**

* Architect, Project manager</p>
* Representative of plans, operations, legacy systems, standards & technology.
* Security architect, safety architect.
* Representative of regulations and laws.

**Input views**

* NAF v3 formalism:
  * NAV-1 focussing on objectives, selected description views, scope, timeline,
    scenarios, drivers and assumptions).
* NAFv4 grid:
  * A1 to A8, Ar
  * C8, Cr.
  * Si, Sr, Li, Lr, Pi, Pr of legacy.


**Output views**

* NAFv3 formalism:
  * Updated NAV-1 Including description of alternatives from selected viewpoints
    (for instance NCV, NSOV, NOV, NSV, NTV).
  * Description of impacts on NCV3 for each alternative
* NAFv4 grid
  * A1 to A8, Ar.
  * C1 to C8, Cr.

## Project: Evaluate Alternatives of Architecture and Get Trade-off

**Objectives**

* Compare identified alternatives of architecture and highlight key benefit of
  each, according to architecture drivers at both project and enterprise levels.
* Identify and report on the best candidate architecture with regards to needs
  and key assumptions.
* Identify sustainable trade-offs that:
  * Reduce gaps to needs at a satisfactory level for stakeholders.
  * reduce sensitivity to possible changes.

**Tasks**

* Assess architecture consistency with regards to key (weighted) drivers and
  constraints and determine architecture gaps.
* Confirm/update architecture evaluation grid according to project motivation data.
* Confirm/update architecture goals and objectives.
* Conduct evaluation and comparison with regards to architecture goals and
  objectives.
* Determine trade-off proposals ensuring confirmed project objectives are met in
  consistency with enterprise constraints and principles.
* Get decisions from the architecture board (i.e. the board will have assessed trade-
  off proposal architectures with regards to key architecture drivers and constraints.
* Perform gap analysis (Capability coverage, cost, availability, performance)
  on architecture trade-off.
* Update risk data and mitigation actions.
* Baseline 15 trade-off architecture in the architecture repositories, including
  traceability links to rationale for evaluation & decision.
* Update architecture dashboard.

**Inputs**

* Statement of architecture work.
* Initialised evaluation and comparison grid.
* Weighted comparison criteria.

**Outputs**

Report on architecture evaluation activities:

* Score of assessed alternatives of architecture and identified trade-offs.
* Description of the trade-off, including key assumptions, concerned criteria & weights.
* Gap analysis: evaluates the distance of trade-off to architecture objectives
  (capability coverage, effectiveness, performances, cost, availability, risk).
* Updated high level Implementation requirements.
* Migration plan and migration strategy.
* Up to date architecture dashboard.

**Stakeholders**

* Architect, project manager,
* Representative of plan, operations, legacy systems, representative of standard & technology.
* Representative of regulations and laws.
* Security architect and, safety architects.
* Representative of Human factors
* Sponsor.

**Input views**

* NAFv3 formalism:
  * NAV-1: evaluation method, key milestones, constraints, evaluation criteria,
    objectives of trade-offs: what to optimise, why, when?)
    Views to compare
    - NCV3: Expected and proposed.
    - NOVj: expected and proposed.
    - NSVj: constraints and proposed.
    - NTVj: initialised and achievable by alternative.
    - NSOVi: expected and achievable by alternative.

**Output views**

* NAFv3 formalism:
  * NAV-1 updated. compared views and value.
  * NCVi: actual phasing vs expected.
  * NOVj: operational architecture effectiveness.
  * NSVj: impacts on Key interfaces and legacy, system qualities & performance.
  * NTVj: achievability of expected TRLs.
  * NSOVi: impact on expected quality and availability (migration, implementation
    and maintenance).

## Project: Plan Migration

**Objectives**

* Coordinate various project impacted by the defined architecture.
* Elaborate implementation plan from a prioritised list of projects.

**Tasks**

* Analyse & confirm gap analysis with respect to architecture definition.
* Prioritise projects according to description of baseline:
  * Estimate resources for migration using baseline of capability
    phasing, system evolution, system technology evolution,
    technology forecast.
  * Perform cost/benefit analysis foreach project.
  * Identify high risk projects with respect to capability
    dependencies and projects’ milestones.
  * Generate a proposal migration roadmap.
  * Establish a migration plan showing how existing systems will migrate to
    the architecture baseline.
  * Identify impacts and issue change requests on baseline architecture.
    * Architecture descriptions including phasing and mapping views
    * Links to key drivers and constraints.
* List of standard products and required evolutions.

**Inputs**

* Baseline of architecture definition:
  * Descriptions: capability, operational, system, technical, phasing, and mapping views.
  * traceability to architecture trade-off, hypotheses and rationale (motivation data).
  * traceability to top level requirements reflecting (and or having led to)
    architecture trade-offs (motivation data).</p>
  * traceability to standard products/building blocks (refer to project
    architecture repositories).</p>
* Risk data & mitigation action list.

**Outputs**

* Impact analysis report.
* Detailed migration plan.
* If necessary, proposal to update architecture contract.

**Stakeholders**

* Architect, project manager.
* Representatives of plans, operations, legacy systems, standard &amp; technology watch.
* Representative of regulations and laws.
* Security and safety architects.
* Representative of human factors
* Sponsor.


**Input views**

* NAFv3 formalism:
  * NAV-1, NCV-2, NCV-3, NCV-4, NSOV-1, NSOV-2, NSV-1, NSV-7, NSV-8, NSV-9, NTV-1, NTV-2.

* NAFv4 grid:
  * A1 to 8, Ar; C1 to 8, Cr S1to 8, Sr, L1 to 8, Lr, P1 to 8, Pr.

**Output views**

* NAFv3 formalism:
  * NAV-1, NCV-1, NCV-3, NCV-4, NSOV-1, NSOV-2, NSV-1, NSV-8, SV-9, NSOV-1, NSOV-2, NTV-1, NTV-2.

* NAFv4 grid:
  * A1 to 8, Ar, C1 to 8, Cr,S1 to 8, Sr, L1 to 8, Lr, P1 to 8, Pr.

## Project: Govern Application of Architecture

**Objectives**

* Monitor application of architecture in multiple development & deployment projects.
* Formulate recommendations and set a contract between architecture board and impacted projects.

**Tasks**

For each impacted project,

* Identify key architectural requirements.
* Define conformance review plan and reviews according to the project’s timeline.
* Define and share conformance rules and criteria.
* Perform architecture compliance reviews
* Identified architectural gaps and formulate recommendations.
* Document change requests to the baseline architecture.

**Inputs**

* Architecture motivation data.
* Request for architecture work.
* Statement of architecture work.
* Architecture vision.
* Architecture repositories.
* Architecture definition and associated change requests, including roadmap,
  transition scenario of each impacted projects and associated migration plans.


**Outputs**

For each impacted project:

* Status of projects’ compliance to baseline architecture including impact analysis.
  and identified gaps and recommendation to impacted projects.
* Update to architecture state of work.
* Update to project’s architecture.
* Compliance of developed and or deployed solution.
* New change requests (if any) to in the architecture baseline.

**Stakeholders**

* Architect, project manager.
* Representatives (plan, operations, legacy systems, standard, technology watch, regulations and laws).
* Specialists (security, safety, human factors, etc.)
* Sponsors.

**Input views**

* NAFv3 formalism:
  * NAV-1, NCV2, NCV3, NCV-4, NSV-7, NSV-8, NSV-9, NTV-1.
* NAFv4 grid:
  * A1 to A8, Ar;
  * C1-C8; Cr
  * S1-S8, Sr
  * L1-L8, Lr
  * P1-P8, Pr

**Output views**

* NAFv3 formalism :
  * Recommendations to architects on NOV-1 to 3, NSOV-1 to 2, NSV-1 to 8.
  * Change request on NSV-1 and/or NSV-7 and/or NSV-8, NSV-9 and/or NTV-1
* NAFv4:
  * A1-A8, Ar
  * C1-C8; Cr
  * S1-S8, Sr
  * L1-L8, Lr
  * P1-P8, Pr

##Project: Decide on Architecture Changes


**Objectives**

* Ensure that changes to the architecture are decided and managed in a controlled manner.
* Establish an architecture change management process for the new architecture
  that will be used along governance of implementation & deployment projects.


**Tasks**

* Tailor architecture change management process.
* Collect and classify architecture change requests.
* Develop change requirements to meet architecture goals as defined in the
  vision.
* Define the nature and impact of change & get agreements from the architecture
  board.
* Manage risks.

**Inputs**

* Request for architecture work identified at trade-off analysis and decision.
* Statement of Architecture work.
* Architecture vision.
* Architecture repositories.
* Architecture definition document and roadmap.
* Motivation data:
* change requests due to changes identified in enterprise business, technology or standards.
* Transition scenario.
* Architecture state of work.
* Implementation and migration plan, security, safety, maintainability, operational costs, human comfort, configurability,
* Evolution of enterprise and business context since the last architecture change.
* Up to date opportunity reports.
* Up to date Technology maturity status report.

**Outputs**

Agreement for architecture changes.

* Architecture updates.
* New request for architecture work (to initiate a new cycle of the method)
* Updated Statement of architecture work.
* Updated architecture SOW.
* Notification of changes toward architecture stakeholders.

**Stakeholders**

* Architect, project manager.
* Representatives (plan, operations, legacy systems, standard, technology watch, regulations and laws).
* Specialists (security, safety, human factors, etc.).
* Sponsors.

**Input views**

NAFV3: change described from any relevant concept (capabilities, system ,
capability increment milestones, functions, services, organisation, activities,
etc.) and or viewpoint.

* NAF v3 formalisms:
  * NCV-1 to 4, NSOV-1 to 2, NSV- 1 to 11, NTV-1 to 2.
* NAFV4: grid:
  * C1 to 8,S1 to 8; L1 to 8, P1 to 8 Cr, Sr, Lr, Pr.


**Output views**

All Views and perspectives impacted by architecture change. (capabilities,
system , capability increment milestones, functions, services, organisation,
activities, etc.), accepted changes and Impacts.

* NAFV-3 formalism:
  * NCV, NSOV, NSV, NTV.
* NAFv4 grid:
  *  A1-A8 and/or C1-8 and S1-8 or and /or L1-8, P1-8, Ar,Cr,Sr, Lr,Pr.
