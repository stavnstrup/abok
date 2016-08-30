---
title: Architecture Meta-Data Layer
---

# A1 – Meta-Data Definitions


{%include rasterfigure.html url="image39.png" width="604" height="353" description="A1 Logical Diagram" %}


<table>
<thead>
<tr>
<th>Element Name</th>
<th>Element Kind</th>
<th>Definition</th>
</tr>
</thead>
<tbody>
<tr>
<td>ADElement</td>
<td>Type</td>
<td><p>From ISO42010:</p>
An AD element is any construct in an architecture description. AD elements are the most primitive constructs discussed in this International Standard. Every stakeholder, concern, architecture viewpoint, architecture view, model kind, architecture model, architecture decision and rationale (see 4.2.7) is considered an AD element. When viewpoints and model kinds are defined and their models are populated, additional AD elements are introduced.</td>
</tr>
<tr>
<td>ArchitectureDescription</td>
<td>Type</td>
<td>A work product used to express an architecture.</td>
</tr>
<tr>
<td>ArchitectureModel</td>
<td>Type</td>
<td>No specific definition provided in ISO42010.</td>
</tr>
<tr>
<td>ArchitectureView</td>
<td>Type</td>
<td>A work product expressing the architecture of a system from the perspective of specific system concerns.</td>
</tr>
<tr>
<td>DublinCoreTag</td>
<td>Type</td>
<td>A MetaDataCategory that is a DublinCore tag.</td>
</tr>
<tr>
<td>MetaData</td>
<td>Type</td>
<td>A StringRepresentation that can be applied to any element in the architecture.<br />Note: wherever possible, standard Meta-Data types should be used - e.g. conforming to Dublin Core<br />Note for MOD Users: The MOD Meta Data Standard categories shall be used.</td>
</tr>
<tr>
<td>MetaDataCategory</td>
<td>Type</td>
<td>A MetaDataType that defines the category of a MetaData element.<br />example: http://purl.org/dc/terms/abstract</td>
</tr>
<tr>
<td>MetaDataCategoryInScheme</td>
<td>Type</td>
<td>A WholePartTypeType that asserts a MetaDataCategory belongs to a MetaDataScheme.</td>
</tr>
<tr>
<td>MetaDataScheme</td>
<td>Type</td>
<td>A RepresentationScheme that defines a set of MetaData.</td>
</tr>
<tr>
<td>ModemThing</td>
<td>Type</td>
<td>Any Thing that can feature in a MODEM Architecture. Note: things that appear in the MODEM metamodel will not necessarily be instances, unless they appear in an architecture.</td>
</tr>
<tr>
<td>ArchitectureViewpoint</td>
<td>Type</td>
<td>A work product establishing the conventions for the construction, interpretation and use of architecture views to frame specific system concerns.</td>
</tr>
<tr>
<td>ModelElement</td>
<td>Type</td>
<td>A graphical element in an ArchitectureModel.</td>
</tr>
<tr>
<td>StructuredADElement</td>
<td>Type</td>
<td>An ADElement that has other ADElements as part of it.<br />Note: this is not in ISO42010, but is required if the model is to be useful.</td>
</tr>
<tr>
<td>URI</td>
<td>Type</td>
<td>A MetaData that is a uniform resource identifier.</td>
</tr>
<tr>
<td>URL</td>
<td>Type</td>
<td>A URI that is a uniform resource location.</td>
</tr>
<tr>
<td>URN</td>
<td>Type</td>
<td>A URI that is a uniform resource name.</td>
</tr>
<tr>
<td>architectureMetaData</td>
<td>TupleType</td>
<td>A metaDataAnnotation that relates a MetaData element to the ArchitectureDescription it annotates.</td>
</tr>
<tr>
<td>assumption</td>
<td>TupleType</td>
<td>A describedBy that states an assumption about an ADElement.<br />Note: Any given ADElement may have zero to many assumptions.</td>
</tr>
<tr>
<td>categoryOfMetaData</td>
<td>TupleType</td>
<td>A typeInstance that relates a MetaData element to its category.</td>
</tr>
<tr>
<td>definition</td>
<td>TupleType</td>
<td>A metaDataAnnotation that provides the definition for a ModemThing.</td>
</tr>
<tr>
<td>finding</td>
<td>TupleType</td>
<td>A describedBy that describes a finding about an ArchitectureDescription.<br />Note: Any given ADElement may have zero to many findings.</td>
</tr>
<tr>
<td>metaDataAnnotation</td>
<td>TupleType</td>
<td>A representedBy that relates a MetaData element to the ModemThing it describes.</td>
</tr>
<tr>
<td>purpose</td>
<td>TupleType</td>
<td>An architectureMetaData that describes the purpose of a StructuredADElement.</td>
</tr>
<tr>
<td>recommendation</td>
<td>TupleType</td>
<td>An architectureMetaData that expresses a recommendation arising from a StructuredADElement.</td>
</tr>
<tr>
<td>viewCode</td>
<td>TupleType</td>
<td>A metaDataAnnotation that uses MetaData to represent the short code that identifies an ArchitectureViewpoint.<br />Note that viewCode and viewDescription from M3 are handled using the core IDEAS description and naming patterns.</td>
</tr>
<tr>
<td>webReference</td>
<td>TupleType</td>
<td>A metaDataAnnotation that asserts URI contains information about a ModemThing.</td>
</tr>
</tbody>
</table>

<p>Table ‑: A1 Element List</p>


# A2 – Architecture Products

{%include rasterfigure.html url="image40.png" width="604" height="258" description="A2 Logical Diagram" %}

