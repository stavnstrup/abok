---
title: Architecting for the enterprise scope
---


Architecture elaborated to master the overall enterprise business are
typically:

-   Architecture of the enterprise itself. The enterprise is therefore
    analysed with a systemic approach from the enterprise internal and
    external stakeholders’ viewpoints. This allows formalising the
    enterprise processes, roles, information system(s), assets, etc.

-   Architectures used by the programmes and the projects of the
    enterprise in order to deliver the enterprise systems/products
    required by internal and external contracts.

In both cases these architectures provide directions and guidance for
the enterprise programmes and projects in charge of developing and
maintaining either the enterprise itself or the enterprise
systems/products.

These architectures have to be considered as an input for enterprise
governance.

# Overview of the Enterprise Architecting activities

+--------------------------------------+--------------------------------------+
| **Stages**                           | **Description**                      |
+======================================+======================================+
| Enterprise: Architecture Landscape\  | Put in place the enterprise          |
| (AL)                                 | architecture context with            |
|                                      | identification of the stakeholders,  |
|                                      | and definition the organisational    |
|                                      | context, architecture principles,    |
|                                      | capabilities, processes, outcomes,   |
|                                      | roles and responsibilities.          |
+--------------------------------------+--------------------------------------+
| Enterprise: Architecture Vision\     | Get an updated enterprise            |
| (AV)                                 | architecture vision with related     |
|                                      | stakeholders, key-requirements and   |
|                                      | contraints, architecture management  |
|                                      | plan, relevant activities and        |
|                                      | outcomes.                            |
+--------------------------------------+--------------------------------------+
| Enterprise: Architecture Description | Define the enterprise architecture   |
|                                      | viewpoints according to the concerns |
| (AD)                                 | of the stakeholders and provide an   |
|                                      | approved set of alternatives of      |
|                                      | enterprise architectures.            |
+--------------------------------------+--------------------------------------+
| Enterprise: Architecture Evaluation\ | Define the evaluation criteria       |
| (AE)                                 | according to the concerns of the     |
|                                      | stakeholders, evaluate each          |
|                                      | alternative of enterprise            |
|                                      | architectures, get an approved       |
|                                      | selection among the alternatives of  |
|                                      | enterprise architectures for         |
|                                      | application and possibly request for |
|                                      | evolution.                           |
+--------------------------------------+--------------------------------------+
| Enterprise: Plan Migration\          | Get an updated transformation        |
| (PM)                                 | roadmap for application of the       |
|                                      | enterprise architecture with a       |
|                                      | rationale and a governance model.    |
+--------------------------------------+--------------------------------------+
| Enterprise: Architecture Governance\ | Check for the application of the     |
| (AG)                                 | enterprise architecture according to |
|                                      | the migration plan and provide       |
|                                      | recommendation.                      |
+--------------------------------------+--------------------------------------+
| Enterprise: Architecture Changes\    | Decide on the requests for change,   |
| (AC)                                 | evaluate the level of applicability  |
|                                      | of the enterprise architectures and  |
|                                      | decide if iterations are needed to   |
|                                      | update the enterprise architectures. |
+--------------------------------------+--------------------------------------+
| Enterprise: Motivation & Dashboard\  | Put in place a selection of data and |
| (MD)                                 | build a dashboard reflecting the     |
|                                      | motivation of the stakeholders.      |
|                                      | Maintain the reference libraries and |
|                                      | architecture repositories to be in   |
|                                      | line.                                |
+--------------------------------------+--------------------------------------+

Note: For governance activities, it is highly recommended to consider
COBIT[^12] and ISO
38500[^13] in addition to NAF chapter 2.

# Enterprise Architecting activities

