---
title: Structure of the Architecture Management Plan
---



# General information


## Document overview

This document is an annex of the Systems Engineering Management Plan (SEMP).

It provides the overall framework for the architecture development of the YSR-SYS (Yellow Search and Rescue System).

It describes the architecture products and their links with the
SE products in order to deliver the system on time, on costs,
on quality.

This document is organised as follows:

1.  This chapter

2.  General information

3.  Architecture Development Overview

4.  Architecture Development Commitment

## Purpose of this Document

Architecture is the fundamental organization of a system embodied in its
components, their relationships to each other and to the environment and
the principles guiding its design and evolution (Ref: NATO Architecture
Framework v3).

The purpose of the architecture management plan (AMP) is to identify and
describe the overall tasks, processes, principles and objectives for the
architecture development during the lifecycle of the YSR\_SYS
Architecture Development

It focuses on critical elements like engaging the stakeholders,
interface definition, requirement engineering, IVQ., technical and
managerial risks accuracy of the description, delivery of the
architecture description and tools used in order to ensure an effective
architecture development and to integrate all types of effort, including
both system engineering and specialty engineering.

The architecture management plan is a living document which will be
updated as required and in conjunction with System Engineering
Management Plan updates. The content of the updates will include an
on-going revision of the current baseline and new baselines established
for each review.

An engineer or technical stakeholder new to the project shall be able to
read the architecture management plan and to understand how the
architecture development will be conducted in support of Systems
Engineering for the project and why it is being done in that way.

This architecture management plan establishes the plan for the
Architecture Development including:

-   The technical key success criteria and the Architecture strategy and
    approach supporting the description of the YSR\_SYS according to
    the requirements.

-   Governance, planning, management, and control of the architecture
    products and deliverables.

-   Schedule objectives for YSR\_SYS Project

In order to complement and support the overall Project Management Plan,
the Architecture Management Plan contains a description of the
Architecture development and the relationship to other activities. The
alignment of the PMP with the architecture management plan and other
management plans should be ensured through peer reviews throughout the
project lifecycle.

The architecture management plan provides a plan for delivering the
architecture of YSR\_SYS in line with the execution of the System
Engineering process. The aim of architecture development is to ensure a
clear and coherent description of YSR\_SYS, according to users’ needs,
including its components, its internal and external liaisons within its
environment.

The architecture management plan is driven by the following goal and
course of action:

-   Goal: Deliver the appropriate information for supporting the system
    acceptance,

-   CoA: capitalize on the existing aspects, support test-cases on new
    critical subjects, align as much as possible through
    model delivery.

# Architecture Development Overview

## Project Overview

### Introduction

The YSR_SYS supports the Yellow security forces by conducting surveillance,
monitoring, recovery and assistance in the water and land environments of the
Yellow country. The YSR_SYS is dedicated to plan, launch, conduct and monitor
rescue missions in maritime and land environment.

The areas of responsibilities (AoR) of the YSR_SYS are:

1.  The borders of the Yellow country with blue and green
    countries (1500km)

2.  Coverage of the Yellow coastline (500km)

3.  Coverage of the Yellow territorial waters,

4.  Coverage of the Yellow Exclusive Economic Zone. ;

Moreover, the Yellow country is committed to support the security
activities directed and coordinated by the Rainbow community. The
YSR_SYS establishes a link between the Yellow security forces and the
Rainbow Forces for Search and Rescue.

For achieving this goal, YSR_SYS conducts the surveillance of the AoR,
while maintaining the capability to launch rescue teams airborne,
maritime or vehicle montyed. Rescue teams are provided by the Border
Guards, Coasts Guards and, when necessary , by requests sent to the
Navy.

The YSR_SYS, is a system made of a limited set of sensors, operational
centres and IT and radio-communications network for supporting and
ensuring safety to distress vehicles or individuals. The YSR_SYS
focuses mostly on:

-   Detection of the position of distress elements

-   Reception of the distress messages

-   Establishment of a searching zone,

-   Coordination of searches activities,

-   Execution of recovery and medical support

The main tasks of YSR_SYS are:

1.  Detection;

2.  Warning,

3.  Command and control,