<table>
<thead>
<tr>
<th>Element Name</th>
<th>Element Kind</th>
<th>Definition</th>
</tr>
</thead>
<tbody>
<tr>
<td>ADElement</td>
<td>Type</td>
<td><p>From ISO42010:</p>
An AD element is any construct in an architecture description. AD elements are the most primitive constructs discussed in this International Standard. Every stakeholder, concern, architecture viewpoint, architecture view, model kind, architecture model, architecture decision and rationale (see 4.2.7) is considered an AD element. When viewpoints and model kinds are defined and their models are populated, additional AD elements are introduced.</td>
</tr>
<tr>
<td>Architecture</td>
<td>Type</td>
<td>Fundamental concepts or properties of a system in its environment embodied in its elements, relationships, and in the principles of its design and evolution.</td>
</tr>
<tr>
<td>ArchitectureDescription</td>
<td>Type</td>
<td>A work product used to express an architecture.</td>
</tr>
<tr>
<td>ArchitectureFramework</td>
<td>Type</td>
<td><p>From ISO42010:<br />Uses of architecture frameworks include, but are not limited to: creating architecture descriptions; developing architecture modelling tools and architecting methods; and establishing processes to facilitate communication, commitments and interoperation across multiple projects and/or organizations.<br />NOTE 1 Architecture frameworks frequently encompass both provisions for architecture description and additional architecting practices.<br />EXAMPLES The following are architecture frameworks in the terms of this International Standard: Zachman’s information systems architecture framework [44], UK Ministry of Defence Architecture Framework [27], The Open Group’s Architecture Framework (TOGAF) [41], Kruchten’s “4+1” view model [23], Siemens’ 4 views method [10], Reference Model for Open Distributed Processing (RM-ODP), [ISO/IEC 10746] and Generalized Enterprise Reference Architecture (GERA) [ISO 15704].</p></td>
</tr>
<tr>
<td>ArchitectureModel</td>
<td>Type</td>
<td>No specific definition provided in ISO42010.</td>
</tr>
<tr>
<td>ArchitectureView</td>
<td>Type</td>
<td>A work product expressing the architecture of a system from the perspective of specific system concerns.</td>
</tr>
<tr>
<td>ArchitectureViewpoint</td>
<td>Type</td>
<td>A work product establishing the conventions for the construction, interpretation and use of architecture views to frame specific system concerns.</td>
</tr>
<tr>
<td>Concerns</td>
<td>Type</td>
<td><p>From ISO42010:<br />A concern could be held by one or more stakeholders. Concerns arise throughout the life cycle from system needs and requirements, from design choices and from implementation and operating considerations. A concern could be manifest in many forms, such as in relation to one or more stakeholder needs, goals, expectations, responsibilities, requirements, design constraints, assumptions, dependencies, quality attributes, architecture decisions, risks or other issues pertaining to the system.<br />EXAMPLES The following are concerns in the terms of this International Standard: functionality, feasibility, usage, system purposes, system features, system properties, known limitations, structure, behavior, performance, resource utilization, reliability, security, information assurance, complexity, evolvability, openness, concurrency, autonomy, cost, schedule, quality of service, flexibility, agility, modifiability, modularity, control, inter-process communication, deadlock, state change, subsystem integration, data accessibility, privacy, compliance to regulation, assurance, business goals and strategies, customer experience, maintainability, affordability and disposability. The distribution transparencies described in the Reference Model of Open Distributed Processing [ISO/IEC 10746-1] are concerns in the terms of this International Standard. Software properties as described in SQUARE [ISO/IEC 25010:2011, 4.2] name concerns in the terms of this International Standard.</p></td>
</tr>
<tr>
<td>ConfiguredResourceType</td>
<td>Type</td>
<td>An IndividualResourcePowertype that is a part of a ResourceType another ConfiguredResourceType.</td>
</tr>
<tr>
<td>HumanAndNonHumanConfigurationType</td>
<td>Type</td>
<td>A ResourceType that has both Human and Non-Human components.</td>
</tr>
<tr>
<td>ISO42010_System</td>
<td>Type</td>
<td>The term system is used in this International Standard to refer to entities whose architectures are of interest. The term is intended to encompass, but is not limited to, entities within the following domains:<br />- systems as described in [ISO/IEC 15288]: “systems that are man-made and may be configured with one or more of the following: hardware, software, data, humans, processes (e.g., processes for providing service to users), procedures (e.g. operator instructions), facilities, materials and naturally occurring entities”;<br />- software products and services as described in [ISO/IEC 12207];<br />- software-intensive systems as described in [IEEE Std 1471TM:2000]: “any system where software contributes essential influences to the design, construction, deployment, and evolution of the system as a whole” to encompass “individual applications, systems in the traditional sense, subsystems, systems of systems, product lines, product families, whole enterprises, and other aggregations of interest”.<br />This International Standard takes no position on what constitutes a system within those domains—or elsewhere. The nature of systems is not defined by this International Standard.</td>
</tr>
<tr>
<td>LogicalArchitecture</td>
<td>Type</td>
<td>A NodeParent whose parts are either Nodes, KnownResources or LogicalDomains.</td>
</tr>
<tr>
<td>MetaData</td>
<td>Type</td>
<td>A StringRepresentation that can be applied to any element in the architecture.<br />Note: wherever possible, standard Meta-Data types should be used - e.g. conforming to Dublin Core<br />Note for MOD Users: The MOD Meta Data Standard categories shall be used.</td>
</tr>
<tr>
<td>MetaDataCategory</td>
<td>Type</td>
<td>A MetaDataType that defines the category of a MetaData element.<br />example: http://purl.org/dc/terms/abstract</td>
</tr>
<tr>
<td>MetaDataCategoryInScheme</td>
<td>Type</td>
<td>A WholePartTypeType that asserts a MetaDataCategory belongs to a MetaDataScheme.</td>
</tr>
<tr>
<td>MetaDataScheme</td>
<td>Type</td>
<td>A RepresentationScheme that defines a set of MetaData.</td>
</tr>
<tr>
<td>ModelKind</td>
<td>Type</td>
<td><p>Conventions for a type of modelling.</p>
NOTE Examples of model kinds include: data flow diagrams, class diagrams, Petri nets, balance sheets, organization charts and state transition models.</td>
</tr>
<tr>
<td>ModelKindPartOfViewpoint</td>
<td>Type</td>
<td>A ModelPartOfViewType where a ModelKind is a typical part of an ArchitectureViewpoint.</td>
</tr>
<tr>
<td>ModelPartOfView</td>
<td>Type</td>
<td>A ModelPartOfViewType where a ModelKind is a typical part of an ArchitectureViewpoint.</td>
</tr>
<tr>
<td>OrganisationType</td>
<td>Type</td>
<td><p>A ResponsibleHumanResourceType and a ConstructedHumanResourceType that is a type of Organisation. This is not used as a component of a ResourceType.</p>
Examples: Government Department, Commercial Company, Accounting Department.</td>
</tr>
<tr>
<td>PersonType</td>
<td>Type</td>
<td>A ResponsibleHumanResourceType that is a type of person.</td>
</tr>
<tr>
<td>PhysicalArchitecture</td>
<td>Type</td>
<td>A HumanAndNonHumanConfigurationType that specifies the structure and behaviour of an EnterprisePhase.</td>
</tr>
<tr>
<td>PostType</td>
<td>Type</td>
<td>A ConstructedHumanResourceType and ResponsibleHumanResourceType specifying a type of Post. This is not used as a component of a ResourceType. A type of point of contact or responsible person.<br />Note that this is the type of post - e.g. Desk Officer, Commander, etc.</td>
</tr>
<tr>
<td>ResourceType</td>
<td>Type</td>
<td>A PhysicalArchitectureIndividualType that is a type of IndividualResource. This is not used as a component of a ResourceType, but may use components. [ABSTRACT]</td>
</tr>
<tr>
<td>ResourceTypeConfiguration</td>
<td>Type</td>
<td>A ModemWholePartType that is a relationship between types of ResourceTypeUsages which asserts one ResourceTypeUsage is part of another.</td>
</tr>
<tr>
<td>ResponsibleHumanResourceType</td>
<td>Type</td>
<td>A HumanResourceType that is a type of ResponsibleHumanResource.<br />A PostType, OrganisationType or a PersonType.</td>
</tr>
<tr>
<td>StructuredADElement</td>
<td>Type</td>
<td>An ADElement that has other ADElements as part of it.<br />Note: this is not in ISO42010, but is required if the model is to be useful.</td>
</tr>
<tr>
<td>ViewPartOfDescription</td>
<td>Type</td>
<td>A WholePartType where an ArchitectureView is part of an ArchitectureDescription.</td>
</tr>
<tr>
<td>ViewpointPartOfFramework</td>
<td>Type</td>
<td>A WholePartTypeType that asserts an ArchitectureViewpoint is part of an ArchitectureFramework.</td>
</tr>
<tr>
<td>IndividualResourcePowertype</td>
<td>Powertype</td>
<td>The powertype of IndividualResourceState.</td>
</tr>
<tr>
<td>EnterprisePhase</td>
<td>IndividualType</td>
<td>An UndertakingState that is a current or future state of a WholeLifeEnterprise or another EnterprisePhase.</td>
</tr>
<tr>
<td>Organisation</td>
<td>IndividualType</td>
<td>A ConstructedHumanResource which is an Organisation.</td>
</tr>
<tr>
<td>Person</td>
<td>IndividualType</td>
<td>An individual human being.</td>
</tr>
<tr>
<td>Post</td>
<td>IndividualType</td>
<td>A HumanResourcethat is a position in an Organisation that may be filled wholly or partly by a ResponsibleHumanResource; in other words, by an Organisation, Person or Post.<br />As the position is in the Organisation, it is a part of the Organisation.</td>
</tr>
<tr>
<td>ResponsibleHumanResource</td>
<td>IndividualType</td>
<td>A Person, Post or Organisation.<br />These can be held responsible for their actions, hence are responsible human resources.</td>
</tr>
<tr>
<td>WholeLifeEnterprise</td>
<td>IndividualType</td>
<td>An EnterprisePhase that represents the whole existance of an enterprise.</td>
</tr>
<tr>
<td>architectureMetaData</td>
<td>TupleType</td>
<td>A metaDataAnnotation that relates a MetaData element to the ArchitectureDescription it annotates.</td>
</tr>
<tr>
<td>architectureRealisation</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation that asserts that a PhysicalArchitecture is a realisation of a LogicalArchitecture.</td>
</tr>
<tr>
<td>architectureReference</td>
<td>TupleType</td>
<td>ArchitectureDescription to another ArchitectureDescription it refers to.</td>
</tr>
<tr>
<td>categoryOfMetaData</td>
<td>TupleType</td>
<td>A typeInstance that relates a MetaData element to its category.</td>
</tr>
<tr>
<td>configurationType</td>
<td>TupleType</td>
<td>A superSubtype that asserts that a ResourceType is a superType of ConfiguredResourceType.</td>
</tr>
<tr>
<td>enterpriseStructure</td>
<td>TupleType</td>
<td>A wholePart that asserts that one EnterprisePhase is a spatial part of another.</td>
</tr>
<tr>
<td>enterpriseTemporalPart</td>
<td>TupleType</td>
<td>An enterpriseStructure and a temporalWholePart that asserts that one EnterprisePhase is a temporal part of another (i.e. it is a phase of the other).</td>
</tr>
<tr>
<td>enterpriseWholePhase</td>
<td>TupleType</td>
<td>An enterpriseTemporalPart where whole is a WholeLifeEnterprise.</td>
</tr>
<tr>
<td>exhibits</td>
<td>TupleType</td>
<td>A couple that asserts an ISO42010_System has an Architecture.</td>
</tr>
<tr>
<td>expresses</td>
<td>TupleType</td>
<td>A representedBy that asserts and an ArchitectureDescription represents an Architecture.</td>
</tr>
<tr>
<td>frameworkGovernsDescription</td>
<td>TupleType</td>
<td>A typeInstance relating an ArchitectureDescription to the ArchitectureFramework it conforms to.</td>
</tr>
<tr>
<td>logicalArchitectureOfEnterprisePhase</td>
<td>TupleType</td>
<td>Relates an EnterprisePhase to a LogicalArchitecture that specifies its (logical) structure and behavior.</td>
</tr>
<tr>
<td>metaDataAnnotation</td>
<td>TupleType</td>
<td>A representedBy that relates a MetaData element to the ModemThing it describes.</td>
</tr>
<tr>
<td>modelKindGovernsModel</td>
<td>TupleType</td>
<td>A typeInstance where an ArchitecturalModel conforms to a ModelKind.</td>
</tr>
<tr>
<td>physicalArchitectureOfEnterprisePhase</td>
<td>TupleType</td>
<td>Relates an EnterprisePhase to a ResourceType that specifies its structure and behavior.</td>
</tr>
<tr>
<td>stakeholderConcern</td>
<td>TupleType</td>
<td>A couple that relates a Concern to a stakeholder that have the Concern.<br />Note: a concern may be held by more than one Stakeholder, hence there maybe multiple stakeholderConcerns.</td>
</tr>
<tr>
<td>systemConcern</td>
<td>TupleType</td>
<td>A couple that relates an ISO42010_System to a Concern that is held against the system<br />NOTE A concern pertains to any influence on a system in its environment including: developmental, technological, business, operational, organizational, political, economic, legal, regulatory, ecological and social influences.</td>
</tr>
<tr>
<td>viewpointGovernsView</td>
<td>TupleType</td>
<td>A typeInstance where an ArchitectureView conforms to an ArchitectureViewpoint.</td>
</tr>
</tbody>
</table>

