---
title: Concepts Layer
---

# C1 – Capability Taxonomy


{%include rasterfigure.html url="image2.png" description="C1 Logical Diagram" %}


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
<td>ApplicableMoE</td>
<td>Type</td>
<td>An ApplicableMeasureCategory where the categories are MeasureOfEffectivenessCategories and the things being measured are Capabilities.</td>
</tr>
<tr>
<td>Capability</td>
<td>Type</td>
<td>A DispositionalProperty that is the set of all things that are capable of achieving a particular outcome.
</td>
</tr>
<tr>
<td>MeasureCategory</td>
<td>Type</td>
<td>
<p>A MeasureType whose members are recognised types of MeasureInstance.</p>
<p>Examples:</p>
<p>Mass (included in IDEAS), Length (included in IDEAS), Velocity, Hardness.</p>
</td>
</tr>
<tr>
<td>capabilitySpecialisation</td>
<td>TupleType</td>
<td>A superSubtype that relates one Capability (supertype) to a more specialised Capability (subtype).</td>
</tr>
</tbody>
</table>


Table : C1 Element List


# C2 - Enterprise Vision

{%include rasterfigure.html url="image3.emf" description="Overview" %}


{%include rasterfigure.html url="image4.png" description="C2 Logical Diagram" %}



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
<td>ApplicableMoE</td>
<td>Type</td>
<td>An ApplicableMeasureCategory where the categories are MeasureOfEffectivenessCategories and the things being measured are Capabilities.</td>
</tr>
<tr>
<td>BenefitOfGoal</td>
<td>Type</td>
<td>A RepresentationInStructure where a BenefitStatement is part of a StatementOfGoal.</td>
</tr>
<tr>
<td>BenefitStatement</td>
<td>Type</td>
<td>A StringDescription that is part of a StatementOfGoal which describes a benefit realised by achieving the goal.</td>
</tr>
<tr>
<td>Capability</td>
<td>Type</td>
<td>A DispositionalProperty that is the set of all things that are capable of achieving a particular outcome.</td>
</tr>
<tr>
<td>CBRNEnvironment</td>
<td>Type</td>
<td>An EnvironmentalFactor that defines the type of chemical, biological, radiological and nuclear environment in which an Enterprise may operate.</td>
</tr>
<tr>
<td>EnvironmentalFactor</td>
<td>Type</td>
<td>A GeopoliticalLocationStateType that defines some aspect of the environment in which an Enterprise may operate.</td>
</tr>
<tr>
<td>LightConditions</td>
<td>Type</td>
<td>An EnvironmentmentalFactor that defines the types of light (e.g. broad daylight, dusk, moonlit, etc.) in which an Enterprise may operate.</td>
</tr>
<tr>
<td>Measure</td>
<td>Type</td>
<td>A Property whose members are Individuals that all share a common, measurable property, or whose properties lie within a MeasureRange.<br />
Examples: 2kg, 4 weeks, 2km.</td>
</tr>
<tr>
<td>MeasureCategory</td>
<td>Type</td>
<td>A MeasureType whose members are recognised types of MeasureInstance.<br/>
Examples: Mass (included in IDEAS), Length (included in IDEAS), Velocity, Hardness.</td>
</tr>
<tr>
<td>MeasureInContext</td>
<td>Type</td>
<td>A ModemIndividualType that brings together EnvironmentalFactors with a Measure in order to qualify the measure.<br />
Examples: 40mph in desert, 1km range in cloudy conditions.</td>
</tr>
<tr>
<td>MeasurePoint</td>
<td>Type</td>
<td>A Measure whose members are Individuals that all share a common property that can be measured.<br />
Examples: 2kg, 4 weeks, 2km.</td>
</tr>
<tr>
<td>MeasureRange</td>
<td>Type</td>
<td>A Measure that is characterised by two MeasurePoints that define its upper and lower bounds.</td>
</tr>
<tr>
<td>SituationType</td>
<td>Type</td>
<td>An EnvironmentalFactor used to describe the types and levels of threat under which an Enterprise may operate.<br />
Examples: Corrosive, Fire, Smoke, Peaceful, Under Fire, Under Heavy Fire, etc.</td>
</tr>
<tr>
<td>SubGoal</td>
<td>Type</td>
<td>A RepresentationInStructure where one StatementOfGoal is part of another.</td>
</tr>
<tr>
<td>TerrainType</td>
<td>Type</td>
<td>An EnvironmentalFactor that defines the type of ground conditions that an Enterprise may operate in.<br />
Note: TerrainType is a subtype of GeopoliticalLocationStateType as the terrain may change over time (e.g. muddy, frozen ground, deep snow, etc.)</td>
</tr>
<tr>
<td>VisionStatement</td>
<td>Type</td>
<td>A StringDescription that is a short paragraph outlining the vision for a given phase of an enterprise.</td>
</tr>
<tr>
<td>EnduringTask</td>
<td>IndividualType</td>
<td>An Undertaking recognised by an enterprise as being essential to achieving its goals - i.e. a strategic specification of what the enterprise does.</td>
</tr>
<tr>
<td>EnduringTaskPhase</td>
<td>IndividualType</td>
<td>A ProcessState that is a temporal part of an EnduringTask.</td>
</tr>
<tr>
<td>EnterpriseRoleInEnduringTask</td>
<td>IndividualType</td>
<td>A ParticipationExtent whose extent is the participation of an EnterprisePhase (or WholeLifeEnterprise) in an EnduringTask.</td>
</tr>
<tr>
<td>EnterprisePhase</td>
<td>IndividualType</td>
<td>An UndertakingState that is a current or future state of a WholeLifeEnterprise or another EnterprisePhase.</td>
</tr>
<tr>
<td>HumanResourceRoleInEnduringTask</td>
<td>IndividualType</td>
<td>A ParticipationExtent where the participant is a ResponsibleHumanResource and the Process is an EnduringTask.</td>
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
<td>A HumanResource that is a position in an Organisation that may be filled wholly or partly by a ResponsibleHumanResource; in other words, by an Organisation, Person or Post. As the position is in the Organisation, it is a part of the Organisation.</td>
</tr>
<tr>
<td>Project</td>
<td>IndividualType</td>
<td>An Undertaking that is a time-limited endeavour to create a specific set of products or services.</td>
</tr>
<tr>
<td>WholeLifeEnterprise</td>
<td>IndividualType</td>
<td>An EnterprisePhase that represents the whole existance of an enterprise.</td>
</tr>
<tr>
<td>capabilityForTask</td>
<td>TupleType</td>
<td>A propertyOfIndividual that asserts a Capability is required in order for an Enterprise to conduct a phase of an EnduringTask.</td>
</tr>
<tr>
<td>enduringTaskEnterpriseRole</td>
<td>TupleType</td>
<td>A processWholeRoleExtentPart which relates an EnduringTaskPhase to an EnterpriseRoleInEnduringTask.</td>
</tr>
<tr>
<td>enduringTaskHumanResourceRole</td>
<td>TupleType</td>
<td>A processWholeRoleExtentPart where the Process is an EnduringTask and the involved Individual is a ResponsibleHumanResource.</td>
</tr>
<tr>
<td>enterpriseVision</td>
<td>TupleType</td>
<td>A describedBy that relates a VisionStatement to the EnteprisePhase it describes.</td>
</tr>
<tr>
<td>enterpriseGoal</td>
<td>TupleType</td>
<td>A describedBy that relates a StatementOfGoal to the EnterprisePhase it describes.</td>
</tr>
<tr>
<td>enterpriseMeasureOfEffectiveness</td>
<td>TupleType</td>
<td>A measureOfIndividual where the Individual is an EnterprisePhase and the measure is a MeasureOfEffectiveness.</td>
</tr>
<tr>
<td>enterpriseRole</td>
<td>TupleType</td>
<td>An agentParticipation where the agent is a WholeLifeEnterprise and the participation is an EnterpriseRoleInEnduringTask. An enterpriseRole relates a WholeLifeEnterprise to a role it performs in an EnduringTask</td>
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
<td>environmentalContext</td>
<td>TupleType</td>
<td>A couple that relates a MeasureInContext to an EnvironmentalFactor in order to qualify the measure.</td>
</tr>
<tr>
<td>exhibitsCapability</td>
<td>TupleType</td>
<td>A propertyOfIndividual that relates an EnteprisePhase to a Capability that it exhibits. Note: replaces exhibits tagged value in M3</td>
</tr>
<tr>
<td>humanResourceEnduringTaskRole</td>
<td>TupleType</td>
<td>An agentParticipation where the Agent is a ResponsibleHumanResource and the Process is an EnduringTask.</td>
</tr>
<tr>
<td>measureTypeInstance</td>
<td>TupleType</td>
<td>A typeInstance that asserts a Measure is an instance of a MeasureCategory. Examples: 2kg is a mass, 40m/s is a velocity</td>
</tr>
<tr>
<td>phaseOfEnduringTask</td>
<td>TupleType</td>
<td>An undertakingWholeState where the state (part) is an EnduringTaskPhase and the whole is an EnduringTask.</td>
</tr>
<tr>
<td>qualifiedMeasure</td>
<td>TupleType</td>
<td>A superSubtype that relates a MeasureInContext to the measure it qualifies.</td>
</tr>
<tr>
<td>taskMeasureOfEffectiveness</td>
<td>TupleType</td>
<td>A measureOfIndividual that asserts a Measure is an MoE for an EnduringTaskPhase</td>
</tr>
<tr>
<td>upperBoundOfMeasureRange</td>
<td>TupleType</td>
<td>A superSubtype that asserts the MeasureInstance that is the upper bound (i.e. maximum measure) of a MeasureRange.</td>
</tr>
</tbody>
</table>