4.  Search

5.  Rescue.

The solution interacts with the existing systems already deployed in the
Yellow country for maritime surveillance.

The delivery of the system is planned in one release 1.0, followed by a
series of upgrades to be delivered while the system will be operated.

This architecture management plan focuses on the SR 1.0 representing the
“to be” system. The delivery is organized as follows

-   T0 initialization of the contract

-   Requirement Review RR

-   Preliminary Design Review PDR

-   Critical Design review CDR

-   Integration Readiness Review

-   Verification Readiness Review

-   Acceptance review

The implementation follows a model based approach and benefits from the
guidelines of the ISO N15288. It is executed using the XXX Tool.

The system is built on the following structure (PBS).

## Architecture Development Goals and Objectives

-   Describe the system

-   Provide accurate requirements

-   Support integration, verification, validation

## Architecture Development Scope

The architecture scope covers the delivery of a system for search and
rescue for the Yellow country

The architecture covers Capabilities, operational services and system
perspectives

## Interactions with other System Engineering Disciplines

-   Requirement Management activities:

-   Subsystem Design activities:

-   System Integration, Verification and Validation (IVV) activities:

-   Acquisition activities

-   Implementation activities

-   Capability management activities

![](media/image78.emf) Figure 70: Architecture development interactions with other SE disciplines

*Note:* Subsystem design activities follow the same approach: a
subsystem architecture description is derived from the Maritime
Surveillance System architecture, subsystem requirements are derived
from system requirements and subsystem IVV activities are performed to
integrate, verify and validate the subsystems, before to be integrated
at system level.

## Architecture Development Key Stakeholders
----------------------------------------------------------------------------------------------------------------------------------------

-   **The Architecture community:**

-   The end-users community:

    The end users provide concrete feedback on the effectiveness of the
    system and on the environment.

-   The Maritime Surveillance delivery community

    -   The sub-contractor community

    -   The Provider program

![](media/image79.emf) Figure 71: Structure of the project team


Actors

This paragraph details the role of the main actors involved in the
architecture development.

-   Chief engineer

-   System Engineering Team Lead

-   Architect Team

The following diagram details the relationship between the stakeholders
of the program. 3 types of relationships are considered:

-   Approval of documents:

-   Operational coordination

-   Coordination and development:

Figure 72: Relationships between  the architecture stakeholders

## Success Factors


The objectives of a successful delivery of the system rely on:

-   Acceptance of the architecture documents by the relevant
    stakeholders during (RR / PDR / CDR).

-   Compliance of the architecture documents with the CDRL based
    on standard.

-   Delivery on time

The following success factors have been identified for meeting the
objectives:

-   Ability to re-use the legacy of information and architecture already
    delivered,

-   Ability to manage in parallel different Baselines

-   Ability to translate the documentation and information already
    produced

-   Ability to generate the documentation

-   Robustness of the model and of the information in order to support
    spiral

-   Access to the stakeholders’ information for ensuring technical
    accuracy of the architecture description

-   Buy-in of the stakeholders’

-   Quality of the link between the requirements and the architecture
    products

-   Clear description of the interface system

## Architecture Development Strategy

-   The development of the architecture must consider the following
    elements

-   The architecture development is based on the following course of
    action

## Architecture Development Lifecycle

<!-- -->

-   **Internal Goals:**

    -   Initiate a standard development process model with measureable
        deliverables

    -   Capitalize on all identified outbound constraints and
        requirements available

    -   Enable a comprehensive architecture for all relevant releases,.

    -   Enable analysis of requirements based on specialty and
        testability

-   **External Goals:**

    -   Provide reasonable transparency to both Customer and Corporate
        Stakeholders and confidence in foreseeable results.

-   **Method:**

    -   Initiate Model Based Engineering to structure requirements and
        provide a reference solution.

    -   Enable useful management planning both specialized
        (requirements, architecture, IVV) and general


Figure 73: Engineering Strategy



# Architecture Development Commitment

## Scope of Architecture Delivery

In order to limit the delays required for delivering the architecture,
the following architecture documents will be issued

