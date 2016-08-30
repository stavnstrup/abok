---
title: Service Specification Layer
---



# C1-S1 – Capability to Service Mapping


{%include figure.html url="{{rasterimagepath}}image11.png" width="604" height="264" description="C1-S1 Logical Diagram" %}


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
<td>CapabilityOfService</td>
<td>Type</td>
<td>A TypicalWholePart that relates a Service to the specification of its underlying capability. Note: in MODAF 1.2 and M3 there was &quot;ServiceAimsToAchieve&quot; which showed how services were put together to achieve a capability. This was considered redundant, as it can (and should) be shown in OV-2 by tracing a Node to a capability and the services that support its OperationActivities.</td>
</tr>
<tr>
<td>ServiceSpecification</td>
<td>Type</td>
<td>A ServiceDeliveryType that is the specification of a ServiceDelivery. Note: was called &quot;Service&quot; in M3.</td>
</tr>
</tbody>
</table>

<p>Table ‑: C1-S1 Element List</p>


# S1 – Service Taxonomy


{%include figure.html url="{{rasterimagepath}}image12.png" width="605" height="776" description=" S1 Logical Diagram" %}

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
<td>AttributeOfService</td>
<td>Type</td>
<td>A typeInstance that relates a ServiceSpecification to a ServiceAttribute relevent to measuring service performance.</td>
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
<td>TerrainType</td>
<td>Type</td>
<td>An EnvironmentalFactor that defines the type of ground conditions that an Enterprise may operate in.<br />Note: TerrainType is a subtype of GeopoliticalLocationStateType as the terrain may change over time (e.g. muddy, frozen ground, deep snow, etc.)</td>
</tr>
<tr>
<td>ServiceSpecification</td>
<td>Type</td>
<td>A ServiceDeliveryType that is the specification of a ServiceDelivery.</td>
</tr>
<tr>
<td>WeatherConditions</td>
<td>Type</td>
<td>An EnvironmentalFactor that defines the type of weather in which an Enterprise may operate</td>
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
<td>measureTypeInstance</td>
<td>TupleType</td>
<td>A typeInstance that asserts a Measure is an instance of a MeasureCategory. Examples: 2kg is a mass, 40m/s is a velocity.</td>
</tr>
<tr>
<td>qualifiedMeasure</td>
<td>TupleType</td>
<td>A superSubtype that relates a MeasureInContext to the measure it qualifies</td>
</tr>
<tr>
<td>serviceGeneralisation</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation where one ServiceSpecification is a specialisation of another.</td>
</tr>
<tr>
<td>upperBoundOfMeasureRange</td>
<td>TupleType</td>
<td>A superSubtype that asserts the MeasureInstance that is the upper bound (i.e. maximum measure) of a MeasureRange.</td>
</tr>
</tbody>
</table>

<p>Table ‑: S1 Element List</p>


# S2 – Not Used


# S3 – Service Interfaces