Table ‑: C2 Element List



# C3 - Capability Dependencies


{%include rasterfigure.html url="image5.png" description="C3 Logical Diagram" %}



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
<td>Capability</td>
<td>Type</td>
<td>A DispositionalProperty that is the set of all things that are capable of achieving a particular outcome.</td>
</tr>
<tr>
<td>CapabilityComposition</td>
<td>Type</td>
<td>A MeasureType whose members are recognised types of MeasureInstance.<br />
Examples:
Mass (included in IDEAS), Length (included in IDEAS), Velocity, Hardness.</td>
</tr>
<tr>
<td>capabilityDependency</td>
<td>TupleType</td>
<td>A couple that relates a (dependent) Capability to a Capability it is dependentUpon</td>
</tr>
<tr>
<td>capabilitySpecialisation</td>
<td>TupleType</td>
<td>A superSubtype that relates one Capability (supertype) to a more specialised Capability (subtype).</td>
</tr>
</tbody>
</table>

Table ‑: C3 Element List



# C4 – Standard Processes

{%include rasterfigure.html url="image6.png" description="C4 Logical Diagram" %}


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
<td>ActivityGroup</td>
<td><strong>Type</strong></td>
<td>An OperationalActivity that is entirely composed of other OperationalActivities.</td>
</tr>
<tr>
<td>ActivityGrouping</td>
<td>Type</td>
<td>An ActivityComposition where the parent Activity is an ActivityGroup.</td>
</tr>
<tr>
<td>Capability</td>
<td>Type</td>
<td>A DispositionalProperty that is the set of all things that are capable of achieving a particular outcome.</td>
</tr>
<tr>
<td>CapabilityRole</td>
<td>Type</td>
<td>A ParticipationExtentType which is the extent of a Capability's participation in a StandardActivity.</td>
</tr>
<tr>
<td>OperationalActivity</td>
<td>Type</td>
<td>A ProcessType that is a type of logical process, specified independently of how the process is carried out. Note: an OperationalActivity may only be carried out by a logical Node.</td>
</tr>
<tr>
<td>RoleInStandardActivity</td>
<td>Type</td>
<td>A ProcessWholeRoleExtentPartType that relates a StandardActivity to a CapabilityRole.</td>
</tr>
<tr>
<td>RoleOfCapability</td>
<td>Type</td>
<td>An AgentParticipationType that relates a Capability to its role in a StandardOperationalActivity.</td>
</tr>
<tr>
<td>StandardActivity</td>
<td>Type</td>
<td>A ProcessType that is a standard procedure (e.g. doctrinal tasks). Note: This is equivalent to what some defence organisations call JETLs. Note: was called &quot;StandardOperationalActivity&quot; in M3.</td>
</tr>
<tr>
<td>StandardActivityComposition</td>
<td>Type</td>
<td>A TypicalWholePart that asserts one StandardActivity is part of another.</td>
</tr>
<tr>
<td>EnduringTask</td>
<td>IndividualType</td>
<td>An Undertaking recognised by an enterprise as being essential to achieving its goals - i.e. a strategic specification of what the enterprise does.</td>
</tr>
<tr>
<td>EnduringTaskPhase</td>
<td>IndividualType</td>
<td>A ProcessState that is a temporal part of an EnduringTask.</td>
</tr>
<tr>
<td>capabilityForTask</td>
<td>TupleType</td>
<td>A propertyOfIndividual that asserts a Capability is required in order for an Enterprise to conduct a phase of an EnduringTask.</td>
</tr>
<tr>
<td>templateForTask</td>
<td>TupleType</td>
<td>A modemIndividualTypeInstance that relates an EnduringTask to an EnduringTaskTemplate that specifies it.</td>
</tr>
</tbody>
</table>