<p>Table ‑: A2 Element List</p>


# A3 – Architecture Correspondence


{%include rasterfigure.html url="image41.png" width="605" height="314" description="A3 Logical Diagram" %}

<table>
<thead>
<tr>
<th>Element Name</th>
<th>Element Kind</th>
<th>Definition</th>
</tr>
</thead>
<tbody>
<tr>
<td>ADElement</td>
<td>Type</td>
<td><p>From ISO42010:</p>
An AD element is any construct in an architecture description. AD elements are the most primitive constructs discussed in this International Standard. Every stakeholder, concern, architecture viewpoint, architecture view, model kind, architecture model, architecture decision and rationale (see 4.2.7) is considered an AD element. When viewpoints and model kinds are defined and their models are populated, additional AD elements are introduced.</td>
</tr>
<tr>
<td>ArchitectureDescription</td>
<td>Type</td>
<td>A work product used to express an architecture.</td>
</tr>
<tr>
<td>ArchitectureModel</td>
<td>Type</td>
<td>No specific definition provided in ISO42010.</td>
</tr>
<tr>
<td>ArchitectureView</td>
<td>Type</td>
<td>A work product expressing the architecture of a system from the perspective of specific system concerns.</td>
</tr>
<tr>
<td>Correspondence</td>
<td>Type</td>
<td><p>From ISO42010:</p>
A correspondence defines a relation between AD elements. Correspondences are used to express architecture relations of interest within an architecture description (or between architecture descriptions). Correspondences can be governed by correspondence rules. Correspondence rules are used to enforce relations within an architecture description (or between architecture descriptions).</td>
</tr>
<tr>
<td>CorrespondenceRule</td>
<td>Type</td>
<td><p>From ISO42010:</p>
Correspondence rules are used to enforce relations within an architecture description (or between architecture descriptions).</td>
</tr>
<tr>
<td>ModelElement</td>
<td>Type</td>
<td>A graphical element in an ArchitectureModel.</td>
</tr>
<tr>
<td>StructuredADElement</td>
<td>Type</td>
<td>An ADElement that has other ADElements as part of it.<br />Note: this is not in ISO42010, but is required if the model is to be useful.</td>
</tr>
<tr>
<td>architectureReference</td>
<td>TupleType</td>
<td>A couple that relates an ArchitectureDescription to another ArchitectureDescription it refers to.</td>
</tr>
<tr>
<td>ruleGovernsCorrespondence</td>
<td>TupleType</td>
<td>A typeInstance relating a correspondence to the CorrespondenceRule that governs it.</td>
</tr>
</tbody>
</table>