{%include figure.html url="{{rasterimagepath}}image13.png" width="604" height="325" description="S3 Logical Diagram" %}


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
<td>AsynchronousOperation</td>
<td>Type</td>
<td>An OperationSpecification where the caller and called do not wait for each other to complete the communication.</td>
</tr>
<tr>
<td>DataElement</td>
<td>Type</td>
<td>A SymbolOrSymbolStringType that represents interactions between resource elements.</td>
</tr>
<tr>
<td>Interface</td>
<td>Type</td>
<td>A ModemIndividualType that is an interface either provided or required by another ModemIndividualType.</td>
</tr>
<tr>
<td>InterfaceOperation</td>
<td>Type</td>
<td>A TypicalWholePart that realtes an OperationSpecification to its InterfaceSpecification.</td>
</tr>
<tr>
<td>InterfaceSpecification</td>
<td>Type</td>
<td>A ModemIndividualType that is a part of another ModemIndividualType that defines how it communicates</td>
</tr>
<tr>
<td>MessageSpecification</td>
<td>Type</td>
<td>A DataElement that specifies the content of a message.</td>
</tr>
<tr>
<td>OperationInputParameter</td>
<td>Type</td>
<td>A TypicalWholePart where an OperationParameter is passed into a OperationSpecification.</td>
</tr>
<tr>
<td>OperationParameter</td>
<td>Type</td>
<td>A ModemIndividualType that is a part of an OperationSpecification. OperationParameters are passed in and out of OperationSpecifications.</td>
</tr>
<tr>
<td>OperationReadWriteParameter</td>
<td>Type</td>
<td>A TypicalWholePart where an OperationParameter is passed into an OperationSpecification that can then be modified and the result read after processing.</td>
</tr>
<tr>
<td>OperationReturnParameter</td>
<td>Type</td>
<td>A TypicalWholePart where an OperationParameter is passed out of an OperationSpecification.</td>
</tr>
<tr>
<td>OperationSpecification</td>
<td>Type</td>
<td>A ModemIndividualType that is an invokable part of an InterfaceSpecification. [ABSTRACT]</td>
</tr>
<tr>
<td>ProvidedInterface</td>
<td>Type</td>
<td>An Interface describing what a ServiceSpecification or a ResourceType is capable of providing when invoked by an external element.</td>
</tr>
<tr>
<td>RequiredInterface</td>
<td>Type</td>
<td>An Interface describing what a ServiceSpecification or a ResourceType requires from an external element.</td>
</tr>
<tr>
<td>ServiceInterface</td>
<td>Type</td>
<td>A TypicalWholePart that relates a ServiceSpecification to an Interface that it requires or provides.</td>
</tr>
<tr>
<td>ServiceSpecification</td>
<td>Type</td>
<td>A ServiceDeliveryType that is the specification of a ServiceDelivery.<br />Note: was called &quot;Service&quot; in M3.</td>
</tr>
<tr>
<td>SynchronousOperation</td>
<td>Type</td>
<td>An OperationSpecification where the caller and called wait for each other to complete the communication.</td>
</tr>
<tr>
<td>specForInterface</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation that relates an Interface to the InterfaceSpecification that specifies it</td>
</tr>
<tr>
<td>supportedMessageFormat</td>
<td>TupleType</td>
<td>A couple that relates an Interface to a MessageSpecification that it can support.</td>
</tr>
</tbody>
</table>


<p>S3 Element List</p>


# S4 – Service Functions


{%include figure.html url="{{rasterimagepath}}image14.png" width="604" height="225" description="S4 Logical Diagram" %}

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
<td>ConsumerServiceFunction</td>
<td>Type</td>
<td>An IndividualExchangeRoleType where the role is a ServiceFlowImportRole and the consumer is a ServiceFunction</td>
</tr>
<tr>
<td>ProducerServiceFunction</td>
<td>Type</td>
<td>An IndividualExchangeRoleType where the role is a ServiceFlowExportRole and the producer is a ServiceFunction</td>
</tr>
<tr>
<td>ServiceExport</td>
<td>Type</td>
<td>A SendInExchangeType where the sender is a ServiceSpecification or ServiceFunction</td>
</tr>
<tr>
<td>ServiceFlow</td>
<td>Type</td>
<td>An ExchangeType where two ServiceSpecifications interact.</td>
</tr>
<tr>
<td>ServiceFlowExportRole</td>
<td>Type</td>
<td>A SendType where the sender is a ServiceSpecification or ServiceFunction.</td>
</tr>
<tr>
<td>ServiceFlowImportRole</td>
<td>Type</td>
<td>A RecieveType where the receiver is a ServiceSpecification or ServiceFunction</td>
</tr>
<tr>
<td>ServiceFunction</td>
<td>Type</td>
<td>A ServiceProcess carried out by a ServiceSpecification.</td>
</tr>
<tr>
<td>ServiceFunctionComposition</td>
<td>Type</td>
<td>A TypicalWholePart that relates a parent (whole) ServiceFunction to its child (part) ServiceFunction<br />Note: was called &quot;ActivityComposition&quot; in M3</td>
</tr>
<tr>
<td>ServiceImport</td>
<td>Type</td>
<td>A ReceiveInExchangeType where the receiver is a ServiceSpecification or ServiceFunction.</td>
</tr>
<tr>
<td>ServiceRole</td>
<td>Type</td>
<td>A ProcessPartOfBodyType that asserts that a ServiceFunction is part of a ServiceSpecification.</td>
</tr>
<tr>
<td>ServiceSpecification</td>
<td>Type</td>
<td>A ServiceDeliveryType that is the specification of a ServiceDelivery.<br />Note: was called &quot;Service&quot; in M3.</td>
</tr>
</tbody>
</table>