Table : C4 Element List


# C5 – Effects

{%include rasterfigure.html url="image7.emf" description="???" %}


# C6 – Not Used


# C7 – Performance Parameters

{%include rasterfigure.html url="image8.png" description="C7 Logical Diagram" %}


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
<td>ApplicableMoE</td>
<td>Type</td>
<td>An ApplicableMeasureCategory where the categories are MeasureOfEffectivenessCategories and the things being measured are Capabilities.</td>
</tr>
<tr>
<td>Capability</td>
<td>Type</td>
<td>A DispositionalProperty that is the set of all things that are capable of achieving a particular outcome.</td>
</tr>
<tr>
<td>MeasureCategory</td>
<td>Type</td>
<td>A MeasureType whose members are recognised types of MeasureInstance.<br />
Examples:<br />
Mass (included in IDEAS), Length (included in IDEAS), Velocity, Hardness.</td>
</tr>
</tbody>
</table>

C7 Element List


# C8 – Planning Assumptions

{%include rasterfigure.html url="image9.png" description="C8 Logical Diagram" %}



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
<td>BenefitOfGoal</td>
<td>Type</td>
<td>A RepresentationInStructure where a BenefitStatement is part of a StatementOfGoal.</td>
</tr>
<tr>
<td>BenefitStatement</td>
<td>Type</td>
<td>A StringDescription that is part of a StatementOfGoal which describes a benefit realised by achieving the goal.</td>
</tr>
<tr>
<td>Constraint</td>
<td>Type</td>
<td>An IndividualType that is the collection of all the objects subject to a particular constraint.</td>
</tr>
<tr>
<td>StatementOfGoal</td>
<td>Type</td>
<td>A StringDescription that is a specific, required objective for an EnterprisePhase.</td>
</tr>
<tr>
<td>SubGoal</td>
<td>Type</td>
<td>A RepresentationInStructure where one StatementOfGoal is part of another.</td>
</tr>
<tr>
<td>VisionStatement</td>
<td>Type</td>
<td>A StringDescription that is a short paragraph outlining the vision for a given phase of an enterprise.</td>
</tr>
<tr>
<td>EnduringTask</td>
<td>IndividualType</td>
<td>An Undertaking recognised by an enterprise as being essential to achieving its goals - i.e. a strategic specification of what the enterprise does.</td>
</tr>
<tr>
<td>EnterprisePhase</td>
<td>IndividualType</td>
<td>An UndertakingState that is a current or future state of a WholeLifeEnterprise or another EnterprisePhase.</td>
</tr>
<tr>
<td>EnterpriseRoleInEnduringTask</td>
<td>IndividualType</td>
<td>A ParticipationExtent whose extent is the participation of an EnterprisePhase (or WholeLifeEnterprise) in an EnduringTask.</td>
</tr>
<tr>
<td>ModemIndividualElement</td>
<td>IndividualType</td>
<td>An Individual that can feature in a MODEM architecture.</td>
</tr>
<tr>
<td>UndertakingPart</td>
<td>IndividualType</td>
<td>A ModemIndividualElement that is part of an Undertaking.</td>
</tr>
<tr>
<td>UndertakingState</td>
<td>IndividualType</td>
<td>An UndertakingPart that is a temporal part of an Undertaking.</td>
</tr>
<tr>
<td>WholeLifeEnterprise</td>
<td>IndividualType</td>
<td>An EnterprisePhase that represents the whole existance of an enterprise.</td>
</tr>
<tr>
<td>constraintOnIndividual</td>
<td>TupleType</td>
<td>A couple that asserts a constraint placed upon a ModemThing related to a ModemThing.</td>
</tr>
<tr>
<td>enduringTaskEnterpriseRole</td>
<td>TupleType</td>
<td>A processWholeRoleExtentPart which relates an EnduringTaskPhase to an EnterpriseRoleInEnduringTask.</td>
</tr>
<tr>
<td>enterpriseGoal</td>
<td>TupleType</td>
<td>A describedBy that relates a StatementOfGoal to the EnterprisePhase it describes.</td>
</tr>
<tr>
<td>enterpriseRole</td>
<td>TupleType</td>
<td>An agentParticipation where the agent is a WholeLifeEnterprise and the participation is an EnterpriseRoleInEnduringTask. An enterpriseRole relates a WholeLifeEnterprise to a role it performs in an EnduringTask.</td>
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
<td>enterpriseVision</td>
<td>TupleType</td>
<td>A describedBy that relates a VisionStatement to the EnteprisePhase it describes.</td>
</tr>
<tr>
<td>enterpriseWholePhase</td>
<td>TupleType</td>
<td>An enterpriseTemporalPart where whole is a WholeLifeEnterprise.</td>
</tr>
<tr>
<td>phaseOfEnduringTask</td>
<td>TupleType</td>
<td>An undertakingWholeState where the state (part) is an EnduringTaskPhase and the whole is an EnduringTask.</td>
</tr>
</tbody>
</table>

