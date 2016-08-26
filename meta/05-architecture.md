

{%include figure.html url="{{rasterimagepath}}" description="" %}

---
title: Physical Resource Specifications Layer
---


# P1 – Resource Types


<p><img src="images/media/image28.png" width="605" height="476" /><br /><span id="_Toc393217520" class="anchor"></span>Figure ‑: P1 Logical Diagram</p>

{%include figure.html url="{{rasterimagepath}}" description="" %}


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


<p><span id="_Toc393217570" class="anchor"></span>Table ‑: P1 Element List</p>


# P2 – Resource Structure</h3>


<p><img src="images/media/image29.png" width="605" height="421" /><br /><span id="_Toc393217521" class="anchor"></span>Figure ‑: P2 Logical Diagram</p>

{%include figure.html url="{{rasterimagepath}}" description="" %}

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
<p><span id="_Toc393217571" class="anchor"></span>Table ‑: P2 Element List</p>


#  P3 – Resource Connectivity</h3>
<p><img src="images/media/image30.png" width="604" height="448" /><br /><span id="_Toc393217522" class="anchor"></span>Figure ‑: P3 Logical Diagram</p>

{%include figure.html url="{{rasterimagepath}}" description="" %}

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

<p><span id="_Toc393217572" class="anchor"></span>Table ‑: P3 Element List</p>



# P4 – Resource Functions</h3>

<p><img src="images/media/image31.png" width="605" height="510" /><br /><span id="_Toc393217523" class="anchor"></span>Figure ‑: P4 Logical Diagram</p>

{%include figure.html url="{{rasterimagepath}}" description="" %}

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

<p><span id="_Toc393217573" class="anchor"></span>Table ‑: P4 Element List</p>


# L4-P4 – Activity to Function Mapping


<p><img src="images/media/image32.png" width="604" height="504" /><br /><span id="_Toc393217524" class="anchor"></span>Figure ‑: L4-P4 Logical Diagram</p>

{%include figure.html url="{{rasterimagepath}}" description="" %}


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

<p><span id="_Toc393217574" class="anchor"></span>Table ‑: L4-P4 Element List</p>



# P5 – Resource States</h3>

<p><img src="images/media/image33.png" width="604" height="450" /><br /><span id="_Toc393217525" class="anchor"></span>Figure ‑: P5 Logical Diagram</p>

{%include figure.html url="{{rasterimagepath}}" description="" %}

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

<p><span id="_Toc393217575" class="anchor"></span>Table ‑: P5 Element List</p>



# P6 – Resource Sequence

<p><img src="images/media/image34.png" width="604" height="491" /><br />Figure 4-33: P6 Logical Diagram</p>

{%include figure.html url="{{rasterimagepath}}" description="" %}

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

<p><span id="_Toc393217576" class="anchor"></span>Table ‑: P6 Element List</p>

# P5/6 – Physical Resource Triggers

<p><img src="images/media/image35.png" width="605" height="763" /><br /><span id="_Toc393217527" class="anchor"></span>Figure ‑: P5/6 Physical Resource Triggers Logical Diagram</p>

{%include figure.html url="{{rasterimagepath}}" description="" %}

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


<p><span id="_Toc393217577" class="anchor"></span>Table ‑: P5/6 Physical Resource Triggers Element List</p>


# P7 – Physical Data Model

<p><img src="images/media/image36.png" width="604" height="498" /><br /><span id="_Toc393217528" class="anchor"></span>Figure ‑: P7 Logical Diagram</p>

{%include figure.html url="{{rasterimagepath}}" description="" %}

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
<td>A RepresentationInStructure that asserts a CardinalitySpecifier is part of an EntityRelationshipEnd, and that it represents the maximum cardinality value of that end.<br />Note: If no Maximum Cardinality is specified (i.e. there is no instance of this tuple type related to the EntityRelationshipEnd) then the default is &quot;many&quot; or &quot;*&quot;.</td>
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

<p><span id="_Toc393217578" class="anchor"></span>Table ‑: P7 Element List</p>



# P8 – Resource Constraints</h3>

