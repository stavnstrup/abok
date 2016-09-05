---
title: Introduction
permalink: /:path/index.html
---

# Introduction to MODEM

MODEM is the meta model that underpins the NAF. It, defines the structure of the
underlying architectural information that is presented in the NAF Viewpoints.
Individually, Viewpoints can only provide consistency in terms of the type of
information produced; i.e. it can be recognised that one Viewpoint is a logical
model, whilst another is a physical resource model. However, similar information
may be represented in more than one Viewpoint and there may be important
relationships between the information in different Viewpoints that should be
captured. This consistency between Viewpoints is provided by a reference model
(or Meta Model), which identifies all the types of architectural elements
represented across all the Viewpoints, and the relationships between those
concepts. MODEM, therefore, provides semantic rigour for the NAF.

A high-level view of the NAF Meta-Model (MODEM) is shown below:

{% include rasterfigure.html url="image1.emf" description="High-Level View of MODEM" %}


{% include rasterfigure.html url="image1.emf" description="High Level View with Deployed layer removed" %}




# Modelling Notation

The UML model for MODEM uses the following colour scheme. :


* Sky-blue = Type
* Orange = IndividualType
* Lilac = Powertype
* Light-green = TupleType
* Dark-grey = Individual
* Yellow = NamingScheme


For MODEM, in addition to the element fill colour, the border colour is used to
indicate the NAF Viewpoint, using the following standard colours:

* Yellow = Architecture Meta-Data layer Viewpoints
* Green = Concepts layer Viewpoints
* Purple = Service Specifications layer Viewpoints
* Blue = Logical Specifications layer Viewpoints
* Orange = Physical Resource Specifications layer Viewpoints
* Pink = Architecture Roadmap, e.g. Acquisition Viewpoints

* Grey = Technology & Standards Viewpoints


In addition, placeable types (Tuples, TupleTypes, TupleTypeTypes, etc.) are
displayed with thin borders whilst all other elements have thick borders.

Where additions were necessary, these additions are shown with a red border.

# Viewpoint Meta-Models and Element Lists

In the remainder of this Chapter, the meta-model and a list of elements is
presented for each Viewpoint. If required, the user may visit the accompanying
website to access more readable versions of the individual meta-models.