Table ‑: C8 Element List



# Cr – Capability Roadmap

{%include rasterfigure.html url="image10.png" description="Cr Logical Diagram" %}

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
<td>ApplicableMoE</td>
<td>Type</td>
<td>An ApplicableMeasureCategory where the categories are MeasureOfEffectivenessCategories and the things being measured are Capabilities.</td>
</tr>
<tr>
<td>Capability</td>
<td>Type</td>
<td>A DispositionalProperty that is the set of all things that are capable of achieving a particular outcome.</td>
</tr>
<tr>
<td>CapabilityConfiguration</td>
<td>Type</td>
<td>A composite structure representing the physical and human resources (and their interactions) that when brought together provide one or more Capabilities. A CapabilityConfiguration is a set of Resources configured to provide a capability, and should be guided by [doctrine] which may take the form of Standard or OperationalConstraint stereotypes.</td>
</tr>
<tr>
<td>CapabilityConfigurationInPackage</td>
<td>Type</td>
<td>A ResourceInPackage where the ResourceType is a CapabilityConfiguration and the package is a ResourcePackageSpecification.</td>
</tr>
<tr>
<td>CapabilityPackageSpecification</td>
<td>Type</td>
<td>A ResourcePackageSpecification that contains at least one CapabilityConfiguration.</td>
</tr>
<tr>
<td>CBRNEnvironment</td>
<td>Type</td>
<td>An EnvironmentalFactor that defines the type of chemical, biological, radiological and nuclear environment in which an Enterprise may operate.</td>
</tr>
<tr>
<td>EnvironmentalFactor</td>
<td>Type</td>
<td>A GeopoliticalLocationStateType that defines some aspect of the environment in which an Enterprise may operate.</td>
</tr>
<tr>
<td>HumanAndNonHumanConfigurationType</td>
<td>Type</td>
<td>A ResourceType that has both Human and Non-Human components.</td>
</tr>
<tr>
<td>LightConditions</td>
<td>Type</td>
<td>An EnvironmentmentalFactor that defines the types of light (e.g. broad daylight, dusk, moonlit, etc.) in which an Enterprise may operate.</td>
</tr>
<tr>
<td>Measure</td>
<td>Type</td>
<td>A Property whose members are Individuals that all share a common, measurable property, or whose properties lie within a MeasureRange.<br />
Examples: 2kg, 4 weeks, 2km.</td>
</tr>
<tr>
<td>MeasureCategory</td>
<td>Type</td>
<td>A MeasureType whose members are recognised types of MeasureInstance.<br />
Examples: Mass (included in IDEAS), Length (included in IDEAS), Velocity, Hardness.</td>
</tr>
<tr>
<td>MeasureInContext</td>
<td>Type</td>
<td>A ModemIndividualType that brings together EnvironmentalFactors with a Measure in order to qualify the measure.<br />
Examples: 40mph in desert, 1km range in cloudy conditions</td>
</tr>
<tr>
<td>MeasurePoint</td>
<td>Type</td>
<td>A Measure whose members are Individuals that all share a common property that can be measured.<br />
Examples: 2kg, 4 weeks, 2km.</td>
</tr>
<tr>
<td>MeasureRange</td>
<td>Type</td>
<td>A Measure that is characterised by two MeasurePoints that define its upper and lower bounds.</td>
</tr>
<tr>
<td>ResourceInPackage</td>
<td>Type</td>
<td>A ResourceUsage that specifies that a ResourceType is part of a DeliveryPackageSpecification</td>
</tr>
<tr>
<td>ResourcePackageSpecification</td>
<td>Type</td>
<td>A ResourcePackageType that specifies the types of Resource (i.e. ResourceTypes) that make up a ResourcePackage.</td>
</tr>
<tr>
<td>ResourceType</td>
<td>Type</td>
<td>A PhysicalArchitectureIndividualType that is a type of IndividualResource. This is not used as a component of a ResourceType, but may use components. [ABSTRACT].</td>
</tr>
<tr>
<td>TerrainType</td>
<td>Type</td>
<td>An EnvironmentalFactor that defines the type of ground conditions that an Enterprise may operate in.<br />
Note: TerrainType is a subtype of GeopoliticalLocationStateType as the terrain may change over time (e.g. muddy, frozen ground, deep snow, etc.)</td>
</tr>
<tr>
<td>SituationType</td>
<td>Type</td>
<td>An EnvironmentalFactor used to describe the types and levels of threat under which an Enterprise may operate.<br />
Examples: Corrosive, Fire, Smoke, Peaceful, Under Fire, Under Heavy Fire, etc</td>
</tr>
<tr>
<td>WeatherConditions</td>
<td>Type</td>
<td>An EnvironmentalFactor that defines the type of weather in which an Enterprise may operate.</td>
</tr>
<tr>
<td>EnterprisePackageEvent</td>
<td>IndividualType</td>
<td>A ResourcePackageState that is an event that occurs in a WholeLifeEnterprise - e.g. the introduction of a new Capability at the point of a PackageInService.</td>
</tr>
<tr>
<td>PackageInService</td>
<td>IndividualType</td>
<td>An IndividualResourceState that marks in in-service point for a ResourcePackage.</td>
</tr>
<tr>
<td>PackageOutOfService</td>
<td>IndividualType</td>
<td>An IndividualResourceState which marks the point at which a ResourcePackage ceases to be in service.<br />
Note: the components of the package may go on in service in some other configuration, but the package itself is retired</td>
</tr>
<tr>
<td>Project</td>
<td>IndividualType</td>
<td>An Undertaking that is a time-limited endeavour to create a specific set of products or services.</td>
</tr>
<tr>
<td>ProjectMilestone</td>
<td>IndividualType</td>
<td>A ProjectPart that marks the end of one ProjectPhase and possibly the beginning of another.<br />
Note: the temporal extent of a ProjectMilestone is likely to be finite - e.g. there may be milestone meetings, funding reviews, etc. before another Project or ProjectPhase can start.</td>
</tr>
<tr>
<td>ProjectPhase</td>
<td>IndividualType</td>
<td>A ProjectState that is a temporal part of a Project and has been nominated as a phase of a Project.</td>
</tr>
<tr>
<td>ResourcePackage</td>
<td>IndividualType</td>
<td>A HumanAndNonHumanConfiguration that is a collection of IndividualResources for a purpose.<br />
Example: All the fully configured aircraft delivered in an acquisition programme<br />
Example: A force element package put together for a particular operation<br />
Example: A tranche of new assets delivered into an enterprise</td>
</tr>
<tr>
<td>ResourcePackageState</td>
<td>IndividualType</td>
<td>A temporal part of a ResourcePackage.</td>
</tr>
<tr>
<td>WholeLifeEnterprise</td>
<td>IndividualType</td>
<td>An EnterprisePhase that represents the whole existance of an enterprise.</td>
</tr>
<tr>
<td>capabilityPackageDeliversCapability</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation where a CapabilityPackageSpecification provides a Capability.</td>
</tr>
<tr>
<td>capabilityRealisation</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation that relates a CapabilityConfiguration to a Capability.</td>
</tr>
<tr>
<td>capabilitySpecialisation</td>
<td>TupleType</td>
<td>A superSubtype that relates one Capability (supertype) to a more specialised Capability (subtype).</td>
</tr>
<tr>
<td>environmentalContext</td>
<td>TupleType</td>
<td>A couple that relates a MeasureInContext to an EnvironmentalFactor in order to qualify the measure.</td>
</tr>
<tr>
<td>inService</td>
<td>TupleType</td>
<td>A startBorder that indicates that a PackageInService marks the introduction into service of a ResourcePackage.</td>
</tr>
<tr>
<td>lowerBoundOfMeasureRange</td>
<td>TupleType</td>
<td>A superSubtype that asserts the MeasureInstance that is the lower bound (i.e. minimum measure) of a MeasureRange.</td>
</tr>
<tr>
<td>measureTypeInstance</td>
<td>TupleType</td>
<td>A typeInstance that asserts a Measure is an instance of a MeasureCategory. Examples: 2kg is a mass, 40m/s is a velocity.</td>
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
<td>outOfService</td>
<td>TupleType</td>
<td>An endBorder that indicates that an PackageOutOfService marks the termination of service of a ResourcePackage</td>
</tr>
<tr>
<td>packageEventInEnterprise</td>
<td>TupleType</td>
<td>An enterpriseWholePart where a EnterprisePackageEvent is part of a WholeLifeEnterprise - e.g. the package is rolled-out into the enterprise.</td>
</tr>
<tr>
<td>packageSpecification</td>
<td>TupleType</td>
<td>A modemIndividualTypeInstance that relates a ResourcePackage to the ResourcePackageSpecification that specifies the types of Resource it consists of.</td>
</tr>
<tr>
<td>projectWholePhase</td>
<td>TupleType</td>
<td>A projectPhaseTemporalPart where the whole is a Project.</td>
</tr>
<tr>
<td>qualifiedMeasure</td>
<td>TupleType</td>
<td>A superSubtype that relates a MeasureInContext to the measure it qualifies.</td>
</tr>
<tr>
<td>resourcePackageMeasure</td>
<td>TupleType</td>
<td>A measureOfIndividual where the measure Individual is a ResourcePackage.</td>
</tr>
<tr>
<td>resourceStateInMilestone</td>
<td>TupleType</td>
<td>A modemWholePart that asserts a ResourcePackageState occurs within a ProjectMilestone.</td>
</tr>
<tr>
<td>resourceTypeMeasure</td>
<td>TupleType</td>
<td>A measureOfType where the type is a ResourceType.</td>
</tr>
<tr>
<td>upperBoundOfMeasureRange</td>
<td>TupleType</td>
<td>A superSubtype that asserts the MeasureInstance that is the upper bound (i.e. maximum measure) of a MeasureRange.</td>
</tr>
</tbody>
</table>

Table : Cr Element List