+--------------------------------------------------------------------------+
| **Enterprise: Architecture Landscape (AL)**                              |
+==========================================================================+
| **Objectives**                                                           |
+--------------------------------------------------------------------------+
| -   To formalise the organisational context where the enterprise         |
|     architecture activities take place.                                  |
|                                                                          |
| -   To identify the stakeholders of the enterprise architectures and     |
|     their related activities, with their expectations.                   |
|                                                                          |
| -   To define the constraining enterprise architecture principles.       |
|                                                                          |
| -   To define the enterprise architecture process with roles,            |
|     responsibilities, work-products and workflow.                        |
|                                                                          |
| -   To define the capabilities for enterprise architecture work.         |
|                                                                          |
| -   To get a commitment on the enterprise architecture process and usage |
|     of its outcomes.                                                     |
+--------------------------------------------------------------------------+
| **Inputs**                                                               |
+--------------------------------------------------------------------------+
| -   Enterprise strategy, policies, direction and guidance.               |
|                                                                          |
| -   Enterprise motivation model: business principles, business goals,    |
|     and business, driver, etc.                                           |
|                                                                          |
| -   Agreement on NAF usage, with possibly some other working references. |
+--------------------------------------------------------------------------+
| Recommended views                                                        |
+--------------------------------------------------------------------------+
| -   NAF v3 formalism:                                                    |
|                                                                          |
|     -   NAV-1 to 2, NAV-3[^14].           |
|                                                                          |
| -   NAF v4 Grid cells:                                                   |
|                                                                          |
|     -   A1 to 7.                                                         |
+--------------------------------------------------------------------------+


+--------------------------------------------------------------------------+
| **Enterprise: Architecture Vision (AV)**                                 |
+==========================================================================+
| **Objectives**                                                           |
+--------------------------------------------------------------------------+
| For a particular cycle of architecture activities:                       |
|                                                                          |
| -   To review the list of the stakeholders for the architected entity.   |
|                                                                          |
| -   To formalise and update the key-requirements and constraints from    |
|     the architecture stakeholders.                                       |
|                                                                          |
| -   To get the updated architecture vision.                              |
|                                                                          |
| -   To plan the architecture activities to be performed for the          |
|     architecting cycle.                                                  |
|                                                                          |
| -   To check the coherency by other enterprise architecture activities   |
|     on other enterprise architectures and other possible parallel        |
|     architecture cycles.                                                 |
|                                                                          |
| -   To get approval to the architecture management plans and outcomes.   |
+--------------------------------------------------------------------------+
| **Inputs**                                                               |
+--------------------------------------------------------------------------+
| -   Request for the enterprise architecture evolution.                   |
|                                                                          |
| -   Enterprise motivation data.                                          |
|                                                                          |
| -   Organisational model for enterprise architecture.                    |
|                                                                          |
| -   Pre-existing enterprise architecture vision.                         |
|                                                                          |
| -   Enterprise architecture landscape.                                   |
+--------------------------------------------------------------------------+
| Recommended views                                                        |
+--------------------------------------------------------------------------+
| -   NAF v3 formalism:                                                    |
|                                                                          |
|     -   NAV-1 to 3.                                                      |
|                                                                          |
|     -   A consistent set of NAV-1, NOV-1, NCV-1, NSV-1 and NSOV-1.       |
|                                                                          |
| -   NAF v4 Grid cells:                                                   |
|                                                                          |
|     -   A3, Ar.                                                          |
|                                                                          |
|     -   C5.                                                              |
|                                                                          |
|     -   Cr, Sr, Lr, Pr.                                                  |
|                                                                          |
|     -   C1, S1, L1, P1, A1.                                              |
|                                                                          |
|     -   A2 (Architecture Context Diagram (ACD)), L2, C2.                 |
+--------------------------------------------------------------------------+

+--------------------------------------------------------------------------+
| **Enterprise: Architecture Description (AD)**                            |
+==========================================================================+
| **Objectives**                                                           |
+--------------------------------------------------------------------------+
| -   To validate the viewpoints with respect to their concerns of         |
|     the stakeholders.                                                    |
|                                                                          |
| -   To provide one or several alternatives of description for an         |
|     enterprise architecture through these viewpoints.                    |
|                                                                          |
| -   To get an agreement of the alternatives of enterprise architectures. |
+--------------------------------------------------------------------------+
| **Inputs**                                                               |
+--------------------------------------------------------------------------+
| -   Request for architecture work with a statement of work.              |
|                                                                          |
| -   Enterprise architecture vision (list of stakeholders, concerns,      |
|     viewpoints, Architecture overview).                                  |
|                                                                          |
| -   Enterprise motivation data.                                          |
|                                                                          |
| -   Architecture principles.                                             |
|                                                                          |
| -   Pre-existing enterprise architecture description in the enterprise   |
|     architecture repositories.                                           |
|                                                                          |
| -   Enterprise architecture landscape.                                   |
+--------------------------------------------------------------------------+
| Recommended views                                                        |
+--------------------------------------------------------------------------+
| -   NAF v3 formalism:                                                    |
|                                                                          |
|     -   NCV-1 to 7, NOV-1 to 7.                                          |
|                                                                          |
|     -   NSV-1 to 12, NSOV-1 to 5, NTV1 to 3.                             |
|                                                                          |
| -   NAF v4 Grid cells:                                                   |
|                                                                          |
|     -   C1 to 8, Cr, S1 to 8, Sr, L1 to 8,Lr, P1 to 8, Pr.               |
|                                                                          |
|     -   A1, A2 (ACD), A8.                                                |
+--------------------------------------------------------------------------+

