


{%include figure.html url="{{rasterimagepath}}" description="" %}


---
title: Logical Specifications Layer
---


# L1 – Node Types


{%include figure.html url="{{rasterimagepath}}image20.png" width="604" height="795"" description="L1 Logical Diagram" %}

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
<td>DomainInArchitecture</td>
<td>Type</td>
<td>A ModemWholePartType that asserts a LogicalDomain is part of a LogicalArchitecture.</td>
</tr>
<tr>
<td>LogicalArchitecture</td>
<td>Type</td>
<td>A NodeParent whose parts are either Nodes, KnownResources or LogicalDomains.</td>
</tr>
<tr>
<td>LogicalDomain</td>
<td>Type</td>
<td>A NodeParent that is a collection of Nodes that share some common feature.</td>
</tr>
<tr>
<td>LogicalIndividualType</td>
<td>Type</td>
<td>A ModemIndividualType that is specified independently of any implemenation mechanism (i.e. without specifying the ResourceType).</td>
</tr>
<tr>
<td>LogicalProcess</td>
<td>Type</td>
<td>A ProcessType used to specify functionality without being specific about the type of Resource that provides the functionality.</td>
</tr>
<tr>
<td>Measure</td>
<td>Type</td>
<td>A Property whose members are Individuals that all share a common, measurable property, or whose properties lie within a MeasureRange.<br />Examples: 2kg, 4 weeks, 2km.</td>
</tr>
<tr>
<td>MeasureCategory</td>
<td>Type</td>
<td>A MeasureType whose members are recognised types of MeasureInstance.<br />Examples: Mass (included in IDEAS), Length (included in IDEAS), Velocity, Hardness.</td>
</tr>
<tr>
<td>MeasureInContext</td>
<td>Type</td>
<td>A ModemIndividualType that brings together EnvironmentalFactors with a Measure in order to qualify the measure<br />Examples: 40mph in desert, 1km range in cloudy conditions</td>
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
<td>Node</td>
<td>Type</td>
<td>A NodeState that is used in context of a NodeParent.</td>
</tr>
<tr>
<td>NodeParent</td>
<td>Type</td>
<td>A LogicalIndividualType that is any type of thing that has subTypes that are Nodes.</td>
</tr>
<tr>
<td>NodeRole</td>
<td>Type</td>
<td>A RoleInLogicalProcess which is the extent of a Node's participation in an OperationalActivity.<br />Note: An OperationalActivity can only be conducted by one Node.</td>
</tr>
<tr>
<td>NodeUsage</td>
<td>Type</td>
<td>An AgentWholeAndPartType where a NodeParent has a Node as a part.</td>
</tr>
<tr>
<td>OperationalActivity</td>
<td>Type</td>
<td>A ProcessType that is a type of logical process, specified independently of how the process is carried out.<br />Note: an OperationalActivity may only be carried out by a logical Node.</td>
</tr>
<tr>
<td>SecurityDomain</td>
<td>Type</td>
<td>A LogicalDomain whose parts all share a common SecurityPolicy.</td>
</tr>
<tr>
<td>SecurityPolicy</td>
<td>Type</td>
<td>A Constraint that is concerned with security.</td>
</tr>
<tr>
<td>capabilityForNode</td>
<td>TupleType</td>
<td>A bodyTypeSuperSubType that asserts that a Node exhibits or is required to exhibit a Capability.</td>
</tr>
<tr>
<td>environmentalContext</td>
<td>TupleType</td>
<td>A couple that relates a MeasureInContext to an EnvironmentalFactor in order to qualify the measure.</td>
</tr>
<tr>
<td>logicalSecurityPolicy</td>
<td>TupleType</td>
<td>A constraintOnType that sets the security policy for LogicalIndividualType.</td>
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
<td>qualifiedMeasure</td>
<td>TupleType</td>
<td>A superSubtype that relates a MeasureInContext to the measure it qualifies.</td>
</tr>
<tr>
<td>requiredMeasureOfPerformance</td>
<td>TupleType</td>
<td>A measureOfType that asserts a Node is required to achieve a level of performance specified by a Measure.</td>
</tr>
<tr>
<td>upperBoundOfMeasureRange</td>
<td>TupleType</td>
<td>A superSubtype that asserts the MeasureInstance that is the upper bound (i.e. maximum measure) of a MeasureRange.</td>
</tr>
</tbody>
</table>

<p>>Table ‑: L1 Element List</p>



# L2 – Logical Scenario


{%include figure.html url="{{rasterimagepath}}image21.png" width="604" height="601" description="L2 Logical Diagram" %}

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
<td>CBRNEnvironment</td>
<td>Type</td>
<td>An EnvironmentalFactor that defines the type of chemical, biological, radiological and nuclear environment in which an Enterprise may operate.</td>
</tr>
<tr>
<td>ConsumerRoleInService</td>
<td>Type</td>
<td>An AgentParticipationType that relates a ServiceSpecification to its role in supporting an OperationalActivity.</td>
</tr>
<tr>
<td>DomainInArchitecture</td>
<td>Type</td>
<td>A ModemWholePartType that asserts a LogicalDomain is part of a LogicalArchitecture.</td>
</tr>
<tr>
<td>EnvironmentalFactor</td>
<td>Type</td>
<td>A GeopoliticalLocationStateType that defines some aspect of the environment in which an Enterprise may operate.</td>
</tr>
<tr>
<td>FlowBundle</td>
<td>Type</td>
<td>A TypicalWholePart where the whole is a FlowGroup and the part is a LogicalFlow.</td>
</tr>
<tr>
<td>FlowGroup</td>
<td>Type</td>
<td>A LogicalFlow that is composed of other LogicalFlows.</td>
</tr>
<tr>
<td>FromNode</td>
<td>Type</td>
<td>An RoleInLogicalProcess where a LogicalFlow flows from a Node.</td>
</tr>
<tr>
<td>GeoName</td>
<td>Type</td>
<td>A StringName that identifies a GeopoliticalLocation<br />Examples: &quot;France&quot;, &quot;London, England&quot;, &quot;Magnetic North Pole&quot;, &quot;-90+000+2800CRSWGS_84/&quot;.</td>
</tr>
<tr>
<td>InformationFlow</td>
<td>Type</td>
<td>A LogicalFlow where the FlowedElement is information.</td>
</tr>
<tr>
<td>IntegerRepresentation</td>
<td>Type</td>
<td>A NumericSignType and Representation in which a string of digits (or bits) represents an integer.</td>
</tr>
<tr>
<td>ISO6709Representation</td>
<td>Type</td>
<td>GeoName expressed using the ISO6709:2008 standard notation. Examples: &quot;-90+000+2800CRSWGS_84/&quot;, &quot;+48.8577+002.295/&quot;.</td>
</tr>
<tr>
<td>KnownResource</td>
<td>Type</td>
<td>A ResourceType that plays a part in a LogicalArchitecture.<br />Note: An OV-2 is meant to show logical interactions between nodes. However, sometimes it is known that a connection runs to/from a particular type of resource.</td>
</tr>
<tr>
<td>LightConditions</td>
<td>Type</td>
<td>An EnvironmentmentalFactor that defines the types of light (e.g. broad daylight, dusk, moonlit, etc.) in which an Enterprise may operate.</td>
</tr>
<tr>
<td>LogicalArchitecture</td>
<td>Type</td>
<td>A NodeParent whose parts are either Nodes, KnownResources or LogicalDomains.</td>
</tr>
<tr>
<td>LogicalFlow</td>
<td>Type</td>
<td>An ExchangeType that flows between OperationalActivities and/or Nodes.</td>
</tr>
<tr>
<td>LogicalIndividualType</td>
<td>Type</td>
<td>A ModemIndividualType that is specified independently of any implemenation mechanism (i.e. without specifying the ResourceType).</td>
</tr>
<tr>
<td>LogicalProcess</td>
<td>Type</td>
<td>A ProcessType used to specify functionality without being specific about the type of Resource that provides the functionality.</td>
</tr>
<tr>
<td>LogicalServiceConsumerRole</td>
<td>Type</td>
<td>A ParticipationExtentType which is the extent of an OperationalActivity's participation in as the consumer of a ServiceSpecification.</td>
</tr>
<tr>
<td>Measure</td>
<td>Type</td>
<td>A Property whose members are Individuals that all share a common, measurable property, or whose properties lie within a MeasureRange.<br />Examples: 2kg, 4 weeks, 2km.</td>
</tr>
<tr>
<td>MeasureCategory</td>
<td>Type</td>
<td>A MeasureType whose members are recognised types of MeasureInstance.<br />Examples: Mass (included in IDEAS), Length (included in IDEAS), Velocity, Hardness.</td>
</tr>
<tr>
<td>MeasureInContext</td>
<td>Type</td>
<td>A ModemIndividualType that brings together EnvironmentalFactors with a Measure in order to qualify the measure.<br />Examples: 40mph in desert, 1km range in cloudy conditions</td>
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
<td>Needline</td>
<td>Type</td>
<td>A FlowGroup that is a bundle of LogicalFlows between Nodes.</td>
</tr>
<tr>
<td>Node</td>
<td>Type</td>
<td>A NodeState that is used in context of a NodeParent.</td>
</tr>
<tr>
<td>NodeEnvironment</td>
<td>Type</td>
<td>A TypicalWholePart that indicates an of EnvironmentalFactor of the environment in which the Node will operate.</td>
</tr>
<tr>
<td>NodeParent</td>
<td>Type</td>
<td>A LogicalIndividualType that is any type of thing that has subTypes that are Nodes.</td>
</tr>
<tr>
<td>NodeRole</td>
<td>Type</td>
<td>A RoleInLogicalProcess which is the extent of a Node's participation in an OperationalActivity.<br />Note: An OperationalActivity can only be conducted by one Node.</td>
</tr>
<tr>
<td>NodeUsage</td>
<td>Type</td>
<td>An AgentWholeAndPartType where a NodeParent has a Node as a part.</td>
</tr>
<tr>
<td>OperationalActivity</td>
<td>Type</td>
<td>A ProcessType that is a type of logical process, specified independently of how the process is carried out.<br />Note: an OperationalActivity may only be carried out by a logical Node.</td>
</tr>
<tr>
<td>ProblemDomain</td>
<td>Type</td>
<td>A LogicalDomain that contains (has parts that are) those Nodes which may be realised by physical resources specified in SV-1.<br />There may be more than one alternative solution for a given ProblemDomain specified as a set of SV suites. There may be only one ProblemDomain in a LogicalArchitecture.</td>
</tr>
<tr>
<td>ResourceFlow</td>
<td>Type</td>
<td>A LogicalFlow where the flowed element is a ResourceType.</td>
</tr>
<tr>
<td>ResourceType</td>
<td>Type</td>
<td>A PhysicalArchitectureIndividualType that is a type of IndividualResource. This is not used as a component of a ResourceType, but may use components. [ABSTRACT].</td>
</tr>
<tr>
<td>SecurityDomain</td>
<td>Type</td>
<td>A LogicalDomain whose parts all share a common SecurityPolicy.</td>
</tr>
<tr>
<td>SecurityPolicy</td>
<td>Type</td>
<td>A Constraint that is concerned with security.</td>
</tr>
<tr>
<td>ServiceConsumerNodeRole</td>
<td>Type</td>
<td>A ProcessWholeRoleExtentType that relates an OperationalActivity to the role of a ServiceSpecification that supports it.</td>
</tr>
<tr>
<td>ServiceLevel</td>
<td>Type</td>
<td>A ServiceDeliveryType based on a ServiceSpecification that sets a level of service using of Measures that correspond to ServiceAttributes.</td>
</tr>
<tr>
<td>ServiceSpecification</td>
<td>Type</td>
<td>A ServiceDeliveryType that is the specification of a ServiceDelivery<br />Note: was called &quot;Service&quot; in M3.</td>
</tr>
<tr>
<td>StringName</td>
<td>Type</td>
<td>A Name and a StringRepresentations that is a name expressed as text.</td>
</tr>
<tr>
<td>StringRepresentation</td>
<td>Type</td>
<td>A Representation whose all members are all strings.</td>
</tr>
<tr>
<td>TerrainType</td>
<td>Type</td>
<td>An EnvironmentalFactor that defines the type of ground conditions that an Enterprise may operate in.<br />Note: TerrainType is a subtype of GeopoliticalLocationStateType as the terrain may change over time (e.g. muddy, frozen ground, deep snow, etc.).</td>
</tr>
<tr>
<td>ToNode</td>
<td>Type</td>
<td>A RoleInLogicalProcess where a LogicalFlow flows to a Node.</td>
</tr>
<tr>
<td>TrustLine</td>
<td>Type</td>
<td>A LogicalFlow that asserts that the trustingParty (either a Node or a KnownResource) trusts the trustedParty to a given level (indicated by the level attribute).<br />Note: No unit of measure is associated with the level - security architects must define their own scale of trust levels for a given architecture or set of architectures.</td>
</tr>
<tr>
<td>WeatherConditions</td>
<td>Type</td>
<td>An EnvironmentalFactor that defines the type of weather in which an Enterprise may operate.</td>
</tr>
<tr>
<td>GeopoliticalLocation</td>
<td>IndividualType</td>
<td>A Location and a GeoPoliticalArea.</td>
</tr>
<tr>
<td>Location</td>
<td>IndividualType</td>
<td>A location anywhere on the earth. The means of describing the location is a string (locationDescription). The information contained in that string is governed by the taxonomy reference - e.g. if the Location is a “GPS reference”, the string will contain the GPS coordinates.<br />Note: was called &quot;ActualLocation&quot; in M3 v1.2</td>
</tr>
<tr>
<td>PointLocation</td>
<td>IndividualType</td>
<td>A Location expressed as a point on a ReferenceEllipsoidOrGeoid.</td>
</tr>
<tr>
<td>capabilityForNode</td>
<td>TupleType</td>
<td>A bodyTypeSuperSubType that asserts that a Node exhibits or is required to exhibit a Capability.</td>
</tr>
<tr>
<td>environmentalContext</td>
<td>TupleType</td>
<td>A couple that relates a MeasureInContext to an EnvironmentalFactor in order to qualify the measure.</td>
</tr>
<tr>
<td>levelOfService</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation where a ServiceLevel is sets levels of service based on a ServiceSpecification.</td>
</tr>
<tr>
<td>locationNamedBy</td>
<td>TupleType</td>
<td>A namedBy that identifies a Location.</td>
</tr>
<tr>
<td>logicalSecurityPolicy</td>
<td>TupleType</td>
<td>A constraintOnType that sets the security policy for LogicalIndividualType.</td>
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
<td>nodeLocation</td>
<td>TupleType</td>
<td>A couple used to assert the Location at/in which a Node resides.<br />Note: given that OV-2 is a logical model, more often than not, the environment rather than the actual location should be specified - i.e. use NodeEnvironment.</td>
</tr>
<tr>
<td>qualifiedMeasure</td>
<td>TupleType</td>
<td>A superSubtype that relates a MeasureInContext to the measure it qualifies.</td>
</tr>
<tr>
<td>requiredMeasureOfPerformance</td>
<td>TupleType</td>
<td>A measureOfType that asserts a Node is required to achieve a level of performance specified by a Measure.</td>
</tr>
<tr>
<td>trustLevel</td>
<td>TupleType</td>
<td>A representedBy that uses an IntegerRepresentation to specify an arbitrary level of trust between the Nodes connected by a Trustline.</td>
</tr>
<tr>
<td>typeOfKnownResource</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation where a KnownResource is a subtype of a ResourceType.</td>
</tr>
<tr>
<td>upperBoundOfMeasureRange</td>
<td>TupleType</td>
<td>A superSubtype that asserts the MeasureInstance that is the upper bound (i.e. maximum measure) of a MeasureRange.</td>
</tr>
</tbody>
</table>

<p>Table ‑: L2 Element List</p>

# L3 – Node Interactions

{%include figure.html url="{{rasterimagepath}}image22.png" width="603" height="367" description="L3 Logical Diagram" %}

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
<td>ConsumerActivity</td>
<td>Type</td>
<td>An IndividualExchangeRoleType where an OperationalActivity is the consumer of a LogicalFlow.</td>
</tr>
<tr>
<td>DataModelTypeRepresentation</td>
<td>Type</td>
<td>A DataModelComponent that can be used to represent the type of something.</td>
</tr>
<tr>
<td>EnergyFlow</td>
<td>Type</td>
<td>A LogicalFlow where energy is transferred from one Node to another.</td>
</tr>
<tr>
<td>FlowBundle</td>
<td>Type</td>
<td>A TypicalWholePart where the whole is a FlowGroup and the part is a LogicalFlow.</td>
</tr>
<tr>
<td>FlowedElement</td>
<td>Type</td>
<td>A ModemIndividualType that can be flowed along a LogicalFlow.</td>
</tr>
<tr>
<td>FlowedElementRole</td>
<td>Type</td>
<td>An ExchangedItemRoleType where a FlowedElement is exchanged along a LogicalFlow.</td>
</tr>
<tr>
<td>FlowGroup</td>
<td>Type</td>
<td>A LogicalFlow that is composed of other LogicalFlows.</td>
</tr>
<tr>
<td>FrequencyRange</td>
<td>Type</td>
<td>A MeasureRange that specifies maximum and minimum frequencies, measured in Hertz as real numbers.</td>
</tr>
<tr>
<td>FromNode</td>
<td>Type</td>
<td>An RoleInLogicalProcess where a LogicalFlow flows from a Node.</td>
</tr>
<tr>
<td>HumanResourceType</td>
<td>Type</td>
<td>HumanResource. A PersonType, PostType, OrganisationType or OrganisationRoleType. [ABSTRACT] Note: was called &quot;OrganisationalResource&quot; in M3 v1.2. Note: was called &quot;OrganisationalResourceType&quot; in M3.</td>
</tr>
<tr>
<td>InformationElement</td>
<td>Type</td>
<td>An InformationInstanceType that flows between OperationalActivities and Nodes. The structure of an InformationElement may be defined using a LogicalDataModel.</td>
</tr>
<tr>
<td>InformationElementWholePart</td>
<td>Type</td>
<td>A TypicalWholePart where one InformationElement is a part of another.</td>
</tr>
<tr>
<td>InformationFlow</td>
<td>Type</td>
<td>A LogicalFlow where the FlowedElement is information.</td>
</tr>
<tr>
<td>InformationRole</td>
<td>Type</td>
<td>A FlowedElementRole where information is flowed.</td>
</tr>
<tr>
<td>LogicalExport</td>
<td>Type</td>
<td>A SendType where a LogicalFlow exports from a Node or OperationalActivity.<br />Note: this is the equivalent of OpActivityOutputPin in M3.</td>
</tr>
<tr>
<td>LogicalFlow</td>
<td>Type</td>
<td>An ExchangeType that flows between OperationalActivities and/or Nodes.</td>
</tr>
<tr>
<td>LogicalFlowExport</td>
<td>Type</td>
<td>A SendInExchangeType where a LogicalFlow exports from a Node or OperationalActivity.</td>
</tr>
<tr>
<td>LogicalFlowImport</td>
<td>Type</td>
<td>A ReceiveInExchangeType where a LogicalFlow imports to a Node or OperationalActivity.</td>
</tr>
<tr>
<td>LogicalImport</td>
<td>Type</td>
<td>A ReceiveType where a LogicalFlow imports to a Node or OperationalActivity<br />Note: this is the equivalent of OpActivityInputPin in M3.</td>
</tr>
<tr>
<td>Measure</td>
<td>Type</td>
<td>A Property whose members are Individuals that all share a common, measurable property, or whose properties lie within a MeasureRange.<br />Examples: 2kg, 4 weeks, 2km.</td>
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
<td>A ResourceType that is a type of NonHumanResource (i.e. an Artefact or NaturalResource) [ABSTRACT].</td>
</tr>
<tr>
<td>OperationalActivity</td>
<td>Type</td>
<td>A ProcessType that is a type of logical process, specified independently of how the process is carried out.<br />Note: an OperationalActivity may only be carried out by a logical Node.</td>
</tr>
<tr>
<td>OrganisationRoleType</td>
<td>Type</td>
<td><p>A type of role a human resource may carry out in an organisation. This is not used as a component of a ResourceType.<br />Note: was called &quot;RoleType&quot; in M3.</p></td>
</tr>
<tr>
<td>OrganisationType</td>
<td>Type</td>
<td><p>A ResponsibleHumanResourceType and a ConstructedHumanResourceType that is a type of Organisation. This is not used as a component of a ResourceType.<br />Examples: Government Department, Commercial Company, Accounting Department.</p></td>
</tr>
<tr>
<td>PersonType</td>
<td>Type</td>
<td>A ResponsibleHumanResourceType that is a type of person.</td>
</tr>
<tr>
<td>PostType</td>
<td>Type</td>
<td>A ConstructedHumanResourceType and ResponsibleHumanResourceType specifying a type of Post. This is not used as a component of a ResourceType. A type of point of contact or responsible person.<br />Note that this is the type of post - e.g. Desk Officer, Commander, etc.</td>
</tr>
<tr>
<td>ProducerActivity</td>
<td>Type</td>
<td>An IndividualExchangeRoleType where the involved ProcessType is an OperationalActivity that is the producer of a LogicalFlow.</td>
</tr>
<tr>
<td>Property</td>
<td>Type</td>
<td>An IndividualType whose members all exhibit a common trait or feature. Often the Individuals are states having a property (the state of being 18 degrees centigrade), where this property can be a CategoricalProperty (qv.) or a DispositionalProperty (qv.).<br />Examples: Ability to fly at Mach 2, 10kg.</td>
</tr>
<tr>
<td>ResourceFlow</td>
<td>Type</td>
<td>A LogicalFlow where the flowed element is a ResourceType.</td>
</tr>
<tr>
<td>ResourceFlowRole</td>
<td>Type</td>
<td>A FlowedElementRole where a ResourceType is flowed.</td>
</tr>
<tr>
<td>ResourceType</td>
<td>Type</td>
<td>A PhysicalArchitectureIndividualType that is a type of IndividualResource. This is not used as a component of a ResourceType, but may use components. [ABSTRACT].</td>
</tr>
<tr>
<td>RoleInFlow</td>
<td>Type</td>
<td>An ExchangedItemRoleInExchangeType where the role in exchange is a LogicalFlow.</td>
</tr>
<tr>
<td>RoleInInformationFlow</td>
<td>Type</td>
<td>A RoleInFlow where Information is being flowed.</td>
</tr>
<tr>
<td>RoleInResourceFlow</td>
<td>Type</td>
<td>A RoleInFlow where a ResourceType is being flowed.</td>
</tr>
<tr>
<td>RoleOfFlowedElement</td>
<td>Type</td>
<td>An IndividualRoleAsExchangedItemType where a FlowedElement is exchanged.</td>
</tr>
<tr>
<td>RoleOfInformation</td>
<td>Type</td>
<td>A RoleOfFlowedElement where the flowed element is Information.</td>
</tr>
<tr>
<td>RoleOfResourceInFlow</td>
<td>Type</td>
<td>A RoleOfFlowedElement where the flowed element is ResourceType</td>
</tr>
<tr>
<td>infoElementRepresentation</td>
<td>TupleType</td>
<td>A representedByDataType that asserts an InformationElement is represented by a DataModelTypeRepresentation.</td>
</tr>
<tr>
<td>logicalFlowMeasure</td>
<td>TupleType</td>
<td>A logicalFlowProperty and a measureOfType - i.e. an assignment of a Measure to a LogicalFlow.</td>
</tr>
<tr>
<td>logicalFlowProperty</td>
<td>TupleType</td>
<td>A propertyOfType where the Property applies to a LogicalFlow.</td>
</tr>
</tbody>
</table>

<p>Table ‑: L3 Element List</p>



# L4 – Logical Activities



{%include figure.html url="{{rasterimagepath}}image23.png" width="604" height="620"  description="L4 Logical Diagram" %}


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
<td>ActivityComposition</td>
<td>Type</td>
<td>A TypicalWholePart that relates a parent (whole) OperationalActivity to its child (part).</td>
</tr>
<tr>
<td>ActivityGroup</td>
<td>Type</td>
<td>An OperationalActivity that is entirely composed of other OperationalActivities</td>
</tr>
<tr>
<td>ActivityGrouping</td>
<td>Type</td>
<td>An ActivityComposition where the parent Activity is an ActivityGroup.</td>
</tr>
<tr>
<td>AffectedNode</td>
<td>Type</td>
<td>An IndividualRoleType where the role extent is an AffectedRole and the whole is a Node.</td>
</tr>
<tr>
<td>AffectedRole</td>
<td>Type</td>
<td>A RoleExtentType that corresponds to the part of a Node affected by an Activity that acts upon it.<br />Note: by &quot;part&quot;, this includes temporal parts, so all of the Node may be affected for a period of time. This was previously &lt;&lt;ActsUpon&gt;&gt; in M3.</td>
</tr>
<tr>
<td>CBRNEnvironment</td>
<td>Type</td>
<td>An EnvironmentalFactor that defines the type of chemical, biological, radiological and nuclear environment in which an Enterprise may operate.</td>
</tr>
<tr>
<td>ConsumerActivity</td>
<td>Type</td>
<td>An IndividualExchangeRoleType where an OperationalActivity is the consumer of a LogicalFlow.</td>
</tr>
<tr>
<td>ConsumerRoleInService</td>
<td>Type</td>
<td>An AgentParticipationType that relates a ServiceSpecification to its role in supporting an OperationalActivity.</td>
</tr>
<tr>
<td>ControlInput</td>
<td>Type</td>
<td>A LogicalImport where the imported LogicalFlow controls the OperationalActivity.<br />Note: this exists to provide compatibility with IDEF0.</td>
</tr>
<tr>
<td>EffectActivity</td>
<td>Type</td>
<td>An ProcessWholeRoleExtentPartType where the ProcessType is an OperationalActivity.</td>
</tr>
<tr>
<td>EnergyFlow</td>
<td>Type</td>
<td>A LogicalFlow where energy is transferred from one Node to another.</td>
</tr>
<tr>
<td>EnvironmentalFactor</td>
<td>Type</td>
<td>A GeopoliticalLocationStateType that defines some aspect of the environment in which an Enterprise may operate.</td>
</tr>
<tr>
<td>InformationFlow</td>
<td>Type</td>
<td>A LogicalFlow where the FlowedElement is information.</td>
</tr>
<tr>
<td>LightConditions</td>
<td>Type</td>
<td>An EnvironmentmentalFactor that defines the types of light (e.g. broad daylight, dusk, moonlit, etc.) in which an Enterprise may operate.</td>
</tr>
<tr>
<td>LogicalExport</td>
<td>Type</td>
<td>A SendType where a LogicalFlow exports from a Node or OperationalActivity.<br />Note: this is the equivalent of OpActivityOutputPin in M3</td>
</tr>
<tr>
<td>LogicalFlow</td>
<td>Type</td>
<td>An ExchangeType that flows between OperationalActivities and/or Nodes.</td>
</tr>
<tr>
<td>LogicalFlowExport</td>
<td>Type</td>
<td>A SendInExchangeType where a LogicalFlow exports from a Node or OperationalActivity.</td>
</tr>
<tr>
<td>LogicalFlowImport</td>
<td>Type</td>
<td>A ReceiveInExchangeType where a LogicalFlow imports to a Node or OperationalActivity.</td>
</tr>
<tr>
<td>LogicalImport</td>
<td>Type</td>
<td>A ReceiveType where a LogicalFlow imports to a Node or OperationalActivity<br />Note: this is the equivalent of OpActivityInputPin in M3.</td>
</tr>
<tr>
<td>LogicalServiceConsumerRole</td>
<td>Type</td>
<td>A ParticipationExtentType which is the extent of an OperationalActivity's participation in as the consumer of a ServiceSpecification.</td>
</tr>
<tr>
<td>Measure</td>
<td>Type</td>
<td>A Property whose members are Individuals that all share a common, measurable property, or whose properties lie within a MeasureRange.<br />Examples: 2kg, 4 weeks, 2km.</td>
</tr>
<tr>
<td>MeasureCategory</td>
<td>Type</td>
<td>A MeasureType whose members are recognised types of MeasureInstance.<br />Examples: Mass (included in IDEAS), Length (included in IDEAS), Velocity, Hardness.</td>
</tr>
<tr>
<td>MeasureInContext</td>
<td>Type</td>
<td>A ModemIndividualType that brings together EnvironmentalFactors with a Measure in order to qualify the measure.<br />Examples: 40mph in desert, 1km range in cloudy conditions</td>
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
<td>MechanismInput</td>
<td>Type</td>
<td>A LogicalImport where the imported LogicalFlow provides a mechanism for conducting the OperationalActivity.<br />Note: this exists to provide compatibility with IDEF0</td>
</tr>
<tr>
<td>Node</td>
<td>Type</td>
<td>A NodeState that is used in context of a NodeParent.</td>
</tr>
<tr>
<td>NodeRole</td>
<td>Type</td>
<td>A RoleInLogicalProcess which is the extent of a Node's participation in an OperationalActivity.<br />Note: An OperationalActivity can only be conducted by one Node.</td>
</tr>
<tr>
<td>OperationalActivity</td>
<td>Type</td>
<td>A ProcessType that is a type of logical process, specified independently of how the process is carried out.<br />Note: an OperationalActivity may only be carried out by a logical Node.</td>
</tr>
<tr>
<td>ProducerActivity</td>
<td>Type</td>
<td>An IndividualExchangeRoleType where the involved ProcessType is an OperationalActivity that is the producer of a LogicalFlow.</td>
</tr>
<tr>
<td>ResourceFlow</td>
<td>Type</td>
<td>A LogicalFlow where the flowed element is a ResourceType.</td>
</tr>
<tr>
<td>ServiceConsumerNodeRole</td>
<td>Type</td>
<td>A ProcessWholeRoleExtentType that relates an OperationalActivity to the role of a ServiceSpecification that supports it.</td>
</tr>
<tr>
<td>ServiceLevel</td>
<td>Type</td>
<td>A ServiceDeliveryType based on a ServiceSpecification that sets a level of service using of Measures that correspond to ServiceAttributes.</td>
</tr>
<tr>
<td>ServiceSpecification</td>
<td>Type</td>
<td>A ServiceDeliveryType that is the specification of a ServiceDelivery<br />Note: was called &quot;Service&quot; in M3.</td>
</tr>
<tr>
<td>StandardActivity</td>
<td>Type</td>
<td>A ProcessType that is a standard procedure (e.g. doctrinal tasks).<br />Note: This is equivalent to what some defence organisations call JETLs.<br />Note: was called &quot;StandardOperationalActivity&quot; in M3.</td>
</tr>
<tr>
<td>TerrainType</td>
<td>Type</td>
<td>An EnvironmentalFactor that defines the type of ground conditions that an Enterprise may operate in.<br />Note: TerrainType is a subtype of GeopoliticalLocationStateType as the terrain may change over time (e.g. muddy, frozen ground, deep snow, etc.).</td>
</tr>
<tr>
<td>WeatherConditions</td>
<td>Type</td>
<td>An EnvironmentalFactor that defines the type of weather in which an Enterprise may operate.</td>
</tr>
<tr>
<td>EnduringTask</td>
<td>IndividualType</td>
<td>An Undertaking recognised by an enterprise as being essential to achieving its goals - i.e. a strategic specification of what the enterprise does.</td>
</tr>
<tr>
<td>activityBasedOn</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation that asserts that an OperationalActivity is based on a StandardActivity - e.g. a specialist usage of doctrine.</td>
</tr>
<tr>
<td>environmentalContext</td>
<td>TupleType</td>
<td>A couple that relates a MeasureInContext to an EnvironmentalFactor in order to qualify the measure.</td>
</tr>
<tr>
<td>levelOfService</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation where a ServiceLevel is sets levels of service based on a ServiceSpecification.</td>
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
<td>qualifiedMeasure</td>
<td>TupleType</td>
<td>A superSubtype that relates a MeasureInContext to the measure it qualifies.</td>
</tr>
<tr>
<td>serviceLevelMeasure</td>
<td>TupleType</td>
<td>A measureOfType that specifies a ServiceLevel.</td>
</tr>
<tr>
<td>templateForTask</td>
<td>TupleType</td>
<td>A modemIndividualTypeInstance that relates an EnduringTask to an EnduringTaskTemplate that specifies it.</td>
</tr>
<tr>
<td>upperBoundOfMeasureRange</td>
<td>TupleType</td>
<td>A superSubtype that asserts the MeasureInstance that is the upper bound (i.e. maximum measure) of a MeasureRange.</td>
</tr>
</tbody>
</table>


<p>Table ‑: L4 Element List</p>


# L5 – Logical States

{%include figure.html url="{{rasterimagepath}}image24.png" width="604" height="379" description="L5 Logical Diagram" %}

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
<td>Node</td>
<td>Type</td>
<td>A NodeState that is used in context of a NodeParent.</td>
</tr>
<tr>
<td>NodeState</td>
<td>Type</td>
<td>A LogicalIndividualType that is a type of state that a Node can be in. This includes the limit case of the whole-life state type - i.e. the Node itself..</td>
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
<td>stateMachineForNode</td>
<td>TupleType</td>
<td>An appliedStateMachine that relates a Node to its state machine.</td>
</tr>
<tr>
<td>stateTransitionInRegion</td>
<td>TupleType</td>
<td>A regionTypeInstance that asserts a StateTransition features in a StateMachineRegion.</td>
</tr>
</tbody>
</table>


<p>Table ‑: L5 Element List</p>


# L6 – Logical Sequence

{%include figure.html url="{{rasterimagepath}}image25.png" width="604" height="508" description="L6 Logical Diagram" %}

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
<td>ActivityOnLifeline</td>
<td>Type</td>
<td>A TypicalWholePart where a SequencedActivity is part of a NodeLifeline.<br />Note: a given SequencedActivity may appear on one and only one NodeLifeline</td>
</tr>
<tr>
<td>Delay</td>
<td>Type</td>
<td>A TriggerItem that is a pause between Processes, Events, etc.</td>
</tr>
<tr>
<td>EventBoundedLogicalProcess</td>
<td>Type</td>
<td>A LogicalProcess that can have LogicalEvents marking its start and end points.</td>
</tr>
<tr>
<td>FromNode</td>
<td>Type</td>
<td>An RoleInLogicalProcess where a LogicalFlow flows from a Node.</td>
</tr>
<tr>
<td>ItemInLogicalScenario</td>
<td>Type</td>
<td>An ItemInScenario where the item (part) is a LogicalScenarioItem and the scenario (whole) is a LogicalScenario.</td>
</tr>
<tr>
<td>LifelineForNode</td>
<td>Type</td>
<td>A StateOfNode that asserts that a NodeLifeLine is a typical temporal part of a Node.</td>
</tr>
<tr>
<td>LogicalDelay</td>
<td>Type</td>
<td>A LogicalSequencedItem that is part of a LogicalScenario that has a specified temporal extent, but an unspecified spatial extent.</td>
</tr>
<tr>
<td>LogicalEndEvent</td>
<td>Type</td>
<td>An EndBorderType that relates a EventBoundedLogicalProcess to the LogicalEvent that marks its end.<br />Note: there may be no more than one LogicalEndEvent for a given EventBoundedLogicalProcess.</td>
</tr>
<tr>
<td>LogicalEvent</td>
<td>Type</td>
<td>An Event that marks the beginning or end of an EventBoundedLogicalProcess.</td>
</tr>
<tr>
<td>LogicalFlow</td>
<td>Type</td>
<td>An ExchangeType that flows between OperationalActivities and/or Nodes.</td>
</tr>
<tr>
<td>LogicalScenario</td>
<td>Type</td>
<td>A Scenario that does not specify particular ResourceTypes - i.e. one that consists of Nodes and LogicalProcesses.</td>
</tr>
<tr>
<td>LogicalScenarioPart</td>
<td>Type</td>
<td>A LogicalIndividualType that is part of a LogicalScenario - note this can include other LogicalScenarios.</td>
</tr>
<tr>
<td>LogicallySequencedItem</td>
<td>Type</td>
<td>A LogicalScenarioPart which may be temporally ordered using LogicalSequencing.</td>
</tr>
<tr>
<td>LogicalSequencing</td>
<td>Type</td>
<td>An ImmediateBeforeAfterType that asserts one LogicallySequencedItem occurs immediately after the other.</td>
</tr>
<tr>
<td>LogicalStartEvent</td>
<td>Type</td>
<td>A StartBorderType that relates an EventBoundedLogicalProcess to the LogicalEvent that marks its start.<br />Note: there may be no more than one LogicalStartEvent for a given EventBoundedLogicalProcess.</td>
</tr>
<tr>
<td>Node</td>
<td>Type</td>
<td>A NodeState that is used in context of a NodeParent.</td>
</tr>
<tr>
<td>NodeLifeline</td>
<td>Type</td>
<td>A NodeState whose extent is defined by a LogicalScenario.</td>
</tr>
<tr>
<td>OperationalActivity</td>
<td>Type</td>
<td>A ProcessType that is a type of logical process, specified independently of how the process is carried out.<br />Note: an OperationalActivity may only be carried out by a logical Node.</td>
</tr>
<tr>
<td>SequencedActivity</td>
<td>Type</td>
<td>An EventBoundedLogicalProcess that is the typical useage of an OperationalActivity in a NodeLifeLine.</td>
</tr>
<tr>
<td>SequencedLogicalFlow</td>
<td>Type</td>
<td>A LogicalScenarioPart that is the typical useage of a LogicalFlow between two NodeLifeLines.</td>
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
<td>ToNode</td>
<td>Type</td>
<td>A RoleInLogicalProcess where a LogicalFlow flows to a Node.</td>
</tr>
<tr>
<td>activityInSequence</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation that relates an OperationaActivity to its usage (as a SequencedActivity) on a NodeLifeLine.<br />Note: A SequencedActivity is based on only one OperationaActivity.</td>
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
<td>flowInScenario</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation that relates a LogicalFlow to its usage (as a SequencedLogicalFlow) in a LogicalScenario.<br />Note: A SequencedLogicalFlow is based on only one LogicalFlow.</td>
</tr>
</tbody>
</table>

<p>Table ‑: L6 Element List</p>



<h3 id="l7-logical-data-model">4.4.7 L7 – Logical Data Model</h3>
<p><img src="images/media/image26.png" width="604" height="539" /><br /><span id="_Toc393217517" class="anchor"></span>Figure ‑: L7 Logical Diagram</p>


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
<td>InformationElement</td>
<td>Type</td>
<td>An InformationInstanceType that flows between OperationalActivities and Nodes. The structure of an InformationElement may be defined using a LogicalDataModel.</td>
</tr>
<tr>
<td>InformationElementWholePart</td>
<td>Type</td>
<td>A TypicalWholePart where one InformationElement is a part of another.</td>
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
<td>LogicalDataModel</td>
<td>Type</td>
<td>A DataModel that is a specification of business information requirements as a formal data structure, where relationships and classes (entities) are used to specify the logic which underpins the information.</td>
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
<td>SimpleDataType</td>
<td>Type</td>
<td>A DataModelTypeRepresentation that is used to specify the type of a literal (e.g. text, integer, floating point number, etc.).</td>
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
<td>dataElementRepresentation</td>
<td>TupleType</td>
<td>A representedByDataType that asserts an DataElement is represented by a DataModelTypeRepresentation.</td>
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
<td>infoElementRepresentation</td>
<td>TupleType</td>
<td>A representedByDataType that asserts an InformationElement is represented by a DataModelTypeRepresentation.</td>
</tr>
<tr>
<td>supportedMessageFormat</td>
<td>TupleType</td>
<td>A couple that relates an Interface to a MessageSpecification that it can support.</td>
</tr>
</tbody>
</table>

<p><span id="_Toc393217567" class="anchor"></span>Table ‑: L7 Element List</p>


<h3 id="l8-logical-constraints">4.4.8 L8 – Logical Constraints</h3>
<p>To be added<br /><span id="_Toc393217518" class="anchor"></span>Figure ‑: L8 Logical Diagram<br />To be added<br /><span id="_Toc393217568" class="anchor"></span>Table ‑: L8 Element List</p>
<h3 id="lr-lines-of-development">4.4.9 Lr – Lines of Development</h3>
<p><img src="images/media/image27.png" width="603" height="478" /><br /><span id="_Toc393217519" class="anchor"></span>Figure ‑: Lr Logical Diagram</p>


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
<td>DefinedIndicatorForThreadType</td>
<td>Type</td>
<td>A StatusOfThreadType that specifies a StatusIndicator may be used to classify ProjectThreads of a particular ProjectThreadType.</td>
</tr>
<tr>
<td>HumanAndNonHumanConfigurationType</td>
<td>Type</td>
<td>A ResourceType that has both Human and Non-Human components.</td>
</tr>
<tr>
<td>ProjectThreads</td>
<td>Type</td>
<td>A ThreadInProjectType that relates a ProjectType to its ProjectThreadTypes.</td>
</tr>
<tr>
<td>ProjectThreadType</td>
<td>Type</td>
<td>A ProjectThreadPowertype that is used to classify ProjectThreads.</td>
</tr>
<tr>
<td>ProjectType</td>
<td>Type</td>
<td>A ProjectType that is used to classify Projects.</td>
</tr>
<tr>
<td>ResourceInPackage</td>
<td>Type</td>
<td>A ResourceUsage that specifies that a ResourceType is part of a DeliveryPackageSpecification.</td>
</tr>
<tr>
<td>ResourcePackageSpecification</td>
<td>Type</td>
<td>A ResourcePackageType that specifies the types of Resource (i.e. ResourceTypes) that make up a ResourcePackage.</td>
</tr>
<tr>
<td>ResourceType</td>
<td>Type</td>
<td>A PhysicalArchitectureIndividualType that is a type of IndividualResource. This is not used as a component of a ResourceType, but may use components. [ABSTRACT]</td>
</tr>
<tr>
<td>StatusIndicator</td>
<td>Type</td>
<td>A ThreadStatusType that classifies a ThreadStatusAtMilestone to indicate its status.</td>
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
<td>An IndividualResourceState which marks the point at which a ResourcePackage ceases to be in service.<br />Note: the components of the package may go on in service in some other configuration, but the package itself is retired.</td>
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
<td>ResourcePackage</td>
<td>IndividualType</td>
<td>A HumanAndNonHumanConfiguration that is a collection of IndividualResources for a purpose.<br />Example: All the fully configured aircraft delivered in an acquisition programme.<br />Example: A force element package put together for a particular operation.<br />Example: A tranche of new assets delivered into an enterprise.</td>
</tr>
<tr>
<td>ResourcePackageState</td>
<td>IndividualType</td>
<td>A temporal part of a ResourcePackage.</td>
</tr>
<tr>
<td>ThreadStatusAtMilestone</td>
<td>IndividualType</td>
<td>A ProjectThreadState that is part of a ProjectMilestone.</td>
</tr>
<tr>
<td>WholeLifeEnterprise</td>
<td>IndividualType</td>
<td>An EnterprisePhase that represents the whole existance of an enterprise.</td>
</tr>
<tr>
<td>capabilityRealisation</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation that relates a CapabilityConfiguration to a Capability.</td>
</tr>
<tr>
<td>indicationOfStatus</td>
<td>TupleType</td>
<td>A modemIndividualTypeInstance where a ThreadStatusAtMilestone is classified by a StatusIndicator.</td>
</tr>
<tr>
<td>inService</td>
<td>TupleType</td>
<td>A startBorder that indicates that an PackageInService marks the introduction into service of a ResourcePackage.</td>
</tr>
<tr>
<td>milestoneBegins</td>
<td>TupleType</td>
<td>A startBoundary that asserts a ProjectMilestone marks the beginning of a Project or ProjectPhase.</td>
</tr>
<tr>
<td>milestoneDependency</td>
<td>TupleType</td>
<td>A beforeAfter that asserts one ProjectMilestone shall occur before the other.<br />Note: This is intended to related milestones from different projects where progress in one project depends on the other.</td>
</tr>
<tr>
<td>milestoneEnds</td>
<td>TupleType</td>
<td>An endBoundary that asserts a ProjectMilestone marks the end of a Project or ProjectPhase.</td>
</tr>
<tr>
<td>outOfService</td>
<td>TupleType</td>
<td>An endBorder that indicates that an PackageOutOfService marks the termination of service of a ResourcePackage.</td>
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
<td>projectSequence</td>
<td>TupleType</td>
<td>A beforeAfter that asserts one Project cannot start until another has finished.</td>
</tr>
<tr>
<td>projectTypeInstance</td>
<td>TupleType</td>
<td>A modemIndividualTypeInstance that asserts a Project is an instance of a ProjectType.</td>
</tr>
<tr>
<td>projectWholeAndPart</td>
<td>TupleType</td>
<td>A projectWholePart where both the whole and part are Projects.</td>
</tr>
<tr>
<td>projectWholePhase</td>
<td>TupleType</td>
<td>A projectPhaseTemporalPart where the whole is a Project.</td>
</tr>
<tr>
<td>resourceStateInMilestone</td>
<td>TupleType</td>
<td>A modemWholePart that asserts a ResourcePackageState occurs within a ProjectMilestone.</td>
</tr>
<tr>
<td>statusAtMilestone</td>
<td>TupleType</td>
<td>A modemWholePart which relates a ThreadStatusAtMilestone to the ProjectMilestone it is part of.</td>
</tr>
</tbody>
</table>


<p><span id="_Toc393217569" class="anchor"></span>Table ‑: Lr Element List</p>