<p>Table ‑: A3 Element List</p>



# A4 – Methodology Used


{%include rasterfigure.html url="image42.png" width="605" height="225" description="A4 Logical Diagram" %}

<table>
<thead>
<tr>
<th>Element Name</th>
<th>Element Kind</th>
<th>Definition</th>
</tr>
</thead>
<tbody>
<tr>
<td>ArchitectureMethodology</td>
<td>Type</td>
<td>A ProjectType that defines a standard way of running an ArchitectureProject.</td>
</tr>
<tr>
<td>ArchitectureProject</td>
<td>IndividualType</td>
<td>A Project that delivers an ArchitectureDescription.</td>
</tr>
<tr>
<td>projectMethodology</td>
<td>TupleType</td>
<td>ArchitectureProject to the ArchitectureMethodology is conforms to.</td>
</tr>
</tbody>
</table>

<p>Table ‑: A4 Element List</p>

# A5 – Architecture Status

{%include rasterfigure.html url="image43.png" width="610" height="381" description="A5 Logical Diagram" %}

<table>
<thead>
<tr>
<th>Element Name</th>
<th>Element Kind</th>
<th>Definition</th>
</tr>
</thead>
<tbody>
<tr>
<td>ADElement</td>
<td>Type</td>
<td><p>From ISO42010:</p>
An AD element is any construct in an architecture description. AD elements are the most primitive constructs discussed in this International Standard. Every stakeholder, concern, architecture viewpoint, architecture view, model kind, architecture model, architecture decision and rationale (see 4.2.7) is considered an AD element. When viewpoints and model kinds are defined and their models are populated, additional AD elements are introduced.</td>
</tr>
<tr>
<td>ArchitectureDescription</td>
<td>Type</td>
<td>A work product used to express an architecture.</td>
</tr>
<tr>
<td>ArchitectureModel</td>
<td>Type</td>
<td>No specific definition provided in ISO42010.</td>
</tr>
<tr>
<td>NextArchitectureVersion</td>
<td>Type</td>
<td>A BeforeAfterType that associates one version of an ArchitectureDescription with another version that follows it.</td>
</tr>
<tr>
<td>NextModelVersion</td>
<td>Type</td>
<td>A BeforeAfterType that associates one version of an ArchitectureModel with another version that follows it.</td>
</tr>
<tr>
<td>StructuredADElement</td>
<td>Type</td>
<td>An ADElement that has other ADElements as part of it.<br />Note: this is not in ISO42010, but is required if the model is to be useful.</td>
</tr>
<tr>
<td>ArchitectureApprovalMilestone</td>
<td>IndividualType</td>
<td>ADElement is approved by a ResponsibleHumanResource<br />Note: this replaces the dateCompleted tag on ArchitecturalDescription in M3.</td>
</tr>
<tr>
<td>ArchitectureProject</td>
<td>IndividualType</td>
<td>A Project that delivers an ArchitectureDescription.</td>
</tr>
<tr>
<td>Manager</td>
<td>IndividualType</td>
<td>An OrganisationalRole where the Person's role in the Organisation is as a Manager.<br />Example: when the Organisation is a Project, the role would be as project manager.</td>
</tr>
<tr>
<td>Organisation</td>
<td>IndividualType</td>
<td>A ConstructedHumanResource which is an Organisation.</td>
</tr>
<tr>
<td>OrganisationalRole</td>
<td>IndividualType</td>
<td>A ConstructedHumanResource that is the state of the ResponsibleHumanResource (that part of its life) where it has the role in an Organisation.<br />Where a role carries the authority to undertake a function - though the human resource given the role has the responsibility.</td>
</tr>
<tr>
<td>Person</td>
<td>IndividualType</td>
<td>An individual human being.</td>
</tr>
<tr>
<td>Post</td>
<td>IndividualType</td>
<td>A HumanResourcethat is a position in an Organisation that may be filled wholly or partly by a ResponsibleHumanResource; in other words, by an Organisation, Person or Post.<br />As the position is in the Organisation, it is a part of the Organisation.</td>
</tr>
<tr>
<td>Project</td>
<td>IndividualType</td>
<td>An Undertaking that is a time-limited endeavour to create a specific set of products or services.</td>
</tr>
<tr>
<td>ProjectMilestone</td>
<td>IndividualType</td>
<td>A ProjectPart that marks the end of one ProjectPhase and possibly the beginning of another.<br />Note: the temporal extent of a ProjectMilestone is likely to be finite - e.g. there may be milestone meetings, funding reviews, etc. before another Project or ProjectPhase can start.</td>
</tr>
<tr>
<td>ProjectPhase</td>
<td>IndividualType</td>
<td>part of a Project and has been nominated as a phase of a Project.</td>
</tr>
<tr>
<td>ResponsibleHumanResource</td>
<td>IndividualType</td>
<td>A Person, Post or Organisation.<br />These can be held responsible for their actions, hence are responsible human resources.</td>
</tr>
<tr>
<td>ResponsibleOwner</td>
<td>IndividualType</td>
<td>An OrganisationProjectRole where the ResponsibleHumanResource is the responsible for the Organisation - e.g. a project owner.</td>
</tr>
<tr>
<td>approved</td>
<td>TupleType</td>
<td>A couple that relates an ArchitectureApprovalMilestone to the ADElement that is approved.</td>
</tr>
<tr>
<td>approver</td>
<td>TupleType</td>
<td>A couple that relates an ArchitectureApprovalMilestone to the ResponsibleHumanResource that approved it.</td>
</tr>
<tr>
<td>createdBy</td>
<td>TupleType</td>
<td>A couple that asserts a ResponsibleHumanResource is the creator of an ADElement.<br />Note: this covers the creatingOrganisation and architect tags that were applied to ArchitectureDescription in M3.</td>
</tr>
<tr>
<td>humanResourceInRole</td>
<td>TupleType</td>
<td>A responsibleHumanResourceState relationship between the OrganisationRole and the ResponsibleHumanResource that bears the responsibility.<br />Note: the OrganisationRole cannot be passed on. Instead, a new instance of the role is created.</td>
</tr>
<tr>
<td>milestoneBegins</td>
<td>TupleType</td>
<td>A startBoundary that asserts a ProjectMilestone marks the beginning of a Project or ProjectPhase.</td>
</tr>
<tr>
<td>milestoneEnds</td>
<td>TupleType</td>
<td>An endBoundary that asserts a ProjectMilestone marks the end of a Project or ProjectPhase.</td>
</tr>
<tr>
<td>projectWholePhase</td>
<td>TupleType</td>
<td>A projectPhaseTemporalPart where the whole is a Project.</td>
</tr>
</tbody>
</table>