<p>Table ‑: S4 Element List</p>


# S5 – Service States

{%include figure.html url="{{rasterimagepath}}image15.png" width="605" height="381" description="S5 Logical Diagram" %}

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
<td>ServiceSpecification</td>
<td>Type</td>
<td>A ServiceDeliveryType that is the specification of a ServiceDelivery.<br />Note: was called &quot;Service&quot; in M3.</td>
</tr>
<tr>
<td>ServiceSpecificationState</td>
<td>Type</td>
<td>A ServiceDeliveryStateType that is a type of temporal state typical of a ServiceSpecification.</td>
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
<td>stateMachineForServiceSpecification</td>
<td>TupleType</td>
<td>An appliedStateMachine that relates a ServiceSpecification to its state machine.</td>
</tr>
<tr>
<td>stateTransitionInRegion</td>
<td>TupleType</td>
<td>A regionTypeInstance that asserts a StateTransition features in a StateMachineRegion</td>
</tr>
</tbody>
</table>


<p>Table ‑: S5 Element List</p>


# S6 – Service Interactions

{%include figure.html url="{{rasterimagepath}}image16.png" width="604" height="473"  description="S6 Logical Diagram" %}

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
<td>AsynchronousOperation</td>
<td>Type</td>
<td>An OperationSpecification where the caller and called do not wait for each other to complete the communication.</td>
</tr>
<tr>
<td>Delay</td>
<td>Type</td>
<td>A TriggerItem that is a pause between Processes, Events, etc.</td>
</tr>
<tr>
<td>EventBoundedServiceProcess</td>
<td>Type</td>
<td>A ServiceProcess that has ServiceEvents marking its beginning and end.</td>
</tr>
<tr>
<td>ItemInServiceScenario</td>
<td>Type</td>
<td>An ItemInScenario where the Scenario is a ServiceScenario.</td>
</tr>
<tr>
<td>LifelineForService</td>
<td>Type</td>
<td>A TypicalTemporalWholePart that asserts a ServiceLifeLine is a typical temporal part of a ServiceSpecification.</td>
</tr>
<tr>
<td>OperationSpecification</td>
<td>Type</td>
<td>A ModemIndividualType that is an invokable part of an InterfaceSpecification [ABSTRACT].</td>
</tr>
<tr>
<td>SequencedOperation</td>
<td>Type</td>
<td>A ServiceScenarioPart that is the typical occurance of an OperationSpecification.</td>
</tr>
<tr>
<td>SequencedServiceFunction</td>
<td>Type</td>
<td>An EventBoundedServiceProcess whose instances are special cases of ServiceFunctions that take part in ServiceScenarios.</td>
</tr>
<tr>
<td>ServiceConsumer</td>
<td>Type</td>
<td>A Node that interacts with one or more services.</td>
</tr>
<tr>
<td>ServiceDelay</td>
<td>Type</td>
<td>A ServiceSequencedItem that has a specified temporal extent, but an unspecified spatial extent..</td>
</tr>
<tr>
<td>ServiceEndEvent</td>
<td>Type</td>
<td>An EndBorderType that relates a EventBoundedServiceProcess to the ServiceEvent that marks its end<br />Note: there may be no more than one ServiceEndEvent for a given EventBoundedServiceProcess</td>
</tr>
<tr>
<td>ServiceEvent</td>
<td>Type</td>
<td>An Event that marks the beginning or end of a EventBoundedServiceProcess.</td>
</tr>
<tr>
<td>ServiceFunction</td>
<td>Type</td>
<td>A ServiceProcess carried out by a ServiceSpecification.</td>
</tr>
<tr>
<td>ServiceLifeline</td>
<td>Type</td>
<td>A ServiceSpecificationState whose extent is defined by a ServiceScenario.</td>
</tr>
<tr>
<td>ServiceOrConsumer</td>
<td>Type</td>
<td>A ServiceScenarioPart that is either a ServiceLifeline or a ServiceConsumer. [ABSTRACT]</td>
</tr>
<tr>
<td>ServiceScenario</td>
<td>Type</td>
<td>A Scenario that describes the order of interactions with a ServiceSpecification.</td>
</tr>
<tr>
<td>ServiceScenarioPart</td>
<td>Type</td>
<td>A ModemIndividualType that features in (i.e. is part of) a ServiceScenario</td>
</tr>
<tr>
<td>ServiceSequencedItem</td>
<td>Type</td>
<td>A ServiceScenarioPart that can be sequenced by ServiceSequencing.</td>
</tr>
<tr>
<td>ServiceSpecification</td>
<td>Type</td>
<td>A ServiceDeliveryType that is the specification of a ServiceDelivery.<br />Note: was called &quot;Service&quot; in M3.</td>
</tr>
<tr>
<td>ServiceStartEvent</td>
<td>Type</td>
<td>A StartBorderType that relates an EventBoundedServicelProcess to the ServiceEvent that marks its start.<br />Note: there may be no more than one ServiceStartEvent for a given ServiceSequencedProcess.</td>
</tr>
<tr>
<td>SynchronousOperation</td>
<td>Type</td>
<td>An OperationSpecification where the caller and called wait for each other to complete the communication.</td>
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
<td>operationCaller</td>
<td>TupleType</td>
<td>A couple that asserts a ServiceOrConsumer invokes a SequencedOperation on a ServiceLifeline.</td>
</tr>
<tr>
<td>operationFlowInScenario</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation that relates an OperationSpecification to its usage (as a SequencedOperation) in a ServiceScenario<br />Note: A SequencedOperation is based on only one OperationSpecification</td>
</tr>
<tr>
<td>operationOwner</td>
<td>TupleType</td>
<td>A couple where a SequencedOperation is run by a ServiceLifeline.</td>
</tr>
<tr>
<td>serviceFunctionInSequence</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation that relates a ServiceFunction to a SequencedServiceFunction that is a case of it being used in a ServiceScenario.</td>
</tr>
</tbody>
</table>



