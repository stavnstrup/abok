---
title: Overall Use Case Description
---

The example consists in 2 uses cases related to the development of
architectures with different purposes:

1. *Development of a capability architecture:*
   The Capability architecture is used at national or multinational
   levels[^1] for specifying the design and the implementation of a
   system solution and the integration rules of the national systems in
   multinational capabilities. This architecture governs the procurement
   of the capability. The capability architecture is based on a series of
   strategic documents published either by the nation itself or by
   multinational bodies mainly for interoperability and contained in the
   enterprise architecture. This example addresses the development of
   capability architecture at national level of the Yellow country
   (reference country). The capability architecture is driven by the
   elements of enterprise architecture developed by the Rainbow
   organisation (reference multinational organisation).

2. *Development of a project architecture :*
   The project architecture is used at national of multinational levels
   for acquiring the system solution. The bid is based on the project
   architecture. The industry, through its answers to the bid, provides a
   concrete solution to the description proposed in the project
   architecture. This example addresses the delivery of a system
   dedicated to search and rescue for the “Yellow Country” which is
   member of the Rainbow organization.

The Project architecture will be presented according to the customer
perspective. When possible the answers provided by the industry will
be evocated.

Presenting these 2 perspectives aims at demonstrating a possible use
of the NAF v4 in the acquisition process.

The example demonstrates:

1.  The method to use for selecting and developing the views for each
    type of architecture (Enterprise OA, Capability RA, Project TA).

2.  The use of the “grid” and the necessary content for developing
    concretely the architecture products.

3.  The sequence of tasks for delivering these architectures.

4.  The new sequence related to governance of the architectures.

NATO is engaged in the procurement of military capabilities and
systems, mostly through the common funding process. Currently NAF is
also used by the industry for describing civilian C2 capabilities[^2].

The example reproduces a “NATO like” structure: the Rainbow
organisation.

The selection of a theme related to maritime surveillance tries to
facilitate the transfer of military only to civilian activities. This
theme can bridge the gap with the examples related to search and
rescue which have already been used by tools and software editors.

# The environment

## General Presentation

This example takes place in a region grouping different countries named
Blue, Yellow and Green which have set up a multinational organization
Rainbow. The Rainbow organization acts as a supra national body for
security, safety and cooperation between the member countries.

The Rainbow Organization has set up a dedicated body, the RSSC “Rainbow
Safety and Security Committee” for coordinating the activities related
to controlling vessels, vehicles and aircrafts cruising in the land,
maritime, coastal and airspace environments. The RSSC is the
coordinating body between the different countries. Some zones (mostly
the countries EEZ) and responsibilities (coordination of maritime
traffic and safety at sea) have been transferred at the RSSC level.

To achieve a safe and secure environment, a set of rules and means have
been established. These rules systems and means are owned, procured and
operated by the member countries. The RSSC has established a central
organization, an operation centre the Rainbow Operation Centre for
Security (ROCS) for coordinating information and activities at
multinational level.

The example describes the approach followed by the Architects of the
Yellow country for developing the necessary products for the acquisition
of a Search and Rescue system. This approach includes the development of
a Capability and project architectures.

The context of the Yellow country is as follows:

1.  Specific environment

    1.  Yellow sits between Blue and Green.

    2. Yellow has a big human force for running the
        maritime surveillance.
    {: type="i"}

2.  Overall

    1.  Immigration and movement of population needs to be
        strictly monitored.

    2. Safety at sea for migrant population is at stake.

    3. The commercial maritime traffic must be controlled.

    4. Rainbow coordinates the control of traffic on national EEZ of
       the countries.

    5.  Rainbow wants to implement a synchronized capability for
        surveillance, custom control and safety.
    {: type="i"}

3.  Maritime surveillance objectives :

    1.  Strategic

        1. Development of an effective maritime surveillance system
           including search and rescue capability.

        2. Need to ensure control on the movement of people goods and
           material

        3. Better linkage with neighbours and with multinational Level.
        {: type="i"}

    2.  Economic

        1. Reduce the costs of maritime surveillance.

        2. Re-use of the legacies (radio systems, radars).
        {: type="i" start="4"}

    3.  Technical

        1. Describe the capability of the maritime surveillance to develop
           in the yellow country for the 5 to 10 coming years.

        2. Integrate the capabilities of maritime surveillance of the
           Rainbow community.

        3. Increase interoperability between yellow forces and with
           Rainbow member states.
        {: type="i" start="6"}

    4.  Operational

        1. Common operational procedures exist at Rainbow level

        2. Interaction is in place between coast guards and civilian
           security actors (Heli-OC- Hospitals).

        3. Interaction is in place with other actors.
        {: type="i" start="9"}
    {: type="a"}
{: type="a"}


The following architecture elements already exist:

1.  Rainbow has developed the enterprise architecture on
    maritime surveillance.

2.  The Rainbow surveillance system connects the national systems.

3.  Blue and Green have engaged the same effort, they have capability
    Level Architecture and Blue is equipped with a SAR system.

4.  Each system already fielded has a complete set of architectures.
{: type="a"}

The following elements characterize architecture, systems, units and
effects.