<p><img src="images/media/image37.png" width="604" height="424" /><br /><span id="_Toc393217529" class="anchor"></span>Figure ‑: P8 Logical Diagram</p>

{%include figure.html url="{{rasterimagepath}}" description="" %}

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

<p><span id="_Toc393217579" class="anchor"></span>Table ‑: P8 Element List</p>




# Pr – Configuration Management</h3>


<p><img src="images/media/image38.png" width="604" height="446" /><br /><span id="_Toc393217530" class="anchor"></span>Figure ‑: Pr Logical Diagram</p>


{%include figure.html url="{{rasterimagepath}}" description="" %}

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

<p><span id="_Toc393217580" class="anchor"></span>Table ‑: Pr Element List</p>


---
title: Architecture Meta-Data Layer
---

# A1 – Meta-Data Definitions

<p><img src="images/media/image39.png" width="604" height="353" /><br /><span id="_Toc393217534" class="anchor"></span>Figure ‑: A1 Logical Diagram</p>

{%include figure.html url="{{rasterimagepath}}" description="" %}


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

<p><span id="_Toc393217584" class="anchor"></span>Table ‑: A1 Element List</p>



# A2 – Architecture Products</h3>

<p><img src="images/media/image40.png" width="604" height="258" /><br /><span id="_Toc393217535" class="anchor"></span>Figure ‑: A2 Logical Diagram</p>

{%include figure.html url="{{rasterimagepath}}" description="" %}

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

<p><span id="_Toc393217585" class="anchor"></span>Table ‑: A2 Element List</p>


# A3 – Architecture Correspondence</h3>

<p><img src="images/media/image41.png" width="605" height="314" /><br /><span id="_Toc393217536" class="anchor"></span>Figure ‑: A3 Logical Diagram</p>

{%include figure.html url="{{rasterimagepath}}" description="" %}

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

<p><span id="_Toc393217586" class="anchor"></span>Table ‑: A3 Element List</p>



# A4 – Methodology Used

<p><img src="images/media/image42.png" width="605" height="225" /><br /><span id="_Toc393217537" class="anchor"></span>Figure ‑: A4 Logical Diagram</p>

{%include figure.html url="{{rasterimagepath}}" description="" %}

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
<p><span id="_Toc393217587" class="anchor"></span>Table ‑: A4 Element List</p>
<h3 id="a5-architecture-status">4.7.5 A5 – Architecture Status</h3>
<p><img src="images/media/image43.png" width="610" height="381" /><br /><span id="_Toc393217538" class="anchor"></span>Figure ‑: A5 Logical Diagram</p>
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

<p><span id="_Toc393217588" class="anchor"></span>Table ‑: A5 Element List</p>


# A6 – Architecture Versions</h3>

<p><img src="images/media/image44.png" width="604" height="194" /><br /><span id="_Toc393217539" class="anchor"></span>Figure ‑: A6 Logical Diagram</p>

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

<p><span id="_Toc393217589" class="anchor"></span>Table ‑: A6 Element List</p>


# A7 – Architecture Meta-Data</h3>

<p><img src="images/media/image45.png" width="604" height="353" /><br /><span id="_Toc393217540" class="anchor"></span>Figure ‑: A7 Logical Diagram</p>

{%include figure.html url="{{rasterimagepath}}" description="" %}

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

<p><span id="_Toc393217590" class="anchor"></span>Table ‑: A7 Element List</p>

# A8 – Standards

<p><img src="images/media/image46.png" width="604" height="342" /><br /><span id="_Toc393217541" class="anchor"></span>Figure ‑: A8 Logical Diagram</p>

{%include figure.html url="{{rasterimagepath}}" description="" %}

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

<p><span id="_Toc393217591" class="anchor"></span>Table ‑: A8 Element List</p>

# Ar – Architecture Roadmap</h3>

<p><img src="images/media/image47.png" width="602" height="430" /><br /><span id="_Toc393217542" class="anchor"></span>Figure ‑: Ar Logical Diagram</p>


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

<p><span id="_Toc393217592" class="anchor"></span>Table ‑: Ar Element List</p>
