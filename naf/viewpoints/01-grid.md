---
title: NAF Grid Representation
---

The NAF is a two-dimensional classification scheme for descriptive representations
of an Enterprise. The views available to NAF modellers are shown in the NAF Grid
Representation at Figure 3-1:

Figure 3-1: NAF Grid Representation

The NAF views are arranged as a grid with columns representing:

1. Classification/Ontology – taxonomies of concepts such as capabilities,
   services, etc.
2. Structure – how elements are assembled (enterprises, nodes, resources, etc.).
3. Connectivity – everything from high-level capability dependencies to detailed
   system connectivity.
4. Behaviour – how things work.
   * Activities – process flows and decomposition.
   * States – allowable state transitions.
   * Sequences – how things interact and in what order.
5. Information – what information/data is used, and how it is structured.
6. Constraints – rules that govern the enterprise, nodes, resources, etc.
7. Programme – project timelines and milestones affecting the elements in the
   architecture.
{: type="a"}

The NAF view rows retain an equivalence with the NAF v3.1 views[^1] , albeit with
names that better describe their purpose, as indicated in Table 3-1: Mapping of NAF
v3.1 views to NAF view :

Table 3-1: Mapping of NAF v3.1 views to NAF view rows

Each cell at the intersection of the layers and model kinds is a view (usually an
existing NAF 3.1 view). The new approach is information-centric. It divides the
framework up into categories of architectural information rather than how the
information is presented.

Most of the NAF v3.1 views match one cell. However, because the grid is based on
the type of information, rather than how it is presented, there are cases where a cell
covers more than one NAF v3.1 view (usually this is where there is a graphical view
and a tabular one showing the same information).

In some cases, there are no corresponding views. Most of these are left blank on the
grid, recognising there is no current requirement in the NAF for this information.
There are two cells (C5, Effects, and Sr, Service Roadmap) where there is meta-
model coverage, but no equivalent view in the current MODAF or NAF specifications.
Some views are not included – notably the Technology and Standards Forecasts,
and the NAV-1 (Overview and Summary Information).

In order to deal with concepts such as actual organisations and fielded capabilities,
the NAF grid approach moves these to the physical layer. Although there was little
coverage of individual people, equipment, etc. in NAF v3.1, the NAF Meta-Model
(MODEM) has more detail in this area.

Finally, some NAF views existed only to document the mapping from one layer to
another. These are shown as interstitial views (C1-S1, Capability to Service
Mapping, and L4-P4, Activity to Function Mapping) in the grid.

[^1]: Post NAF v3.1, the term ‘View’ is used to refer to a populated View within a particular architecture, in accordance with ISO/IEC/IEEE 42010.