<p>Table ‑: S6 Element List</p>


# S7 – Service Interface Parameters

{%include figure.html url="{{rasterimagepath}}image17.png" width="604" height="669"" description="S7 Logical Diagram<" %}


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
<td>AsynchronousOperation</td>
<td>Type</td>
<td>An OperationSpecification where the caller and called do not wait for each other to complete the communication.</td>
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
<td>Entity</td>
<td>Type</td>
<td>A DataModelComponent that defines an item of interest..</td>
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
<td>Interface</td>
<td>Type</td>
<td>A ModemIndividualType that is an interface either provided or required by another ModemIndividualType.</td>
</tr>
<tr>
<td>InterfaceOperation</td>
<td>Type</td>
<td>A TypicalWholePart that realtes an OperationSpecification to its InterfaceSpecification.</td>
</tr>
<tr>
<td>InterfaceSpecification</td>
<td>Type</td>
<td>A ModemIndividualType that is a part of another ModemIndividualType that defines how it communicates</td>
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
<td>MessageSpecification</td>
<td>Type</td>
<td>A DataElement that specifies the content of a message.</td>
</tr>
<tr>
<td>MinAggregateSize</td>
<td>Type</td>
<td>A RepresentationInStructure that specifies the minimum size of an AggregateDataType.</td>
</tr>
<tr>
<td>NumericDataType</td>
<td>Type</td>
<td>A SimpleDataType whose instances are numbers.</td>
</tr>
<tr>
<td>OperationInputParameter</td>
<td>Type</td>
<td>A TypicalWholePart where an OperationParameter is passed into a OperationSpecification.</td>
</tr>
<tr>
<td>OperationParameter</td>
<td>Type</td>
<td>A ModemIndividualType that is a part of an OperationSpecification. OperationParameters are passed in and out of OperationSpecifications.</td>
</tr>
<tr>
<td>OperationReadWriteParameter</td>
<td>Type</td>
<td>A TypicalWholePart where an OperationParameter is passed into a OperationSpecification that can then be modified and the result read after processing.</td>
</tr>
<tr>
<td>OperationReturnParameter</td>
<td>Type</td>
<td>A TypicalWholePart where an OperationParameter is passed out of an OperationSpecification.</td>
</tr>
<tr>
<td>OperationSpecification</td>
<td>Type</td>
<td>A ModemIndividualType that is an invokable part of an InterfaceSpecification. [ABSTRACT]</td>
</tr>
<tr>
<td>PhysicalDataModel</td>
<td>Type</td>
<td>A DataModel that is an implementable specification of a data structure. A PhysicalDataModel realises a LogicalDataModel, taking into account implementation restrictions and performance issues whilst still enforcing the constraints, relationships and typing of the logical model.</td>
</tr>
<tr>
<td>ProvidedInterface</td>
<td>Type</td>
<td>An Interface describing what a ServiceSpecification or a ResourceType is capable of providing when invoked by an external element.</td>
</tr>
<tr>
<td>RequiredInterface</td>
<td>Type</td>
<td>An Interface describing what a ServiceSpecification or a ResourceType requires from an external element.</td>
</tr>
<tr>
<td>ServiceInterface</td>
<td>Type</td>
<td>A TypicalWholePart that relates a ServiceSpecification to an Interface that it requires or provides.</td>
</tr>
<tr>
<td>ServiceSpecification</td>
<td>Type</td>
<td>A ServiceDeliveryType that is the specification of a ServiceDelivery.<br />Note: was called &quot;Service&quot; in M3.</td>
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
<td>SynchronousOperation</td>
<td>Type</td>
<td>An OperationSpecification where the caller and called wait for each other to complete the communication.</td>
</tr>
<tr>
<td>TextDataType</td>
<td>Type</td>
<td>A SimpleDataType whose instances are text literals.<br />Note: Data Models may instantiate several different TextDataTypes - e.g. &quot;String&quot;, &quot;XML Text&quot;, &quot;WideString&quot;, etc.</td>
</tr>
<tr>
<td>choiceElement</td>
<td>TupleType</td>
<td>A couple that asserts a DataModelTypeRepresentation is a valid choice in a ChoiceDataType.</td>
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
<td>parameterRepresentation</td>
<td>TupleType</td>
<td>A representedBy that links an OperationParameter to its datatype (DataModelTypeRepresentation).</td>
</tr>
<tr>
<td>specForInterface</td>
<td>TupleType</td>
<td>A modemIndividualTypeSpecialisation that relates an Interface to the InterfaceSpecification that specifies it.</td>
</tr>
<tr>
<td>supportedMessageFormat</td>
<td>TupleType</td>
<td>A couple that relates an Interface to a MessageSpecification that it can support.</td>
</tr>
</tbody>
</table>

<p>Table ‑: S7 Element List</p>


# S8 – Service Policy


{%include figure.html url="{{rasterimagepath}}image18.png" width="604" height="767" description="S8 Logical Diagram<" %}

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
<td>AttributeOfService</td>
<td>Type</td>
<td>A typeInstance that relates a ServiceSpecification to a ServiceAttribute relevent to measuring service performance.</td>
</tr>
<tr>
<td>Constraint</td>
<td>Type</td>
<td>A Type that is the collection of all the objects subject to a particular constraint.</td>
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
<td>ModemIndividualType</td>
<td>Type</td>
<td>The parent (supertype) of all MODEM elements that are types of Individuals e.g. tank, computer, etc.</td>
</tr>
<tr>
<td>ServiceSpecification</td>
<td>Type</td>
<td>A ServiceDeliveryType that is the specification of a ServiceDelivery. Note: was called &quot;Service&quot; in M3</td>
</tr>
<tr>
<td>ServiceSpecificationState</td>
<td>Type</td>
<td>A ServiceDeliveryStateType that is a type of temporal state typical of a ServiceSpecification.</td>
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
<td>measureTypeInstance</td>
<td>TupleType</td>
<td>A typeInstance that asserts a Measure is an instance of a MeasureCategory. Examples: 2kg is a mass, 40m/s is a velocity.</td>
</tr>
<tr>
<td>qualifiedMeasure</td>
<td>TupleType</td>
<td>A superSubtype that relates a MeasureInContext to the measure it qualifies</td>
</tr>
<tr>
<td>servicePolicy</td>
<td>TupleType</td>
<td>A measureOfType where the Measure specifies a policy for a ServiceSpecification. Note: The Measure must correspond to a given MeasureCategory that is an attributeOfService for the ServiceSpecification</td>
</tr>
<tr>
<td>upperBoundOfMeasureRange</td>
<td>TupleType</td>
<td>A superSubtype that asserts the MeasureInstance that is the upper bound (i.e. maximum measure) of a MeasureRange.</td>
</tr>
</tbody>
</table>

<p>Table ‑: S8 Element List</p>


# Sr – Service Roadmap


{%include figure.html url="{{rasterimagepath}}image19.png" width="604" height="393" description="Sr Logical Diagram" %}


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
<td>AttributeOfService</td>
<td>Type</td>
<td>A typeInstance that relates a ServiceSpecification to a ServiceAttribute relevent to measuring service performance.</td>
</tr>
<tr>
<td>Constraint</td>
<td>Type</td>
<td>A Type that is the collection of all the objects subject to a particular constraint.</td>
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
<td>ModemIndividualType</td>
<td>Type</td>
<td>The parent (supertype) of all MODEM elements that are types of Individuals e.g. tank, computer, etc.</td>
</tr>
<tr>
<td>ServiceLevel</td>
<td>Type</td>
<td>A ServiceDeliveryType based on a ServiceSpecification that sets a level of service using of Measures that correspond to ServiceAttributes.</td>
</tr>
<tr>
<td>ServiceSpecification</td>
<td>Type</td>
<td>A ServiceDeliveryType that is the specification of a ServiceDelivery. Note: was called &quot;Service&quot; in M3</td>
</tr>
<tr>
<td>ServiceSpecificationState</td>
<td>Type</td>
<td>A ServiceDeliveryStateType that is a type of temporal state typical of a ServiceSpecification.</td>
</tr>
<tr>
<td>ServiceSpecificationVersionSuccession</td>
<td>Type</td>
<td>A BeforeAfterType that asserts that one ServiceSpecification succeeds another. Note: both ServiceSpecifications must be versions of the same ServiceSpecificationMaster.</td>
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
<td>An ProjectState that is a temporal part of a Project and has been nominated as a phase of a Project.</td>
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
<td>servicePolicy</td>
<td>TupleType</td>
<td>A measureOfType where the Measure specifies a policy for a ServiceSpecification. Note: The Measure must correspond to a given MeasureCategory that is an attributeOfService for the ServiceSpecification</td>
</tr>
<tr>
<td>serviceSpecificationWithdrawnAt Milestone</td>
<td>TupleType</td>
<td>A couple that indicates that a ServiceSpecification is withdrawn at a ProjectMilestone.</td>
</tr>
<tr>
<td>upperBoundOfMeasureRange</td>
<td>TupleType</td>
<td>A superSubtype that asserts the MeasureInstance that is the upper bound (i.e. maximum measure) of a MeasureRange.</td>
</tr>
</tbody>
</table>


<p>Table ‑: Sr Element List</p>