<p>Table ‑: A5 Element List</p>


# A6 – Architecture Versions


{%include rasterfigure.html url="/image44.png" width="604" height="194" description="A6 Logical Diagram" %}

<table>
<thead>
<tr>
<th>Element Name</th>
<th>Element Kind</th>
<th>Definition</th>
</tr>
</thead>
<tbody>
<tr>
<td>ADElement</td>
<td>Type</td>
<td><p>From ISO42010:</p>
An AD element is any construct in an architecture description. AD elements are the most primitive constructs discussed in this International Standard. Every stakeholder, concern, architecture viewpoint, architecture view, model kind, architecture model, architecture decision and rationale (see 4.2.7) is considered an AD element. When viewpoints and model kinds are defined and their models are populated, additional AD elements are introduced.</td>
</tr>
<tr>
<td>ArchitectureDescription</td>
<td>Type</td>
<td>A work product used to express an architecture.</td>
</tr>
<tr>
<td>ArchitectureModel</td>
<td>Type</td>
<td>No specific definition provided in ISO42010.</td>
</tr>
<tr>
<td>NextArchitectureVersion</td>
<td>Type</td>
<td>A BeforeAfterType that associates one version of an ArchitectureDescription with another version that follows it.</td>
</tr>
<tr>
<td>NextModelVersion</td>
<td>Type</td>
<td>A BeforeAfterType that associates one version of an ArchitectureModel with another version that follows it.</td>
</tr>
<tr>
<td>StructuredADElement</td>
<td>Type</td>
<td>An ADElement that has other ADElements as part of it.<br />Note: this is not in ISO42010, but is required if the model is to be useful.</td>
</tr>
<tr>
<td>ArchitectureApprovalMilestone</td>
<td>IndividualType</td>
<td>A ProjectMilestone where an ADElement is approved by a ResponsibleHumanResource<br />Note: this replaces the dateCompleted tag on ArchitecturalDescription in M3.</td>
</tr>
<tr>
<td>approved</td>
<td>TupleType</td>
<td>A couple that relates an ArchitectureApprovalMilestone to the ADElement that is approved.</td>
</tr>
</tbody>
</table>