+--------------------------------------------------------------------------+
| **Enterprise: Architecture Evaluation (AE)**                             |
+==========================================================================+
| **Objectives**                                                           |
+--------------------------------------------------------------------------+
| -   To formalise the evaluation criteria according to the concerns of    |
|     the stakeholders.                                                    |
|                                                                          |
| -   To evaluate each candidate enterprise architecture.                  |
|                                                                          |
| -   To evaluate the risk, cost, value and opportunities for each         |
|     enterprise architecture.                                             |
|                                                                          |
| -   To select the enterprise architectures for application.              |
+--------------------------------------------------------------------------+
| **Inputs**                                                               |
+--------------------------------------------------------------------------+
| -   Request for architecture work with a statement of work.              |
|                                                                          |
| -   Enterprise architecture vision (list of stakeholders, concerns       |
|     and questions).                                                      |
|                                                                          |
| -   Enterprise motivation data.                                          |
|                                                                          |
| -   Architecture principles.                                             |
|                                                                          |
| -   Pre-existing enterprise architecture. evaluation elements in the     |
|     enterprise architecture repositories.                                |
|                                                                          |
| -   Enterprise architecture landscape.                                   |
|                                                                          |
| -   Enterprise architectures descriptions.                               |
+--------------------------------------------------------------------------+
| Recommended views                                                        |
+--------------------------------------------------------------------------+
| Same as **Enterprise:** **Architectures Description (AD)**               |
+--------------------------------------------------------------------------+

+--------------------------------------------------------------------------+
| **Enterprise: Plan Migration (PM)**                                      |
+==========================================================================+
| **Objectives**                                                           |
+--------------------------------------------------------------------------+
| -   To get updated a roadmap for enterprise projects which progressively |
|     apply the enterprise architectures.                                  |
|                                                                          |
| -   To demonstrate that enterprise transformation satisfies the          |
|     enterprise motivation data.                                          |
|                                                                          |
| -   To provide a governance model for application of the                 |
|     enterprise architectures.                                            |
+--------------------------------------------------------------------------+
| **Inputs**                                                               |
+--------------------------------------------------------------------------+
| -   Request for architecture work with a statement of work.              |
|                                                                          |
| -   Enterprise architecture vision (list of stakeholders and concerns,   |
|     transformation outline).                                             |
|                                                                          |
| -   Enterprise motivation data (including policies and rules             |
|     for transformation).                                                 |
|                                                                          |
| -   Architecture principles.                                             |
|                                                                          |
| -   Pre-existing enterprise transformation actions.                      |
|                                                                          |
| -   Enterprise architecture landscape.                                   |
+--------------------------------------------------------------------------+
| Recommended views                                                        |
+--------------------------------------------------------------------------+
| -   NAF v3 formalism:                                                    |
|                                                                          |
|     -   NPV-1 to 2, (NCV-3, NSV-8, NSV-9), NTV-2                         |
|                                                                          |
| -   NAF v4 Grid cells:                                                   |
|                                                                          |
|     -   Cr, Sr, Lr, Pr, Ar.                                              |
|                                                                          |
|     -   C8, S8, L8, P8, A8.                                              |
|                                                                          |
|     -   C3                                                               |
|                                                                          |
|     -   Mapping of Lr over Cr (NPV-2)                                    |
+--------------------------------------------------------------------------+