-   **System Subsystem Design Document (SSDD):**

    -   This document provides an operational and system description of
        the System Architecture.

    -   The current version of this document will be updated according
        to future version scope and will be aligned with the System
        Specification documents

    -   The SSDD will be broken in different volumes for providing a
        complete description while remaining manageable. The current
        volumes have been identified:

        -   Operational description

        -   System description

-   **System Specification Documents:**

    -   These documents are considered as an annex of the SSDD document.

    -   The System Specification includes the technical notes elaborated
        during the definition phase of each subject.

<!-- -->

-   **System Bill of Material (System BOM).**

    -   .This document is considered as an annex of the SSDD document.

<!-- -->

-   **Interface Documents (IDD/ICD)**:

    -   These documents provide a description of the system interfaces
        between the system elements of the Search and Rescue System, as
        well as system interfaces with external systems.

    -   The current versions of the interface documents will be updated
        according to the future version scope.



Table** D–1: Mapping between architecture documents and SE Milestones

 DOCUMENT NAME                  RR         PDR         CDR
  ----------------------------- ---------- ----------- -----------
  **System Specifications**     Final         -           -
  **SSDD**                      Draft        Final        -
  **Interface Documents**       Final          -          -
  **System BOM**                 -          Updated      Final

The production of the mentioned system architecture documents is
supported by a Model-Based System Engineering (MBSE) approach, using the
NATO Architecture Framework and the modelling tool.

The operational description of the Maritime Surveillance System
architecture will be covered, as much as possible, through the use of
NATO Operational Views (NOV) such as:

-   NOV-2 (Operational Node Connectivity Description) describing the
    operational interactions between the Maritime Surveillance
    Operators working in the Maritime Surveillance Operation Centres.

-   NOV-3 (Operational Information Requirements) describing who
    exchanges what information, with whom, why the information is
    necessary, and with what quality the information exchange
    must occur.

-   NOV-4 (Organisational Relationship Chart) describing the operational
    organisation of the Maritime Surveillance System, the Maritime
    Surveillance roles among the organisation and their relationships.

-   NOV-5 (Operational Activity Model) describing the operational
    activities performed by the Maritime Surveillance Operators
    working in the Maritime Surveillance Operation Centres.

Table D–2: List of NOV views that will be used in the architecture documents

DOCUMENT TYPE                 NOV-2         NOV-3         NOV-4          NOV-5
----------------------------- ------------- ------------- ------------- -------------
**SSDD**                       X             X               X            X
**System Specifications**      X             X               X            X
**System BOM**                                               X           
**Interface Documents**                                      X           

-   The system description of the Maritime Surveillance System
    architecture will be covered, as much as possible, through the use
    of NATO System Views (NSV) such as:

-   NSV-1 (System Interface Description) describing the systems
    interfaces between the hardware and software components of the
    Maritime Surveillance System as well as their deployment among the
    Maritime Surveillance Sites.

-   NSV-2 (Systems Communication Description) describing the media used
    to interconnect the Maritime Surveillance hardware components
    together and the protocols used to exchange data between the
    hardware and software components of the Maritime
    Surveillance System.

-   **NSV-4 (System Functionality Description)** describing the systems
    functions of the Maritime Surveillance System and their allocation
    to the system elements of the Maritime Surveillance System.

Table D–3: List of NSV views that will be used in the architecture documents**

   DOCUMENT TYPE                NSV-1         NSV-2          NSV-4
  ----------------------------- ------------- ------------- -------------
   **SSDD**                     X              X                X
   **System Specifications**    X                               X
   **System BOM**               X                         
   **Interface Documents**      X              X           

 The consistency of the Maritime Surveillance System architecture
 description will be checked, *as much as possible*, through the use
 of:

-   **NSV-5 (Systems Function to Operational Activity
     Traceability Matrix)** describing the mapping between the Maritime
     Surveillance System Functions and the Operational Activities
     performed by the Maritime Surveillance Operators.

-   **Use of a Requirement Traceability module in MEGA** to link as much
     as possible the Maritime Surveillance System architecture
     description in MEGA with the Maritime Surveillance requirements
     stored in DOORS.

## Architecture Schedule

This diagram describes the scheduling planned for the delivery of
architecture.