<p>Table ‑: A6 Element List</p>


# A7 – Architecture Meta-Data


{%include rasterfigure.html url="image45.png" width="604" height="353" description="A7 Logical Diagram" %}

<table>
<thead>
<tr>
<th>Element Name</th>
<th>Element Kind</th>
<th>Definition</th>
</tr>
</thead>
<tbody>
<tr>
<td>ADElement</td>
<td>Type</td>
<td><p>From ISO42010:</p>
An AD element is any construct in an architecture description. AD elements are the most primitive constructs discussed in this International Standard. Every stakeholder, concern, architecture viewpoint, architecture view, model kind, architecture model, architecture decision and rationale (see 4.2.7) is considered an AD element. When viewpoints and model kinds are defined and their models are populated, additional AD elements are introduced.</td>
</tr>
<tr>
<td>ArchitectureDescription</td>
<td>Type</td>
<td>A work product used to express an architecture.</td>
</tr>
<tr>
<td>ArchitectureModel</td>
<td>Type</td>
<td>No specific definition provided in ISO42010.</td>
</tr>
<tr>
<td>ArchitectureView</td>
<td>Type</td>
<td>A work product expressing the architecture of a system from the perspective of specific system concerns.</td>
</tr>
<tr>
<td>ArchitectureViewpoint</td>
<td>Type</td>
<td>A work product establishing the conventions for the construction, interpretation and use of architecture views to frame specific system concerns.</td>
</tr>
<tr>
<td>DublinCoreTag</td>
<td>Type</td>
<td>A MetaDataCategory that is a DublinCore tag.</td>
</tr>
<tr>
<td>MetaData</td>
<td>Type</td>
<td>A StringRepresentation that can be applied to any element in the architecture.<br />Note: wherever possible, standard Meta-Data types should be used - e.g. conforming to Dublin Core<br />Note for MOD Users: The MOD Meta Data Standard categories shall be used.</td>
</tr>
<tr>
<td>MetaDataCategory</td>
<td>Type</td>
<td>A MetaDataType that defines the category of a MetaData element.<br />example: http://purl.org/dc/terms/abstract.</td>
</tr>
<tr>
<td>MetaDataCategoryInScheme</td>
<td>Type</td>
<td>A WholePartTypeType that asserts a MetaDataCategory belongs to a MetaDataScheme.</td>
</tr>
<tr>
<td>MetaDataScheme</td>
<td>Type</td>
<td>A RepresentationScheme that defines a set of MetaData.</td>
</tr>
<tr>
<td>ModelElement</td>
<td>Type</td>
<td>A graphical element in an ArchitectureModel.</td>
</tr>
<tr>
<td>ModemThing</td>
<td>Type</td>
<td>Any Thing that can feature in a MODEM Architecture. Note: things that appear in the MODEM metamodel will not necessarily be instances, unless they appear in an architecture.</td>
</tr>
<tr>
<td>StructuredADElement</td>
<td>Type</td>
<td>An ADElement that has other ADElements as part of it.<br />Note: this is not in ISO42010, but is required if the model is to be useful.</td>
</tr>
<tr>
<td>URI</td>
<td>Type</td>
<td>A MetaData that is a uniform resource identifier.</td>
</tr>
<tr>
<td>URL</td>
<td>Type</td>
<td>A URI that is a uniform resource location.</td>
</tr>
<tr>
<td>URN</td>
<td>Type</td>
<td>A URI that is a uniform resource name.</td>
</tr>
<tr>
<td>architectureMetaData</td>
<td>TupleType</td>
<td>A metaDataAnnotation that relates a MetaData element to the ArchitectureDescription it annotates.</td>
</tr>
<tr>
<td>assumption</td>
<td>TupleType</td>
<td>A describedBy that states an assumption about an ADElement.<br />Note: Any given ADElement may have zero to many assumptions.</td>
</tr>
<tr>
<td>categoryOfMetaData</td>
<td>TupleType</td>
<td>A typeInstance that relates a MetaData element to its category.</td>
</tr>
<tr>
<td>definition</td>
<td>TupleType</td>
<td>A metaDataAnnotation that provides the definition for a ModemThing.</td>
</tr>
<tr>
<td>finding</td>
<td>TupleType</td>
<td>A describedBy that describes a finding about an ArchitectureDescription.<br />Note: Any given ADElement may have zero to many findings.</td>
</tr>
<tr>
<td>metaDataAnnotation</td>
<td>TupleType</td>
<td>A representedBy that relates a MetaData element to the ModemThing it describes.</td>
</tr>
<tr>
<td>purpose</td>
<td>TupleType</td>
<td>An architectureMetaData that describes the purpose of a StructuredADElement.</td>
</tr>
<tr>
<td>recommendation</td>
<td>TupleType</td>
<td>An architectureMetaData that expresses a recommendation arising from a StructuredADElement.</td>
</tr>
<tr>
<td>viewCode</td>
<td>TupleType</td>
<td>A metaDataAnnotation that uses MetaData to represent the short code that identifies an ArchitectureViewpoint.<br />Note that viewCode and viewDescription from M3 are handled using the core IDEAS description and naming patterns.</td>
</tr>
<tr>
<td>webReference</td>
<td>TupleType</td>
<td>A metaDataAnnotation that asserts URI contains information about a ModemThing.</td>
</tr>
</tbody>
</table>

