---
title: Physical Resource Specifications Layer
---


# P1 – Resource Types


{%include figure.html url="{{rasterimagepath}}image28.png" width="605" height="476"" description="P1 Logical Diagram" %}


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
<td>ArtefactType</td>
<td>Type</td>
<td>A NonHumanResourceType that is a type of Artefact. Examples are &quot;car&quot;, &quot;radio&quot;, &quot;diesel&quot;, etc.<br />Note: It has no human components.</td>
</tr>
<tr>
<td>Capability</td>
<td>Type</td>
<td>A DispositionalProperty that is the set of all things that are capable of achieving a particular outcome.</td>
</tr>
<tr>
<td>CapabilityConfiguration</td>
<td>Type</td>
<td>A composite structure representing the physical and human resources (and their interactions) that when brought together provide one or more Capabilities.<br />A CapabilityConfiguration is a set of Resources configured to provide a capability, and should be guided by [doctrine] which may take the form of Standard or OperationalConstraint stereotypes.</td>
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
<td>HumanResourceType</td>
<td>Type</td>
<td>A ResourceType that is a type of HumanResource.<br />A PersonType, PostType, OrganisationType or OrganisationRoleType. [ABSTRACT]<br />Note: was called &quot;OrganisationalResource&quot; in M3 v1.2.<br />Note: was called &quot;OrganisationalResourceType&quot; in M3.</td>
</tr>
<tr>
<td>LightConditions</td>
<td>Type</td>
<td>An EnvironmentmentalFactor that defines the types of light (e.g. broad daylight, dusk, moonlit, etc.) in which an Enterprise may operate.</td>
</tr>
<tr>
<td>Measure</td>
<td>Type</td>
<td>A Property whose members are Individuals that all share a common, measurable property, or whose properties lie within a MeasureRange.<br />Examples: 2kg, 4 weeks, 2km.</td>
</tr>
<tr>
<td>MeasureCategory</td>
<td>Type</td>
<td>A MeasureType whose members are recognised types of MeasureInstance.<br />Examples:
<p>Mass (included in IDEAS), Length (included in IDEAS), Velocity, Hardness.</p></td>
</tr>
<tr>
<td>MeasureInContext</td>
<td>Type</td>
<td>A ModemIndividualType that brings together EnvironmentalFactors with a Measure in order to qualify the measure.<br />Examples: 40mph in desert, 1km range in cloudy conditions.</td>
</tr>
<tr>
<td>MeasurePoint</td>
<td>Type</td>
<td>A Measure whose members are Individuals that all share a common property that can be measured.<br />Examples: 2kg, 4 weeks, 2km.</td>
</tr>
<tr>
<td>MeasureRange</td>
<td>Type</td>
<td>A Measure that is characterised by two MeasurePoints that define its upper and lower bounds.</td>
</tr>
<tr>
<td>NaturalResourceType</td>
<td>Type</td>
<td>A NonHumanResourceType that is a type of NaturalResource.</td>
</tr>
<tr>
<td>Node</td>
<td>Type</td>
<td>A NodeState that is used in context of a NodeParent.</td>
</tr>
<tr>
<td>NonHumanResourceType</td>
<td>Type</td>
<td>A ResourceType that is a type of NonHumanResource (i.e. an Artefact or NaturalResource). [ABSTRACT]</td>
</tr>
<tr>
<td>OrganisationType</td>
<td>Type</td>
<td>A ResponsibleHumanResourceType and a ConstructedHumanResourceType that is a type of Organisation. This is not used as a component of a ResourceType.<br />Examples: Government Department, Commercial Company, Accounting Department.</td>
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
<td>An ConstructedHumanResourceType and ResponsibleHumanResourceType specifying a type of Post. This is not used as a component of a ResourceType. A type of point of contact or responsible person.<br />Note that this is the type of post - e.g. Desk Officer, Commander, etc.</td>
</tr>
<tr>
<td>Property</td>
<td>Type</td>
<td>An IndividualType whose members all exhibit a common trait or feature. Often the Individuals are states having a property (the state of being 18 degrees centigrade), where this property can be a CategoricalProperty (qv.) or a DispositionalProperty (qv.).<br />Examples: Ability to fly at Mach 2, 10kg.</td>
</tr>
<tr>
<td>ResourceType</td>
<td>Type</td>
<td>A PhysicalArchitectureIndividualType that is a type of IndividualResource. This is not used as a component of a ResourceType, but may use components. [ABSTRACT]</td>
</tr>
<tr>
<td>SituationType</td>
<td>Type</td>
<td>An EnvironmentalFactor used to describe the types and levels of threat under which an Enterprise may operate.<br />Examples: Corrosive, Fire, Smoke, Peaceful, Under Fire, Under Heavy Fire, etc.</td>
</tr>
<tr>
<td>SoftwareType</td>
<td>Type</td>
<td>An ArtefactType that is a type of Software.</td>
</tr>
<tr>
<td>StandardConfiguration</td>
<td>Type</td>
<td>A CapabilityConfiguration that has been designated as a standard configuration.</td>
</tr>
<tr>
<td>Technology</td>
<td>Type</td>
<td>An ArtefactPowertype that is a class of Artefact that defines a branch of engineering or computer science.</td>
</tr>
<tr>
<td>TerrainType</td>
<td>Type</td>
<td>An EnvironmentalFactor that defines the type of ground conditions that an Enterprise may operate in.<br />Note: TerrainType is a subtype of GeopoliticalLocationStateType as the terrain may change over time (e.g. muddy, frozen ground, deep snow, etc.)</td>
</tr>
<tr>
<td>branchOfTechnology</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation that asserts an ArtefactType belongs to a branch of Technology.</td>
</tr>
<tr>
<td>capabilityRealisation</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation that relates a CapabilityConfiguration to a Capability.</td>
</tr>
<tr>
<td>environmentalContext</td>
<td>TupleType</td>
<td>A couple that relates a MeasureInContext to an EnvironmentalFactor in order to qualify the measure.</td>
</tr>
<tr>
<td>lowerBoundOfMeasureRange</td>
<td>TupleType</td>
<td>A superSubtype that asserts the MeasureInstance that is the lower bound (i.e. minimum measure) of a MeasureRange.</td>
</tr>
<tr>
<td>nodeRealisation</td>
<td>TupleType</td>
<td>A superSubtype that asserts that a ResourceType provides the functionality specified by an operational node.</td>
</tr>
<tr>
<td>qualifiedMeasure</td>
<td>TupleType</td>
<td>A superSubtype that relates a MeasureInContext to the measure it qualifies.</td>
</tr>
<tr>
<td>resourceTypeMeasure</td>
<td>TupleType</td>
<td>A measureOfType where the type is a ResourceType</td>
</tr>
<tr>
<td>resourceTypeProperty</td>
<td>TupleType</td>
<td>A propertyOfType where the type is a ResourceType.</td>
</tr>
<tr>
<td>upperBoundOfMeasureRange</td>
<td>TupleType</td>
<td>A superSubtype that asserts the MeasureInstance that is the upper bound (i.e. maximum measure) of a MeasureRange.</td>
</tr>
</tbody>
</table>


<p>Table ‑: P1 Element List</p>


# P2 – Resource Structure</h3>


{%include figure.html url="{{rasterimagepath}}image29.png" width="605" height="421" description="P2 Logical Diagram" %}

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
<td>ArtefactType</td>
<td>Type</td>
<td>A NonHumanResourceType that is a type of Artefact. Examples are &quot;car&quot;, &quot;radio&quot;, &quot;diesel&quot;, etc.<br />Note: It has no human components.</td>
</tr>
<tr>
<td>CapabilityConfiguration</td>
<td>Type</td>
<td>A composite structure representing the physical and human resources (and their interactions) that when brought together provide one or more Capabilities.<br />A CapabilityConfiguration is a set of Resources configured to provide a capability, and should be guided by [doctrine] which may take the form of Standard or OperationalConstraint stereotypes.</td>
</tr>
<tr>
<td>Commands</td>
<td>Type</td>
<td>A ResourceCommunication where one ResponsibleHumanResourceTypeConfigurationUsage commands another.</td>
</tr>
<tr>
<td>ConfiguredResourceType</td>
<td>Type</td>
<td>An IndividualResourcePowertype that is a part of a ResourceType another ConfiguredResourceType.</td>
</tr>
<tr>
<td>Controls</td>
<td>Type</td>
<td>A ResourceCommunication where one InteractionElement controls another.</td>
</tr>
<tr>
<td>HumanAndNonHumanConfigurationType</td>
<td>Type</td>
<td>A ResourceType that has both Human and Non-Human components.</td>
</tr>
<tr>
<td>HumanResourceType</td>
<td>Type</td>
<td>A ResourceType that is a type of HumanResource.<br />A PersonType, PostType, OrganisationType or OrganisationRoleType. [ABSTRACT]<br />Note: was called &quot;OrganisationalResource&quot; in M3 v1.2.<br />Note: was called &quot;OrganisationalResourceType&quot; in M3.</td>
</tr>
<tr>
<td>NaturalResourceType</td>
<td>Type</td>
<td>A NonHumanResourceType that is a type of NaturalResource.</td>
</tr>
<tr>
<td>Node</td>
<td>Type</td>
<td>A NodeState that is used in context of a NodeParent.</td>
</tr>
<tr>
<td>NonHumanResourceType</td>
<td>Type</td>
<td>A ResourceType that is a type of NonHumanResource (i.e. an Artefact or NaturalResource). [ABSTRACT]</td>
</tr>
<tr>
<td>OrganisationType</td>
<td>Type</td>
<td>A ResponsibleHumanResourceType and a ConstructedHumanResourceType that is a type of Organisation. This is not used as a component of a ResourceType.<br />Examples: Government Department, Commercial Company, Accounting Department.</td>
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
<td>PortConnector</td>
<td>Type</td>
<td>A ResourceCommunication that has a protocolStackSuperResourcePortConnectorTypeSubType to a ProtocolStack.<br />Note: was called &quot;ResourcePortConnector&quot; in M3.</td>
</tr>
<tr>
<td>PostType</td>
<td>Type</td>
<td>An ConstructedHumanResourceType and ResponsibleHumanResourceType specifying a type of Post. This is not used as a component of a ResourceType. A type of point of contact or responsible person.<br />Note that this is the type of post - e.g. Desk Officer, Commander, etc.</td>
</tr>
<tr>
<td>ResourceCommunication</td>
<td>Type</td>
<td>A ResourceInteraction where DataElements are exchanged.</td>
</tr>
<tr>
<td>ResourceEnergyFlow</td>
<td>Type</td>
<td>A ResourceInteraction where energy is transferred between ResourceUsages.</td>
</tr>
<tr>
<td>ResourceInteraction</td>
<td>Type</td>
<td>An ExchangeType where two ResourceTypes interact. [ABSTRACT]<br />Examples: data exchange between systems, conversations between people, people using systems, flows of materiel from one resource to another, etc.</td>
</tr>
<tr>
<td>ResourceMovement</td>
<td>Type</td>
<td>A ResourceInteraction where the element that flows is a ResourceType.</td>
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
<td>ResourceTypeExport</td>
<td>Type</td>
<td>A CapableOfType where a ResourceInteraction exports from a ResourceTypeUsage.</td>
</tr>
<tr>
<td>ResourceTypeImport</td>
<td>Type</td>
<td>A CapableOfType where a ResourceInteraction imports from a ResourceTypeUsage.</td>
</tr>
<tr>
<td>IndividualResourcePowertype</td>
<td>PowerType</td>
<td>The powertype of IndividualResourceState.</td>
</tr>
<tr>
<td>SoftwareType</td>
<td>Type</td>
<td>An ArtefactType that is a type of Software.</td>
</tr>
<tr>
<td>capabilityRealisation</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation that relates a CapabilityConfiguration to a Capability.</td>
</tr>
<tr>
<td>configurationType</td>
<td>TupleType</td>
<td>A superSubtype that asserts that a ResourceType is a superType of ConfiguredResourceType.</td>
</tr>
<tr>
<td>nodeRealisation</td>
<td>TupleType</td>
<td>A superSubtype that asserts that a ResourceType provides the functionality specified by an operational node.</td>
</tr>
</tbody>
</table>

<p>Table ‑: P2 Element List</p>


#  P3 – Resource Connectivity</h3>


{%include figure.html url="{{rasterimagepath}}image30.png" width="604" height="448" description="P3 Logical Diagram" %}

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
<td>ArtefactType</td>
<td>Type</td>
<td>A NonHumanResourceType that is a type of Artefact. Examples are &quot;car&quot;, &quot;radio&quot;, &quot;diesel&quot;, etc.<br />Note: It has no human components.</td>
</tr>
<tr>
<td>CapabilityConfiguration</td>
<td>Type</td>
<td>A composite structure representing the physical and human resources (and their interactions) that when brought together provide one or more Capabilities. A CapabilityConfiguration is a set of Resources configured to provide a capability, and should be guided by [doctrine] which may take the form of Standard or OperationalConstraint stereotypes.</td>
</tr>
<tr>
<td>ConfiguredResourceType</td>
<td>Type</td>
<td>An IndividualResourcePowertype that is a part of a ResourceType another ConfiguredResourceType.</td>
</tr>
<tr>
<td>DataElement</td>
<td>Type</td>
<td>A SymbolOrSymbolStringType that represents interactions between resource elements.</td>
</tr>
<tr>
<td>FrequencyRange</td>
<td>Type</td>
<td>A MeasureRange that specifies maximum and minimum frequencies, measured in Hertz as real numbers.</td>
</tr>
<tr>
<td>HumanAndNonHumanConfigurationType</td>
<td>Type</td>
<td>A ResourceType that has both Human and Non-Human components.</td>
</tr>
<tr>
<td>Measure</td>
<td>Type</td>
<td>A Property whose members are Individuals that all share a common, measurable property, or whose properties lie within a MeasureRange.<br />Examples: 2kg, 4 weeks, 2km.</td>
</tr>
<tr>
<td>MeasurePoint</td>
<td>Type</td>
<td>A Measure whose members are Individuals that all share a common property that can be measured.<br />Examples: 2kg, 4 weeks, 2km.</td>
</tr>
<tr>
<td>MeasureRange</td>
<td>Type</td>
<td>A Measure that is characterised by two MeasurePoints that define its upper and lower bounds.</td>
</tr>
<tr>
<td>NonHumanResourceType</td>
<td>Type</td>
<td>A ResourceType that is a type of NonHumanResource (i.e. an Artefact or NaturalResource) [ABSTRACT].</td>
</tr>
<tr>
<td>PhysicalArchitecture</td>
<td>Type</td>
<td>A HumanAndNonHumanConfigurationType that specifies the structure and behaviour of an EnterprisePhase.</td>
</tr>
<tr>
<td>Port</td>
<td>Type</td>
<td>An ArtefactComponent that is a type of IndividualPort.<br />Note: was called &quot;ResourcePort&quot; in M3.</td>
</tr>
<tr>
<td>PortComponentOfTypeOfArtefact</td>
<td>Type</td>
<td>A NonHumanResourceUsage that asserts a Port is a component of a type of Artefact.</td>
</tr>
<tr>
<td>PortConnectedToPortConnectorComponent</td>
<td>Type</td>
<td>A PortConnectedToPortConnectorComponent that is a type of IndividualPortConnectedToPortConnector that asserts a Port is a part of a PortConnector.</td>
</tr>
<tr>
<td>PortConnector</td>
<td>Type</td>
<td>A ResourceCommunication that has a protocolStackSuperResourcePortConnectorTypeSubType to a ProtocolStack.<br />Note: was called &quot;ResourcePortConnector&quot; in M3.</td>
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
<td>RadioFrequencyPort</td>
<td>Type</td>
<td>A Port that is a type of RadioFrequencyPort.</td>
</tr>
<tr>
<td>ResourceCommunication</td>
<td>Type</td>
<td>A ResourceInteraction where DataElements are exchanged.</td>
</tr>
<tr>
<td>ResourceInteraction</td>
<td>Type</td>
<td>An ExchangeType where two ResourceTypes interact. [ABSTRACT]<br />Examples: data exchange between systems, conversations between people, people using systems, flows of materiel from one resource to another, etc.</td>
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
<td>ResourceTypeExport</td>
<td>Type</td>
<td>A CapableOfType where a ResourceInteraction exports from a ResourceTypeUsage.</td>
</tr>
<tr>
<td>ResourceTypeImport</td>
<td>Type</td>
<td>A CapableOfType where a ResourceInteraction imports from a ResourceTypeUsage.</td>
</tr>
<tr>
<td>RoleInCommunication</td>
<td>Type</td>
<td>A RoleInInteraction where the exchanged element is a DataElement exchanged over a ResourceCommunication</td>
</tr>
<tr>
<td>RoleOfDataElement</td>
<td>Type</td>
<td>A RoleOfInteractionElement where the element is a DataElement</td>
</tr>
<tr>
<td>SoftwareType</td>
<td>Type</td>
<td>An ArtefactType that is a type of Software.</td>
</tr>
<tr>
<td>IndividualResourcePowertype</td>
<td>PowerType</td>
<td>The powertype of IndividualResourceState.</td>
</tr>
<tr>
<td>configurationType</td>
<td>TupleType</td>
<td>A superSubtype that asserts that a ResourceType is a superType of ConfiguredResourceType.</td>
</tr>
<tr>
<td>isALayerIn</td>
<td>TupleType</td>
<td>A superSubtype that asserts that a ProtocolStack is a kind of Protocol. The Protocol is a layer in the ProtocolStack. The order of the layering is determined by the Protocols' runsOn relations.<br />Note: amalgamates &quot;ProtocolLayer&quot; and &quot;ImplementedOn&quot; in M3.</td>
</tr>
<tr>
<td>lowerBoundOfMeasureRange</td>
<td>TupleType</td>
<td>A superSubtype that asserts the MeasureInstance that is the lower bound (i.e. minimum measure) of a MeasureRange.</td>
</tr>
<tr>
<td>protocolStackSuperPortSubType</td>
<td>TupleType</td>
<td>A superSubType relation with a superType ProtocolStack and a subType Port.</td>
</tr>
<tr>
<td>radioFrequencyPortConnectorFrequencyRange</td>
<td>TupleType</td>
<td>A radioFrequencyRangeAssignment that asserts a radio frequency range has been assigned to a RadioFrequencyPortConnector.</td>
</tr>
<tr>
<td>radioFrequencyPortFrequencyRange</td>
<td>TupleType</td>
<td>A radioFrequencyRangeAssignment that asserts a radio frequency range has been assigned to a RadioFrequencyPort.</td>
</tr>
<tr>
<td>runsOn</td>
<td>TupleType</td>
<td>A couple that asserts that one Protocol (client) may be implemented on another (supplier). This determines the layer order in the ProtocolStack.</td>
</tr>
<tr>
<td>upperBoundOfMeasureRange</td>
<td>TupleType</td>
<td>A superSubtype that asserts the MeasureInstance that is the upper bound (i.e. maximum measure) of a MeasureRange.</td>
</tr>
</tbody>
</table>

<p>Table ‑: P3 Element List</p>



# P4 – Resource Functions</h3>


{%include figure.html url="{{rasterimagepath}}/image31.png" width="605" height="510" description="" %}

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
<td>AffectedResource</td>
<td>Type</td>
<td>An IndividualRoleType where the role extent is an AffectedResourceRole and the whole is a ResourceType.</td>
</tr>
<tr>
<td>AffectedResourceRole</td>
<td>Type</td>
<td>A ModemIndividualType that is the role played by a ResourceType when it is acted upon by a Function.</td>
</tr>
<tr>
<td>ArtefactType</td>
<td>Type</td>
<td>A NonHumanResourceType that is a type of Artefact. Examples are &quot;car&quot;, &quot;radio&quot;, &quot;diesel&quot;, etc.<br />Note: It has no human components.</td>
</tr>
<tr>
<td>CapabilityConfiguration</td>
<td>Type</td>
<td>A composite structure representing the physical and human resources (and their interactions) that when brought together provide one or more Capabilities.<br />A CapabilityConfiguration is a set of Resources configured to provide a capability, and should be guided by [doctrine] which may take the form of Standard or OperationalConstraint stereotypes.</td>
</tr>
<tr>
<td>Commands</td>
<td>Type</td>
<td>A ResourceCommunication where one ResponsibleHumanResourceTypeConfigurationUsage commands another.</td>
</tr>
<tr>
<td>ConfiguredResourceType</td>
<td>Type</td>
<td>An IndividualResourcePowertype that is a part of a ResourceType another ConfiguredResourceType.</td>
</tr>
<tr>
<td>ConsumerFunction</td>
<td>Type</td>
<td>An IndividualExchangeRoleType where the role is a ResourceImport and the consumer is a Function.</td>
</tr>
<tr>
<td>Controls</td>
<td>Type</td>
<td>A ResourceCommunication where one InteractionElement controls another.</td>
</tr>
<tr>
<td>EffectFunction</td>
<td>Type</td>
<td>A TypicalWholePart that relates a ResourceFunction to the AffectedResourceRole played by a ResourceType when acted upon by the ResourceFunction.</td>
</tr>
<tr>
<td>Function</td>
<td>Type</td>
<td>A PhysicalArchitectureProcess that is either carried out by a ResourceType or a ResourceTypeUsage.</td>
</tr>
<tr>
<td>FunctionComposition</td>
<td>Type</td>
<td>A TypicalWholePart that relates a parent (whole) Function to its child (part) Function.</td>
</tr>
<tr>
<td>HumanAndNonHumanConfigurationType</td>
<td>Type</td>
<td>A ResourceType that has both Human and Non-Human components.</td>
</tr>
<tr>
<td>HumanResourceType</td>
<td>Type</td>
<td>A ResourceType that is a type of HumanResource.<br />A PersonType, PostType, OrganisationType or OrganisationRoleType. [ABSTRACT]<br />Note: was called &quot;OrganisationalResource&quot; in M3 v1.2.<br />Note: was called &quot;OrganisationalResourceType&quot; in M3.</td>
</tr>
<tr>
<td>NaturalResourceType</td>
<td>Type</td>
<td>A NonHumanResourceType that is a type of NaturalResource.</td>
</tr>
<tr>
<td>NonHumanResourceType</td>
<td>Type</td>
<td>A ResourceType that is a type of NonHumanResource (i.e. an Artefact or NaturalResource). [ABSTRACT]</td>
</tr>
<tr>
<td>OrganisationType</td>
<td>Type</td>
<td>A ResponsibleHumanResourceType and a ConstructedHumanResourceType that is a type of Organisation. This is not used as a component of a ResourceType.<br />Examples: Government Department, Commercial Company, Accounting Department.</td>
</tr>
<tr>
<td>PerformsFunction</td>
<td>Type</td>
<td>A CapableOf that asserts a Function is conducted by a ResourceType.</td>
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
<td>ProducerFunction</td>
<td>Type</td>
<td>An IndividualExchangeRoleType where the role is a ResourceExport and the producer is a ResourceFunction.</td>
</tr>
<tr>
<td>ResourceCommunication</td>
<td>Type</td>
<td>A ResourceInteraction where DataElements are exchanged.</td>
</tr>
<tr>
<td>ResourceEnergyFlow</td>
<td>Type</td>
<td>A ResourceInteraction where energy is transferred between ResourceUsages.</td>
</tr>
<tr>
<td>ResourceExport</td>
<td>Type</td>
<td>A SendType where the sender is a ResourceType or Function.</td>
</tr>
<tr>
<td>ResourceFunction</td>
<td>Type</td>
<td>A Function carried out by a ResourceType</td>
</tr>
<tr>
<td>ResourceImport</td>
<td>Type</td>
<td>A ReceiveType where the receiver is a ResourceType or Function.</td>
</tr>
<tr>
<td>ResourceInteraction</td>
<td>Type</td>
<td>An ExchangeType where two ResourceTypes interact. [ABSTRACT]<br />Examples: data exchange between systems, conversations between people, people using systems, flows of materiel from one resource to another, etc.</td>
</tr>
<tr>
<td>ResourceInteractionExport</td>
<td>Type</td>
<td>A SendInExchangeType where the sender is a ResourceType or Function.</td>
</tr>
<tr>
<td>ResourceInteractionImport</td>
<td>Type</td>
<td>A RecieveInExchangeType where the receiver is a ResourceType or Function.</td>
</tr>
<tr>
<td>ResourceMovement</td>
<td>Type</td>
<td>A ResourceInteraction where the element that flows is a ResourceType.</td>
</tr>
<tr>
<td>ResourceType</td>
<td>Type</td>
<td>A PhysicalArchitectureIndividualType that is a type of IndividualResource. This is not used as a component of a ResourceType, but may use components. [ABSTRACT]</td>
</tr>
<tr>
<td>SoftwareType</td>
<td>Type</td>
<td>An ArtefactType that is a type of Software.</td>
</tr>
<tr>
<td>UsagePerformsFunction</td>
<td>Type</td>
<td>A CapableOfType where a ResoureceTypeUsage is capable of conducting a UsageSpecificFunction.</td>
</tr>
<tr>
<td>UsageSpecificFunction</td>
<td>Type</td>
<td>A PhysicalArchitectureProcess that is a particular usage of a Function.<br />Note: this is used where there is a requirement to distinguish between two uses of a ResourceType which both have the same functionality, but put to different purposes. This is particularly important for tracing back to OV-5 Activities.</td>
</tr>
<tr>
<td>IndividualResourcePowertype</td>
<td>PowerType</td>
<td>The powertype of IndividualResourceState.</td>
</tr>
<tr>
<td>configurationType</td>
<td>TupleType</td>
<td>A superSubtype that asserts that a ResourceType is a superType of ConfiguredResourceType.</td>
</tr>
</tbody>
</table>

<p>Table ‑: P4 Element List</p>


# L4-P4 – Activity to Function Mapping


{%include figure.html url="{{rasterimagepath}}/image32.png" width="604" height="504" description="L4-P4 Logical Diagram" %}


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
<td>Type</td>
<td>An OperationalActivity that is entirely composed of other OperationalActivities.</td>
</tr>
<tr>
<td>ActivityGrouping</td>
<td>Type</td>
<td>An ActivityComposition where the parent Activity is an ActivityGroup.</td>
</tr>
<tr>
<td>ConfiguredResourceType</td>
<td>Type</td>
<td>An IndividualResourcePowertype that is a part of a ResourceType another ConfiguredResourceType.</td>
</tr>
<tr>
<td>Function</td>
<td>Type</td>
<td>A PhysicalArchitectureProcess that is either carried out by a ResourceType or a ResourceTypeUsage.</td>
</tr>
<tr>
<td>FunctionGroup</td>
<td>Type</td>
<td>A Function that is entirely composed of other Functions</td>
</tr>
<tr>
<td>FunctionGrouping</td>
<td>Type</td>
<td>A FunctionComposition where the parent is a FunctionGroup.</td>
</tr>
<tr>
<td>OperationalActivity</td>
<td>Type</td>
<td>A ProcessType that is a type of logical process, specified independently of how the process is carried out.<br />Note: an OperationalActivity may only be carried out by a logical Node.</td>
</tr>
<tr>
<td>PerformsFunction</td>
<td>Type</td>
<td>A CapableOf that asserts a Function is conducted by a ResourceType.</td>
</tr>
<tr>
<td>ResourceFunction</td>
<td>Type</td>
<td>A Function carried out by a ResourceType</td>
</tr>
<tr>
<td>ResourceType</td>
<td>Type</td>
<td>A PhysicalArchitectureIndividualType that is a type of IndividualResource. This is not used as a component of a ResourceType, but may use components. [ABSTRACT]</td>
</tr>
<tr>
<td>ServiceFunction</td>
<td>Type</td>
<td>A ServiceProcess carried out by a ServiceSpecification.</td>
</tr>
<tr>
<td>UsagePerformsFunction</td>
<td>Type</td>
<td>A CapableOfType where a ResoureceTypeUsage is capable of conducting a UsageSpecificFunction.</td>
</tr>
<tr>
<td>UsageSpecificFunction</td>
<td>Type</td>
<td>A PhysicalArchitectureProcess that is a particular usage of a Function.<br />Note: this is used where there is a requirement to distinguish between two uses of a ResourceType which both have the same functionality, but put to different purposes. This is particularly important for tracing back to OV-5 Activities.</td>
</tr>
<tr>
<td>activityFunctionMapping</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation that relates an OperationalActivity or ActivityGroup to the Function or FunctionGroup that realises it</td>
</tr>
<tr>
<td>serviceFunctionFunctionMapping</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation that relates an OperationalActivity or ActivityGroup to the Function or FunctionGroup that realises it.</td>
</tr>
</tbody>
</table>

<p>Table L4-P4 Element List</p>



# P5 – Resource States</h3>


{%include figure.html url="{{rasterimagepath}}/image33.png" width="604" height="450" description="P5 Logical Diagram" %}

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
<td>CapabilityConfiguration</td>
<td>Type</td>
<td>A composite structure representing the physical and human resources (and their interactions) that when brought together provide one or more Capabilities.<br />A CapabilityConfiguration is a set of Resources configured to provide a capability, and should be guided by [doctrine] which may take the form of Standard or OperationalConstraint stereotypes.</td>
</tr>
<tr>
<td>HumanAndNonHumanConfigurationType</td>
<td>Type</td>
<td>A ResourceType that has both Human and Non-Human components.</td>
</tr>
<tr>
<td>HumanResourceType</td>
<td>Type</td>
<td>A ResourceType that is a type of HumanResource.<br />A PersonType, PostType, OrganisationType or OrganisationRoleType. [ABSTRACT]<br />Note: was called &quot;OrganisationalResource&quot; in M3 v1.2.<br />Note: was called &quot;OrganisationalResourceType&quot; in M3.</td>
</tr>
<tr>
<td>NaturalResourceType</td>
<td>Type</td>
<td>A NonHumanResourceType that is a type of NaturalResource.</td>
</tr>
<tr>
<td>NonHumanResourceType</td>
<td>Type</td>
<td>A ResourceType that is a type of NonHumanResource (i.e. an Artefact or NaturalResource). [ABSTRACT]</td>
</tr>
<tr>
<td>OrganisationType</td>
<td>Type</td>
<td>A ResponsibleHumanResourceType and a ConstructedHumanResourceType that is a type of Organisation. This is not used as a component of a ResourceType.<br />Examples: Government Department, Commercial Company, Accounting Department.</td>
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
<td>ResourceStateType</td>
<td>Type</td>
<td></td>
</tr>
<tr>
<td>ResourceType</td>
<td>Type</td>
<td>A PhysicalArchitectureIndividualType that is a type of IndividualResource. This is not used as a component of a ResourceType, but may use components. [ABSTRACT]</td>
</tr>
<tr>
<td>SoftwareType</td>
<td>Type</td>
<td>An ArtefactType that is a type of Software.</td>
</tr>
<tr>
<td>StateMachine</td>
<td>Type</td>
<td>A StateMachineViews used to model typical states and transitions for ModemIndividualElementTypes.</td>
</tr>
<tr>
<td>StateMachineRegion</td>
<td>Type</td>
<td>A StateMachineRegions which is part of a StateMachine.</td>
</tr>
<tr>
<td>StateSpecification</td>
<td>Type</td>
<td>An OwnedStateSets used in a MODEM state machine.</td>
</tr>
<tr>
<td>StateTransition</td>
<td>Type</td>
<td>A StateSuccessionType indicating there is a possible transition between StateSpecifications.</td>
</tr>
<tr>
<td>regionOfStateMachine</td>
<td>TupleType</td>
<td>A stateMachineViewTypesRegionInstances which relates a StateMachineRegion to a StateMachine.</td>
</tr>
<tr>
<td>stateInRegion</td>
<td>TupleType</td>
<td>A regionTypeInstance that asserts a StateSpecification features in a StateMachineRegion.</td>
</tr>
<tr>
<td>stateMachineForResourceType</td>
<td>TupleType</td>
<td>A appliedStateMachine that relates a ResourceType to its state machine.</td>
</tr>
<tr>
<td>stateTransitionInRegion</td>
<td>TupleType</td>
<td>A regionTypeInstance that asserts a StateTransition features in a StateMachineRegion.</td>
</tr>
</tbody>
</table>

<p>Table ‑: P5 Element List</p>



# P6 – Resource Sequence

{%include figure.html url="{{rasterimagepath}}/image34.png" width="604" height="491" description="P6 Logical Diagram" %}

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
<td>ConfiguredResourceType</td>
<td>Type</td>
<td>An IndividualResourcePowertype that is a part of a ResourceType another ConfiguredResourceType.</td>
</tr>
<tr>
<td>Delay</td>
<td>Type</td>
<td>A TriggerItem that is a pause between Processes, Events, etc.</td>
</tr>
<tr>
<td>EventBoundedPhysicalProcess</td>
<td>Type</td>
<td>A PhysicalArchitectureProcess that can have PhysicalEvents marking its start and end points.</td>
</tr>
<tr>
<td>FunctionOnLifeline</td>
<td>Type</td>
<td>A TypicalWholePart where a SequencedActivity is part of a NodeLifeline.<br />Note: a given SequencedActivity may appear on one and only one NodeLifeline.</td>
</tr>
<tr>
<td>ImplementationScenario</td>
<td>Type</td>
<td>A Scenario that features ResourceTypes, their Functions and Interactions.</td>
</tr>
<tr>
<td>ImplementationScenarioPart</td>
<td>Type</td>
<td>A ModemIndividualType that features in (i.e. is part of) an ImplemenationScenario.</td>
</tr>
<tr>
<td>ItemInImplementationScenario</td>
<td>Type</td>
<td>An ItemInScenario where the Scenario is an ImplementationScenario.</td>
</tr>
<tr>
<td>LifelineForResource</td>
<td>Type</td>
<td>A TypicalTemporalWholePart that asserts a ResourceLifeLine is a typical temporal part of a Resource.</td>
</tr>
<tr>
<td>OperationalActivity</td>
<td>Type</td>
<td>A ProcessType that is a type of logical process, specified independently of how the process is carried out.<br />Note: an OperationalActivity may only be carried out by a logical Node.</td>
</tr>
<tr>
<td>PhysicalDelay</td>
<td>Type</td>
<td>A PhysicallySequencedItem that has a specified temporal extent, but an unspecified spatial extent.</td>
</tr>
<tr>
<td>PhysicalEndEvent</td>
<td>Type</td>
<td>An EndBorderType that relates a EventBoundedPhysicalProcess to the PhysicalEvent that marks its end<br />Note: there may be no more than one PhysicalEndEvent for a given EventBoundedPhysicalProcess.</td>
</tr>
<tr>
<td>PhysicalEvent</td>
<td>Type</td>
<td>An Event that marks the beginning or end of an EventBoundedPhysicalProcess.</td>
</tr>
<tr>
<td>PhysicalSequencing</td>
<td>Type</td>
<td>An ImmediateBeforeAfterType that asserts one PhysicallySequencedItem occurs immediately after the other.</td>
</tr>
<tr>
<td>PhysicallySequencedItem</td>
<td>Type</td>
<td>An ImplemenationScenarioPart that is physically sequenced; i.e. it has a PhysicalSequencing relation.</td>
</tr>
<tr>
<td>PhysicalStartEvent</td>
<td>Type</td>
<td>A StartBorderType that relates an EventBoundedPhysicalProcess to the PhysicalEvent that marks its start.<br />Note: there may be no more than one PhysicalStartEvent for a given PhysicallySequencedProcess.</td>
</tr>
<tr>
<td>ResourceFunction</td>
<td>Type</td>
<td>A Function carried out by a ResourceType</td>
</tr>
<tr>
<td>ResourceLifeline</td>
<td>Type</td>
<td>A ResourceStateType whose extent is defined by an ImplemenationScenario.</td>
</tr>
<tr>
<td>ResourceInteraction</td>
<td>Type</td>
<td>An ExchangeType where two ResourceTypes interact. [ABSTRACT]<br />Examples: data exchange between systems, conversations between people, people using systems, flows of materiel from one resource to another, etc.</td>
</tr>
<tr>
<td>ResourceTypeExport</td>
<td>Type</td>
<td>A CapableOfType where a ResourceInteraction exports from a ResourceTypeUsage.</td>
</tr>
<tr>
<td>ResourcTypeImport</td>
<td>Type</td>
<td>A CapableOfType where a ResourceInteraction imports from a ResourceTypeUsage.</td>
</tr>
<tr>
<td>SequencedFunction</td>
<td>Type</td>
<td>An EventBoundedPhysicalProcess that is the typical useage of a Function in a ResourceLifeLine.</td>
</tr>
<tr>
<td>SequencedResourceInteraction</td>
<td>Type</td>
<td>An ImplementationScenarioPart that is the typical occurance of a ResourceInteraction between two ResourceLifelines.</td>
</tr>
<tr>
<td>Time</td>
<td>Type</td>
<td>A MeasureInstance whose members are Individuals that have a particular temporal dimension of the same length.<br />Examples: 22 seconds, 14 weeks, The time taken for light to travel 2km in a vacuum.</td>
</tr>
<tr>
<td>TimeRange</td>
<td>Type</td>
<td>A MeasureRange where the bounds are Times.</td>
</tr>
<tr>
<td>functionInSequence</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation that relates a ResourceFunction to its usage (as a SequencedFunction) on a ResourceLifeLine.<br />Note: A SequencedFunction is based on only one Function</td>
</tr>
<tr>
<td>delayRange</td>
<td>TupleType</td>
<td>A measureOfType that relates a LogicalDelay to the delayRange in which it falls.</td>
</tr>
<tr>
<td>delayTime</td>
<td>TupleType</td>
<td>A measureOfType that relates a LogicalDelay to its Time.</td>
</tr>
<tr>
<td>interactionInScenario</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation that relates a ResourceInteraction to its usage (as a SequencedResourceInteraction) in an ImplementationScenario.<br />Note: A SequencedResourceInteraction is based on only one ResourceInteraction.</td>
</tr>
</tbody>
</table>

<p>Table ‑: P6 Element List</p>

# P5/6 – Physical Resource Triggers

{%include figure.html url="{{rasterimagepath}}image35.png" width="605" height="763" description="P5/6 Physical Resource Triggers Logical Diagram" %}

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
<td>After</td>
<td>Type</td>
<td>A BeforeAfterType where one TriggerItem starts after another has ended.<br />Note: the TriggerItem that happens after may happen at any point in time after the one that comes before it (i.e. there may be an interval of time between them).</td>
</tr>
<tr>
<td>Delay</td>
<td>Type</td>
<td>A TriggerItem that is a pause between Processes, Events, etc.</td>
</tr>
<tr>
<td>Event</td>
<td>Type</td>
<td>A TemporalBorderType whose instances are instants the mark the temporal beginning or end of an Individual.</td>
</tr>
<tr>
<td>EventBoundedPhysicalProcess</td>
<td>Type</td>
<td>A PhysicalArchitectureProcess that can have PhysicalEvents marking its start and end points.</td>
</tr>
<tr>
<td>ImmediatelyAfter</td>
<td>Type</td>
<td>An After where the subsequent TriggerItem starts immediately as the preceeding TriggerItem ends.</td>
</tr>
<tr>
<td>PhysicalDelay</td>
<td>Type</td>
<td>A PhysicallySequencedItem that has a specified temporal extent, but an unspecified spatial extent.</td>
</tr>
<tr>
<td>PhysicalEndEvent</td>
<td>Type</td>
<td>An EndBorderType that relates a EventBoundedPhysicalProcess to the PhysicalEvent that marks its end<br />Note: there may be no more than one PhysicalEndEvent for a given EventBoundedPhysicalProcess.</td>
</tr>
<tr>
<td>PhysicalEvent</td>
<td>Type</td>
<td>An Event that marks the beginning or end of a EventBoundedPhysicalProcess.</td>
</tr>
<tr>
<td>PhysicalStartEvent</td>
<td>Type</td>
<td>A StartBorderType that relates an EventBoundedPhysicalProcess to the PhysicalEvent that marks its start.<br />Note: there may be no more than one PhysicalStartEvent for a given PhysicallySequencedProcess.</td>
</tr>
<tr>
<td>ResourceStateType</td>
<td>Type</td>
<td>A type of state that a ResourceType may have.</td>
</tr>
<tr>
<td>SequencedFunction</td>
<td>Type</td>
<td>An EventBoundedPhysicalProcess that is the typical useage of a Function in a ResourceLifeLine.</td>
</tr>
<tr>
<td>SequencedResourceInteraction</td>
<td>Type</td>
<td>An ImplementationScenarioPart that is the typical occurance of a ResourceInteraction between two ResourceLifelines.</td>
</tr>
<tr>
<td>StartsAfter</td>
<td>Type</td>
<td>A WeakTemporalOrderingType that asserts one TriggerItem starts before another.<br />Note: there is constraint on when either TriggerItem ends - hence if A starts before B, it is possible that B ends before A and indeed that A ends before B.</td>
</tr>
<tr>
<td>StartsImmediatelyAfter</td>
<td>Type</td>
<td>A StartsAfter where the subsequent TriggerItem starts immediately after the preceeding TriggerItem.</td>
</tr>
<tr>
<td>StateSpecification</td>
<td>Type</td>
<td>An OwnedStateSets used in a MODEM state machine.</td>
</tr>
<tr>
<td>StateTransition</td>
<td>Type</td>
<td>A StateSuccessionType indicating there is a possible transition between StateSpecifications.</td>
</tr>
<tr>
<td>TriggerItem</td>
<td>Type</td>
<td>A ModemIndividualType that can be the cause or effect of a Trigger.</td>
</tr>
</tbody>
</table>


<p>Table ‑: P5/6 Physical Resource Triggers Element List</p>

# P7 – Physical Data Model


{%include figure.html url="{{rasterimagepath}}image36.png" width="604" height="498" description="P7 Logical Diagram" %}

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
<td>AggregateDataType</td>
<td>Type</td>
<td>A DataModelTypeRepresentation which is an aggregate of other DataModelTypeRepresentations.</td>
</tr>
<tr>
<td>ArrayDataType</td>
<td>Type</td>
<td>An AggregateDataType whose members are addressed using a numeric index.</td>
</tr>
<tr>
<td>Attribute</td>
<td>Type</td>
<td>A DataModelComponent that is a defined property of an Entity.</td>
</tr>
<tr>
<td>BagDataType</td>
<td>Type</td>
<td>An AggregateDataType whose members are not kept in any particular order - i.e. there is no way to address a particular member.</td>
</tr>
<tr>
<td>BinaryDataType</td>
<td>Type</td>
<td>A SimpleDataType whose instances are binary objects.<br />Note: Data Models may instantiate several different BinaryDataTypes - e.g. &quot;BLOB&quot;, &quot;MPEG&quot;, &quot;varbinary&quot;, etc</td>
</tr>
<tr>
<td>CardinalitySpecifier</td>
<td>Type</td>
<td>An IntegerRepresentation that specifies the cardinality of an EntityRelationshipEnd.</td>
</tr>
<tr>
<td>ChoiceDataType</td>
<td>Type</td>
<td>A DataModelTypeRepresentation which represents a choice of datatypes, restricted by the architect to a list.<br />Note: Also known as a SELECT in some data modelling languages (e.g. ISO10303-11).</td>
</tr>
<tr>
<td>DataElement</td>
<td>Type</td>
<td>A SymbolOrSymbolStringType that represents interactions between resource elements.</td>
</tr>
<tr>
<td>DataElementWholePart</td>
<td>Type</td>
<td>A TypicalWholePart where one DataElement is a part of another.</td>
</tr>
<tr>
<td>DataModel</td>
<td>Type</td>
<td>A StructuredRepresentation defining the structure of data, showing classifications of data elements and relationships between them..</td>
</tr>
<tr>
<td>DataModelComponent</td>
<td>Type</td>
<td>A Representation that can be part of a DataModel.</td>
</tr>
<tr>
<td>DataModelTypeRepresentation</td>
<td>Type</td>
<td>A DataModelComponent that can be used to represent the type of something.</td>
</tr>
<tr>
<td>EndOfEntityRelationship</td>
<td>Type</td>
<td>A RepresentationStructure where an EntityRelationship has 2 or more EntityRelationshipEnds.</td>
</tr>
<tr>
<td>Entity</td>
<td>Type</td>
<td>A DataModelComponent that defines an item of interest..</td>
</tr>
<tr>
<td>EntityRelationship</td>
<td>Type</td>
<td>A DataModelComponent that represents a relationship between two or more Entities.</td>
</tr>
<tr>
<td>EnumerationType</td>
<td>Type</td>
<td>A DataModelTypeRepresentation which consists of named values.</td>
</tr>
<tr>
<td>FloatingPointDataType</td>
<td>Type</td>
<td>A NumericDataType whose instances are real numbers.<br />Note: Data Models may instantiate several different IntegerDataTypes - e.g. &quot;float&quot;, &quot;double&quot;, &quot;real&quot;, etc.</td>
</tr>
<tr>
<td>HashedAggregate</td>
<td>Type</td>
<td>An AggregateDataType whose members are indexed using an identifier.</td>
</tr>
<tr>
<td>IntegerDataType</td>
<td>Type</td>
<td>A NumericDataType whose instances are integer numbers.<br />Note: Data Models may instantiate several different IntegerDataTypes - e.g. &quot;LongInt&quot;, &quot;short&quot;, &quot;word&quot;, etc</td>
</tr>
<tr>
<td>ItemInDataModel</td>
<td>Type</td>
<td>A RepresentationInStructure where a DataModelComponent is part of a DataModel</td>
</tr>
<tr>
<td>ListDataType</td>
<td>Type</td>
<td>An AggregateDataType whose members are stored and accessed as an ordered list.</td>
</tr>
<tr>
<td>LogicalDataType</td>
<td>Type</td>
<td>A SimpleDataType whose instances are true/false or true/false/unknown.<br />Note: Data Models may instantiate several different LogicalDataTypes - e.g. &quot;Boolean&quot;, &quot;YesNo&quot;, &quot;BOOL&quot;, etc.</td>
</tr>
<tr>
<td>MaxAggregateSize</td>
<td>Type</td>
<td>A RepresentationInStructure that specifies the maximum size of an AggregateDataType.</td>
</tr>
<tr>
<td>MinAggregateSize</td>
<td>Type</td>
<td>A RepresentationInStructure that specifies the minimum size of an AggregateDataType.</td>
</tr>
<tr>
<td>MaxCardinalityOfRelationshipEnd</td>
<td>Type</td>
<td>A RepresentationInStructure that asserts a CardinalitySpecifier is part of an EntityRelationshipEnd, and that it represents the maximum cardinality value of that end.<br />Note: If no Maximum Cardinality is specified (i.e. there is no instance of this tuple type related to the EntityRelationshipEnd) then the default is &quot;many&quot; or &quot;* &quot;.</td>
</tr>
<tr>
<td>MinCardinalityOfRelationshipEnd</td>
<td>Type</td>
<td>A RepresentationInStructure that asserts a CardinalitySpecifier is part of an EntityRelationshipEnd, and that it represents the minimum cardinality value of that end.<br />Note: If no Minimum Cardinality is specified (i.e. there is no instance of this tuple type related to the EntityRelationshipEnd) then the default is zero.</td>
</tr>
<tr>
<td>NumericDataType</td>
<td>Type</td>
<td>A SimpleDataType whose instances are numbers.</td>
</tr>
<tr>
<td>PhysicalDataModel</td>
<td>Type</td>
<td>A DataModel that is an implementable specification of a data structure. A PhysicalDataModel realises a LogicalDataModel, taking into account implementation restrictions and performance issues whilst still enforcing the constraints, relationships and typing of the logical model.</td>
</tr>
<tr>
<td>SimpleDataType</td>
<td>Type</td>
<td>A DataModelTypeRepresentation that is used to specify the type of a literal (e.g. text, integer, floating point number, etc.).</td>
</tr>
<tr>
<td>SoftwareType</td>
<td>Type</td>
<td>An ArtefactType that is a type of Software.</td>
</tr>
<tr>
<td>StringRepresentation</td>
<td>Type</td>
<td>A Representation whose all members are all strings.</td>
</tr>
<tr>
<td>TextDataType</td>
<td>Type</td>
<td>A SimpleDataType whose instances are text literals.<br />Note: Data Models may instantiate several different TextDataTypes - e.g. &quot;String&quot;, &quot;XML Text&quot;, &quot;WideString&quot;, etc.</td>
</tr>
<tr>
<td>aggregateElementType</td>
<td>TupleType</td>
<td>A couple that relates an AggregateDataType to the DataModelTypeRepresentation that specifies the data type of each of its elements.</td>
</tr>
<tr>
<td>attributeType</td>
<td>TupleType</td>
<td>A couple that relates an Attribute to the DataModelTypeRepresentation that specifies its type.</td>
</tr>
<tr>
<td>choiceElement</td>
<td>TupleType</td>
<td>A couple that asserts a DataModelTypeRepresentation is a valid choice in a ChoiceDataType.</td>
</tr>
<tr>
<td>dataElementRepresentation</td>
<td>TupleType</td>
<td>A representedByDataType that asserts a DataElement is represented by a DataModelTypeRepresentation.</td>
</tr>
<tr>
<td>enumerationItem</td>
<td>TupleType</td>
<td>A Couple that relates a StringRepresentation to an EnumerationType of which it is an element.</td>
</tr>
<tr>
<td>entityHasAttribute</td>
<td>TupleType</td>
<td>A couple asserting that an Entity has an Attribute.</td>
</tr>
<tr>
<td>entityRelationship</td>
<td>TupleType</td>
<td>A DataModelComponent that represents a relationship between two or more Entities.</td>
</tr>
<tr>
<td>implementsDataModel</td>
<td>TupleType</td>
<td>A couple that asserts that a SoftwareType implements a PhysicalDataModel.</td>
</tr>
<tr>
<td>subtypeRelationship</td>
<td>TupleType</td>
<td>A couple that asserts that the type represented by one Entity is a subtype of the type represented by the other Entity.</td>
</tr>
</tbody>
</table>

<p>Table ‑: P7 Element List</p>



# P8 – Resource Constraints


{%include figure.html url="{{rasterimagepath}}image37.png" width="604" height="424" description="P8 Logical Diagram" %}

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
<td>Constraint</td>
<td>Type</td>
<td>An IndividualType that is the collection of all the objects subject to a particular constraint.</td>
</tr>
<tr>
<td>ConfiguredResourceType</td>
<td>Type</td>
<td>An IndividualResourcePowertype that is a part of a ResourceType another ConfiguredResourceType.</td>
</tr>
<tr>
<td>DataElement</td>
<td>Type</td>
<td>A SymbolOrSymbolStringType that represents interactions between resource elements.</td>
</tr>
<tr>
<td>Function</td>
<td>Type</td>
<td>A PhysicalArchitectureProcess that is either carried out by a ResourceType or a ResourceTypeUsage.</td>
</tr>
<tr>
<td>InteractionElement</td>
<td>Type</td>
<td>A ModemIndividualType that is the Role played by an InteractionElement in a ResourceInteraction. [ABSTRACT]</td>
</tr>
<tr>
<td>ModemIndividualType</td>
<td>Type</td>
<td>The parent (supertype) of all MODEM elements that are types of Individuals e.g. tank, computer, etc.</td>
</tr>
<tr>
<td>PhysicalArchitectureIndividualType</td>
<td>Type</td>
<td>A ModemIndividualType that is involved in a PhysicalArchitecture.</td>
</tr>
<tr>
<td>Port</td>
<td>Type</td>
<td>An ArtefactComponent that is a type of IndividualPort.<br />Note: was called &quot;ResourcePort&quot; in M3.</td>
</tr>
<tr>
<td>ResourceType</td>
<td>Type</td>
<td>A PhysicalArchitectureIndividualType that is a type of IndividualResource. This is not used as a component of a ResourceType, but may use components. [ABSTRACT]</td>
</tr>
<tr>
<td>IndividualResource</td>
<td>IndividualType</td>
<td>A ModemIndividualElement that is an IndividualOrganisationalResource, an ItemOfMateriel or a ResourceConfiguration.</td>
</tr>
<tr>
<td>ModemIndividualElement</td>
<td>IndividualType</td>
<td>An Individual that can feature in a MODEM architecture.</td>
</tr>
<tr>
<td>constraintOnIndividual</td>
<td>TupleType</td>
<td>A couple that asserts a constraint placed upon a ModemThing related to a ModemThing.</td>
</tr>
<tr>
<td>constraintOnType</td>
<td>TupleType</td>
<td>A superSubtype that asserts all the instances of the subType object are subject to the constraint.</td>
</tr>
</tbody>
</table>

<p>Table ‑: P8 Element List</p>




# Pr – Configuration Management</h3>



{%include figure.html url="{{rasterimagepath}}image38.png" width="604" height="446 description="Pr Logical Diagram<" %}

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
<td>CapabilityConfiguration</td>
<td>Type</td>
<td>A composite structure representing the physical and human resources (and their interactions) that when brought together provide one or more Capabilities.<br />A CapabilityConfiguration is a set of Resources configured to provide a capability, and should be guided by [doctrine] which may take the form of Standard or OperationalConstraint stereotypes.</td>
</tr>
<tr>
<td>HumanAndNonHumanConfigurationType</td>
<td>Type</td>
<td>A ResourceType that has both Human and Non-Human components.</td>
</tr>
<tr>
<td>HumanResourceType</td>
<td>Type</td>
<td>A ResourceType that is a type of HumanResource.<br />A PersonType, PostType, OrganisationType or OrganisationRoleType. [ABSTRACT]<br />Note: was called &quot;OrganisationalResource&quot; in M3 v1.2.<br />Note: was called &quot;OrganisationalResourceType&quot; in M3.</td>
</tr>
<tr>
<td>NaturalResourceType</td>
<td>Type</td>
<td>A NonHumanResourceType that is a type of NaturalResource.</td>
</tr>
<tr>
<td>NonHumanResourceType</td>
<td>Type</td>
<td>A ResourceType that is a type of NonHumanResource (i.e. an Artefact or NaturalResource). [ABSTRACT]</td>
</tr>
<tr>
<td>OrganisationType</td>
<td>Type</td>
<td>A ResponsibleHumanResourceType and a ConstructedHumanResourceType that is a type of Organisation. This is not used as a component of a ResourceType.<br />Examples: Government Department, Commercial Company, Accounting Department.</td>
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
<td>ResourceTypeMaster</td>
<td>Type</td>
<td>A ModemIndividualType that is the master specification from which ResourceTypes are versioned.</td>
</tr>
<tr>
<td>SoftwareType</td>
<td>Type</td>
<td>An ArtefactType that is a type of Software.</td>
</tr>
<tr>
<td>StringRepresentation</td>
<td>Type</td>
<td>A Representation whose all members are all strings.</td>
</tr>
<tr>
<td>VersionSuccession</td>
<td>Type</td>
<td>A BeforeAfterType that asserts one ResourceType succeeds another<br />Note: both ResourceTypes must be versions of the same ResourceTypeMaster.</td>
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
<td>A ProjectState that is a temporal part of a Project and has been nominated as a phase of a Project.</td>
</tr>
<tr>
<td>projectWholePhase</td>
<td>TupleType</td>
<td>A projectPhaseTemporalPart where the whole is a Project.</td>
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
<td>designReleasedAtMilestone</td>
<td>TupleType</td>
<td>A couple that indicates a ResourceType is released as a design at a ProjectMilestone.</td>
</tr>
<tr>
<td>designWithdrawnAtMilestone</td>
<td>TupleType</td>
<td>A couple that indicates a ResourceType was withdrawn as a design at a ProjectMilestone.</td>
</tr>
<tr>
<td>versionIdentifier</td>
<td>TupleType</td>
<td>A representedBy that asserts that a StringRepresentation represents the version identifier of a ServiceSpecification.</td>
</tr>
<tr>
<td>versionOf</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation that asserts a ResourceType is a version of a ResourceTypeMaster.</td>
</tr>
</tbody>
</table>

<p>Table ‑: Pr Element List</p>
