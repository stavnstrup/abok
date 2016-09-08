---
title: PR – Configuration Management
legacy: "NAF v3: NSV-8; MODAF: SV-8"
---

The Pr Configuration Management View depicts the whole lifecycle view of a
Resource, describing how its configuration changes over time.

## Concerns Addressed

* Product Lifecycle Management.
* Version Control.
* Release Scheduling.

## Background

The Pr View provides an overview of how a Resource Type structure changes over
time (note that NAF v3.1 only allowed for Capability Configurations whereas now this
is opened up to all Resource Types). It shows the structure of different versions of
Resource Type (usually Capability Configurations or Service Implementations)
mapped against a timeline.

## Usage

* Development of incremental acquisition strategy.
* Configuration Management.
* Planning technology insertion.

## Representation

* Timeline view.
* ‘Herringbone’ diagram.

## Detailed View Description

A Pr view provides a rich definition of how the architecture and its capabilities are
expected to evolve over time, especially when linked together with other evolution
views such as Lr, Lines of Development, Cr, Capability Roadmap, and A8, Standards
Forecast.

In this manner, the view can be used as an architecture evolution project plan or
transition plan. In meta-model terms, a Pr view is constructed from data specified in
the Lr, Lines of Development, and P2, Resource Structure views, though there may
be several P2 views – one for each version of the configuration.

A Pr view can describe legacy, current and future Resource Types against a timeline.
Using similar modelling elements as those used in the P2, Resource Structure View,
the view shows the structure of the Resource Types under configuration control.
Resource interactions which take place within the Resource Type boundaries may
also be shown.

The changes depicted in the Pr view are derived from the project milestones that are
also shown in Lr, Lines of Development:

Figure 3-72: Example Pr View Showing SAR configuration

## Key Elements and Their Relationships


## Meta-Model

The detailed meta-model and element list for Pr, Configuration Management, is at
paragraph 4.5.11.