+--------------------------------------------------------------------------+
| **Enterprise: Architecture Governance (AG)**                             |
+==========================================================================+
| **Objectives**                                                           |
+--------------------------------------------------------------------------+
| -   To ensure correct application of the enterprise architectures in the |
|     enterprise transformation.                                           |
|                                                                          |
| -   To provide recommendation towards the governance authority of the    |
|     enterprise transformation.                                           |
+--------------------------------------------------------------------------+
| **Inputs**                                                               |
+--------------------------------------------------------------------------+
| -   Request for architecture work with a statement of work.              |
|                                                                          |
| -   Enterprise architecture vision (governance outline).                 |
|                                                                          |
| -   Enterprise motivation data (including policies and rules             |
|     for transformation).                                                 |
|                                                                          |
| -   Enterprise transformation plan.                                      |
|                                                                          |
| -   Portfolio of enterprise projects.                                    |
|                                                                          |
| -   Architecture contract per project or programme.                      |
+--------------------------------------------------------------------------+
| Recommended views                                                        |
+--------------------------------------------------------------------------+
| -   NAF v3 formalism:                                                    |
|                                                                          |
|     -   NAV-1, NOV-1, NCV-1, NSV-1, NPV-1 to 2                           |
|                                                                          |
| -   NAF v4 Grid cells:                                                   |
|                                                                          |
|     -   A1 to 8, Ar                                                      |
|                                                                          |
|     -   C1 to 2, S1 to 2, L1 to 2, P1 to 2                               |
+--------------------------------------------------------------------------+

+--------------------------------------------------------------------------+
| **Enterprise: Architecture Changes (AC)**                                |
+==========================================================================+
| **Objectives**                                                           |
+--------------------------------------------------------------------------+
| -   To transform the requests for changes into decisions for changes in  |
|     the enterprise architecture landscape, enterprise architectures,     |
|     architecture principles and enterprise motivation data.              |
|                                                                          |
| -   To decide on the level of applicability of the                       |
|     enterprise architectures.                                            |
|                                                                          |
| -   To decide on the need to iterate for one or several enterprise       |
|     architectures (stop criteria).                                       |
+--------------------------------------------------------------------------+
| **Inputs**                                                               |
+--------------------------------------------------------------------------+
| -   Change requests for enterprise architectures.                        |
|                                                                          |
| -   Enterprise motivation data.                                          |
|                                                                          |
| -   Organisation model for enterprise architecture.                      |
|                                                                          |
| -   Enterprise architecture vision.                                      |
|                                                                          |
| -   Enterprise architecture landscape.                                   |
+--------------------------------------------------------------------------+
| Recommended views                                                        |
+--------------------------------------------------------------------------+
| -   NAF v3 formalism:                                                    |
|                                                                          |
|     -   (Inputs) All read-only architecture views                        |
|                                                                          |
|     -   (outputs) NAV-1 (decisions)                                      |
|                                                                          |
| -   NAF v4 Grid cells:                                                   |
|                                                                          |
|     -   A5, A6, A7                                                       |
+--------------------------------------------------------------------------+

+--------------------------------------------------------------------------+
| **Enterprise: Motivation & Dashboard (MD)**                              |
+==========================================================================+
| **Objectives**                                                           |
+--------------------------------------------------------------------------+
| -   To manage a consistent access to the enterprise motivation data.     |
|                                                                          |
| -   To provide consistent architecture dashboard related to activities,  |
|     enterprise architecture landscape (including enterprise              |
|     architectures in repositories) and enterprise resources.             |
+--------------------------------------------------------------------------+
| **Inputs**                                                               |
+--------------------------------------------------------------------------+
| -   Enterprise request for update of the enterprise motivation data.     |
|                                                                          |
| -   Enterprise external and internal architectures and                   |
|     architecture elements.                                               |
|                                                                          |
| -   Enterprise external and internal references.                         |
|                                                                          |
| -   Organisational model for enterprise architecture.                    |
|                                                                          |
| -   Enterprise architecture landscape.                                   |
+--------------------------------------------------------------------------+
| Recommended views                                                        |
+--------------------------------------------------------------------------+
| -   NAF v3 formalism                                                     |
|                                                                          |
|     -   NAV-1.                                                           |
|                                                                          |
| -   NAF v4 Grid cells:                                                   |
|                                                                          |
|     -   A1 (meta-description), A7 (meta-description), A5 (content).      |
+--------------------------------------------------------------------------+


[^12]: COBIT (Control Objectives for Information and related Technology): COBIT 5 is a framework for IT governance provided by the Information Systems Audit and Control Association (ISACA).
[^13]: ISO/IEC 38500:2015 Information technology -- Governance of IT for the organisation
[^14]: These views describe the structure of the landscape; not the content.
