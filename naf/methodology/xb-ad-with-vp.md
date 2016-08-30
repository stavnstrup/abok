---
title: Architecture description with viewpoints
---

# Introduction

In this NAF v4 release, the set of views described in Chapter 3 is very
close to the NAF v3 sub-views. Even if the formalism provided for each
NAF v4 view is improved with usage of the IDEAS and MODEM foundation,
this formalism remains in the same spirit as NAF v3. This normally eases
the transition from NAF v3 to v4.

Note: There is a naming shift between NAF v4 and v3. This remaining is
done to get NAF v4 closed to ISO/IEC/IEEE 42010­ terms and concepts. NAF
v3 views become NAF v4 viewpoints and NAF v3 sub-views are now NAF v4
views.

The main difference between NAF v4 and v3 for an architect beginning
with the new version is the notion of Architecture Grid. This grid is to
be thought as taxonomy where views are distributed in semantic groups
according 2 dimensions. This taxonomy is structure to facilitate
explanation of the view.

The architecture grid can be used directly for architecture description,
however ­­­­­ most of the time architecture description is structured
according to viewpoints related to the concerns of the stakeholders.
ISO/IEC/IEEE 42010­ is a standard promoted this practice.

# Description with NAF v3 viewpoints


In NAF v3, viewpoints are predefined even if this does not prevent
architects to change or modify them. Aim of using predefined viewpoints
is to get architectures defined with the same structure in an
enterprise. This architecture alignment eases at least architecture
governance, architecture management, comparison of architectures and
management of architecture repositories. If architecture structures vary
from projects to others, governance and management will be more
complicated; but remain possible as long as architectures are built
using the same set of views.

In NAF v3, formalism is structured according to the following views (now
called viewpoints).

Table -1 – NAF v3 viewpoints and views

  Viewpoint               Views     Aim
  ----------------------- --------- -------
  All-views               NAV-\*    to provide objectives, stakes and context to be considered for the architecture and the entity of interest (e.g. system or product) cover by this architecture. This viewpoint also provides the summary of the architecture with view selection; and common terms and concepts.
  Operational viewpoint   NOV-\*    to describe the architecture as seen by users and operators of the entity of interest.
  Capability viewpoint    NCV-\*    to explain operational capabilities considered with regards to the architecture.
  System viewpoint        NSV-\*    to describe with the system builder viewpoint.
  Technical viewpoint     NTV-\*    to provide the standards and products used over for development and exploitation over the time.
  Service viewpoint       NSOV-\*   to explain how operational, applicative and technical services are used as paradigm for interaction and for activity provision towards service customers.
  Program viewpoint       NPV-\*    to give the programmatic with the acquirer or the provider viewpoint

With an architecture described with NAF v3 viewpoints, the architecture
views are simply used per group according to their family names as shown
by the table above.

# Using the grid concept with NAF v3 viewpoints

In 2005 and 2006, NATO and the Open Group performed a joint study (See
The Open Group Architecture Framework Version 8.1.1, Enterprise Edition,
ISBN: 1-931624-62-3) demonstrating how to express an architecture with
viewpoints and levels of abstraction.

{%include rasterfigure.html url="togaf-exp-properties.png" description="TOGAF V8.1 - Expected properties of the Architectural Model" %}

This model can be used to define an architecture grid with the NAF v3,
as shown by the figure bellow.

{%include figure.html url="grid-naf3-vp.svg" description="Grid with NAF v3 viewpoints"%}


Columns can be used to express contextual, transitional, conceptual,
logical and physical properties of the architecture.

# Grid concept for other architectural models

Architecture grids can be structured to show viewpoints in order to
segregate the stakeholder concerns, and architecture aspects, levels of
abstraction or any other architectural properties.

With this approach, for example, business viewpoints can be split into
provider viewpoints and acquirer viewpoint. This is necessary when the
contracting is not done with a simple B2B model; but with several
providers and one or several acquirers.

Architectural properties (columns of the grid) can express
non-functional properties, as shown in the figure bellow.


{%include figure.html url="grid-other-vp.svg" description="Grid with other viewpoints"%}


Note: This definition of viewpoints can also be an opportunity to
suppress capability viewpoints and services viewpoints since there are
not “true” viewpoints as long as ISO/IEC/IEEE-42010 is considered, I.e.
if a capability is considered as “an ability to perform an action or a
function”. Concept of capability can be considered with user/operator,
acquirer, provider and builder viewpoints. If a service is considered as
an interaction paradigm, this concept can also be considered with the
previous viewpoints. This means that capability and service are not
concepts that have to be described in separate viewpoint.

# Using the grid concept for description with viewpoints and documents

Documents considered during the architecture activities could be OCD
(operational concept document on user side), URD (user requirement
document on user side), SRD (system requirement document on acquirer
side), IER (information exchange requirements), AMP (architecture
management plan on provider side), SSS (on provider side), SSDD
(provider side), and IVVP (on provider side).

In that case, the grid can structure:

-   Rows can be viewpoints.

-   Columns can be documents

-   Cells identify the architecture views developed per viewpoint and
    delivered per document.