<p>Table ‑: A7 Element List</p>

# A8 – Standards


{%include rasterfigure.html url="image46.png" width="604" height="342" description="A8 Logical Diagram<" %}

<table>
<thead>
<tr>
<th>Element Name</th>
<th>Element Kind</th>
<th>Definition</th>
</tr>
</thead>
<tbody>
<tr>
<td>FrequencyRange</td>
<td>Type</td>
<td>A MeasureRange that specifies maximum and minimum frequencies, measured in Hertz as real numbers.</td>
</tr>
<tr>
<td>ModemIndividualType</td>
<td>Type</td>
<td>The parent (supertype) of all MODEM elements that are types of Individuals e.g. tank, computer, etc.</td>
</tr>
<tr>
<td>Protocol</td>
<td>Type</td>
<td>A Standard for communication.</td>
</tr>
<tr>
<td>ProtocolStack</td>
<td>Type</td>
<td>A ModemIndividualType that is all the Individuals which conform to one or more specified protocols (ordered into a stack) that may be implemented by one or more ResourcePorts.<br />Note: was called &quot;ImplementedProtocol&quot; in M3.</td>
</tr>
<tr>
<td>Standard</td>
<td>Type</td>
<td>A ModemIndividualType that is all the individuals that conform to a ratified and peer-reviewed specification that is used to guide or constrain the architecture. A Standard may be applied to any element in the architecture.</td>
</tr>
<tr>
<td>SpectrumAllocation</td>
<td>Type</td>
<td>A Standard specifying a particular frequency range of the electromagnetic spectrum that is allotted to a particular usage.</td>
</tr>
<tr>
<td>CalendarPeriod</td>
<td>IndividualType</td>
<td>A Period that corresponds to a recognised date or time<br />Examples: 1st June 1974, 1885, 14:44:01 on 2nd June 1974, December 2008</td>
</tr>
<tr>
<td>ModemIndividualElement</td>
<td>IndividualType</td>
<td>An Individual that can feature in a MODEM architecture.</td>
</tr>
<tr>
<td>Organisation</td>
<td>IndividualType</td>
<td>A ConstructedHumanResource which is an Organisation.</td>
</tr>
<tr>
<td>individualConformsTo</td>
<td>TupleType</td>
<td>A modemIndividualTypeInstance that asserts that an element in the architecture conforms to a Standard.</td>
</tr>
<tr>
<td>typeConformsTo</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation that asserts a type in the architecture conforms to a Standard.</td>
</tr>
<tr>
<td>responsibleForRatifying</td>
<td>TupleType</td>
<td>A couple that asserts than an Organisation is responsible for the ratification of a standard.<br />Note: was called &quot;RatificationBody&quot; in M3.</td>
</tr>
<tr>
<td>ratifiedOn</td>
<td>TupleType</td>
<td>A couple that asserts a Standard has been ratified on a date.</td>
</tr>
<tr>
<td>withdrawnOn</td>
<td>TupleType</td>
<td>A couple that asserts a Standard has been withdrawn on a date.</td>
</tr>
<tr>
<td>spectrumAllocationRadioFrequencyRange</td>
<td>TupleType</td>
<td>A radioFrequencyRangeAssignment that asserts a spectrum allocation has been assigned to a frequency range.</td>
</tr>
<tr>
<td>isALayerIn</td>
<td>TupleType</td>
<td>A superSubtype that asserts that a ProtocolStack is a kind of Protocol. The Protocol is a layer in the ProtocolStack. The order of the layering is determined by the Protocols' runsOn relations.<br />Note: amalgamates &quot;ProtocolLayer&quot; and &quot;ImplementedOn&quot; in M3.</td>
</tr>
</tbody>
</table>

<p>Table ‑: A8 Element List</p>

# Ar – Architecture Roadmap


{%include rasterfigure.html url="image47.png" width="602" height="430" description="Ar Logical Diagram" %}