1.  Each system has been developed with architecture and
    requirements bases.

2.  A contract is planned for developing the Yellow Maritime Search and
    Rescue System (YMSS).
{: type=a}

The following diagram provides the C2 of the Rainbow organisation
(Capability Vision : goals and objectives).

{%include rasterfigure.html url="image4.png" description="Goals and objectives of the Rainbow Organization at overarching architecture" %}


## Business Area

The Rainbow countries conduct maritime security operations using their
intervention units, vessels, detection sites and operation centres. The
nations monitor the vessels cursing in territorial waters and in the
Exclusive Economic Zone (EEZ). National operation pictures developed by
countries support national situation awareness and are merged, fused and
coordinated by the ROCS.

The following diagram provides a (NAF v4) L2 view of the Yellow
Enterprise architecture of maritime surveillance, which includes Search
and Rescue.

{%include rasterfigure.html url="image5.png" description="L2 NOV 2 view of maritime surveillance" %}

# Maritime Security

Maritime security relies on the effective execution of command and
control, maritime surveillance and maritime safety missions. The
following tasks fall under the responsibility of maritime surveillance:

-   Observe;

-   Detect;

-   Classify;

-   Identify.

To ensure the free circulation of goods and people through regulations,
management and technical solutions are needed. The following diagram
provides a C1 of the enterprise architecture of Yellow country on the
specific aspects of search and rescue.

{%include rasterfigure.html url="image6.png" description="Example of a C1 view of the enterprise architecture of the Yellow country" %}


The main events to detect are as follows:

-   Pollution,

-   Petrol Pollution;

-   Wildfires;

-   Epidemical phenomena;

-   Migration movements;

-   Trafficking;

-   Suspicious movements which could hide terrorist activities.

The mission of maritime security consists in providing a Common
Operational Picture (Common Recognized Operational Picture) for
supporting Situation Awareness over vessels, routes, shipments, ports
access for implementation of the law and the execution of emergency
measures.

# Search and rescue (SAR)

The Search and Rescue (SAR) mission minimizes the loss of life,
injury, and property damage or loss at sea by finding and rendering
aid to those in distress. The Yellow Coast Guard executes this mission
by:

-   Conducting search planning and coordinating SAR response;

-   Searching for, locating, and rescuing mariners in distress;

-   Providing medical advice, assistance, or evacuation;

-   Providing, when necessary, persons in distress safe transport
    to shore.

# Detailed situation of the example

The example addresses the Yellow country situation and the development
of the capability architecture. It focuses on describing how Yellow
country will organize the national maritime surveillance systems for
supporting the Rainbow organization.

The following elements describe the multinational perspective.

1.  **An enterprise architecture of the Rainbow community systems is available:**

    Providing an overall description of the safety and security
    surveillance for the Rainbow organization (the description includes
    the full scope of safety and security and land, maritime, coastal, and
    airspace levels). The Enterprise architecture (OA) addresses the
    following elements at a 10 to 15 years’ time-frame:

    1.  Actors

    2.  Capabilities

    3.  Operational Activities

    4.  Information produced and exchanged

    5.  The whole International cooperation domain

    6.  Roadmaps are included for

        1.  Technology

        2. Capabilities

        3. Doctrine

        4. Interoperability
        {: type="i"}
   {: type="a"}

2.  **A series of architecture objectives and measures of effectiveness
      for the architecture development have been delivered including:**

      1. The number of concurrent missions which can be monitored and
         conducted by the systems of the Rainbow organizations, this
         number is derived to each nation too;

      2. The scope of search by type of assets and by zone to search;

      3. The number of nations capable of collaborating/interfering
         during an operation;

      4. The duration of the different missions.
      {: type="a"}

3.  **For the specific aspects of maritime surveillance the following
      MoEs have been identified:**

      1. The Scope of surveillance (type of vessels, types of tracks and
         the definition of the area of surveillance (AoS)).

      2.  The Number of objects or targets which can be detected and
          monitored in the AoS.

      3.  The number of objects or target equipped with AIS identification
          system which can be monitored in the AoS.

      4.  The Number of surveillance stations (including the Load
          by Station).

      5.  The organization of the system:

        1.  Manpower;

        2. Maintenance;

        3. Training ;

        4. Structures and relationships.
        {: type="i"}
      {: type="a"}

4.  The RSSC has already published a capability architecture which
    contains the following elements to be used for developing the
    Yellow country capability architecture. The outline of the content
    of this architecture includes:

    1.  Purpose of the architecture

        1.  Actors;

        2. Operational activities, messages, operational nodes;

        3. Capabilities;

        4. Services;

        5.  Operational functions;

        6. Systems;

        7. Interfaces;

        8. Standards.
        {: type="i"}
    {: type="a"}

**Description of the work to be conducted**

The architect of the Yellow country will:

1.  Develop the capability architecture for the SAR component of
    maritime surveillance of the Yellow country based on the
    information from the Rainbow enterprise and capability
    architectures,

2.  Develop the project architecture of the Yellow country SAR system in
    line with the capability architecture .

3.  This example will describe the steps followed by the architect for
    producing the architecture products according to the NAF