<table>
<thead>
<tr>
<th>Element Name</th>
<th>Element Kind</th>
<th>Definition</th>
</tr>
</thead>
<tbody>
<tr>
<td>ADElement</td>
<td>Type</td>
<td><p>From ISO42010:</p>
An AD element is any construct in an architecture description. AD elements are the most primitive constructs discussed in this International Standard. Every stakeholder, concern, architecture viewpoint, architecture view, model kind, architecture model, architecture decision and rationale (see 4.2.7) is considered an AD element. When viewpoints and model kinds are defined and their models are populated, additional AD elements are introduced.</td>
</tr>
<tr>
<td>ArchitectureDescription</td>
<td>Type</td>
<td>A work product used to express an architecture.</td>
</tr>
<tr>
<td>ArchitectureModel</td>
<td>Type</td>
<td>No specific definition provided in ISO42010.</td>
</tr>
<tr>
<td>ArchitectureView</td>
<td>Type</td>
<td>A work product expressing the architecture of a system from the perspective of specific system concerns.</td>
</tr>
<tr>
<td>ModelElement</td>
<td>Type</td>
<td>A graphical element in an ArchitectureModel.</td>
</tr>
<tr>
<td>SoftwareType</td>
<td>Type</td>
<td>An ArtefactType that is a type of Software.</td>
</tr>
<tr>
<td>StructuredADElement</td>
<td>Type</td>
<td>An ADElement that has other ADElements as part of it.<br />Note: this is not in ISO42010, but is required if the model is to be useful.</td>
</tr>
<tr>
<td>ArchitectureApprovalMilestone</td>
<td>IndividualType</td>
<td>A ProjectMilestone where an ADElement is approved by a ResponsibleHumanResource.<br />Note: this replaces the dateCompleted tag on ArchitecturalDescription in M3.</td>
</tr>
<tr>
<td>Manager</td>
<td>IndividualType</td>
<td>An OrganisationalRole where the Person's role in the Organisation is as a Manager.<br />Example: when the Organisation is a Project, the role would be as project manager.</td>
</tr>
<tr>
<td>ModellingSession</td>
<td>IndividualType</td>
<td>A ProjectPart where ArchitectureDescriptions are worked on.</td>
</tr>
<tr>
<td>Organisation</td>
<td>IndividualType</td>
<td>A ConstructedHumanResource which is an Organisation.</td>
</tr>
<tr>
<td>OrganisationalRole</td>
<td>IndividualType</td>
<td>A ConstructedHumanResource that is the state of the ResponsibleHumanResource (that part of its life) where it has the role in an Organisation.<br />Where a role carries the authority to undertake a function - though the human resource given the role has the responsibility.</td>
</tr>
<tr>
<td>Person</td>
<td>IndividualType</td>
<td>An individual human being.</td>
</tr>
<tr>
<td>Post</td>
<td>IndividualType</td>
<td>A HumanResourcethat is a position in an Organisation that may be filled wholly or partly by a ResponsibleHumanResource; in other words, by an Organisation, Person or Post.<br />As the position is in the Organisation, it is a part of the Organisation.</td>
</tr>
<tr>
<td>Project</td>
<td>IndividualType</td>
<td>An Undertaking that is a time-limited endeavour to create a specific set of products or services.</td>
</tr>
<tr>
<td>ProjectMilestone</td>
<td>IndividualType</td>
<td><p>A ProjectPart that marks the end of one ProjectPhase and possibly the beginning of another.</p>
Note: the temporal extent of a ProjectMilestone is likely to be finite - e.g. there may be milestone meetings, funding reviews, etc. before another Project or ProjectPhase can start.</td>
</tr>
<tr>
<td>ProjectPhase</td>
<td>IndividualType</td>
<td>An ProjectState that is a temporal part of a Project and has been nominated as a phase of a Project.</td>
</tr>
<tr>
<td>ResponsibleHumanResource</td>
<td>IndividualType</td>
<td>A Person, Post or Organisation.<br />These can be held responsible for their actions, hence are responsible human resources.</td>
</tr>
<tr>
<td>ResponsibleOwner</td>
<td>IndividualType</td>
<td>An OrganisationProjectRole where the ResponsibleHumanResource is the responsible for the Organisation - e.g. a project owner.</td>
</tr>
<tr>
<td>approved</td>
<td>TupleType</td>
<td>A couple that relates an ArchitectureApprovalMilestone to the ADElement that is approved.</td>
</tr>
<tr>
<td>approver</td>
<td>TupleType</td>
<td>A couple that relates an ArchitectureApprovalMilestone to the ResponsibleHumanResource that approved it.</td>
</tr>
<tr>
<td>createdBy</td>
<td>TupleType</td>
<td>A couple that asserts a ResponsibleHumanResource is the creator of an ADElement.<br />Note: this covers the creatingOrganisation and architect tags that were applied to ArchitectureDescription in M3.</td>
</tr>
<tr>
<td>milestoneBegins</td>
<td>TupleType</td>
<td>A startBoundary that asserts a ProjectMilestone marks the beginning of a Project or ProjectPhase.</td>
</tr>
<tr>
<td>milestoneEnds</td>
<td>TupleType</td>
<td>An endBoundary that asserts a ProjectMilestone marks the end of a Project or ProjectPhase.</td>
</tr>
<tr>
<td>modeller</td>
<td>TupleType</td>
<td>An agentParticipation where a Person conducts a ModellingSession</td>
</tr>
<tr>
<td>modellingSessionInProject</td>
<td>TupleType</td>
<td>A projectWholePart relating a ModellingSession to the ArchitectureProject it is part of.</td>
</tr>
<tr>
<td>humanResourceInRole</td>
<td>TupleType</td>
<td>A responsibleHumanResourceState relationship between the OrganisationRole and the ResponsibleHumanResource that bears the responsibility.<br />Note: the OrganisationRole cannot be passed on. Instead, a new instance of the role is created.</td>
</tr>
<tr>
<td>projectWholePhase</td>
<td>TupleType</td>
<td>A projectPhaseTemporalPart where the whole is a Project.</td>
</tr>
<tr>
<td>projectWholeAndPart</td>
<td>TupleType</td>
<td>A projectWholePart where both the whole and part are Projects.</td>
</tr>
<tr>
<td>toolUsed</td>
<td>TupleType</td>
<td>A couple that asserts a SoftwareType was used in the production of a StructuredADElement.</td>
</tr>
</tbody>
</table>

<p>Table ‑: Ar Element List</p>
