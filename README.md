# Challenge: Dynamic Asset Management
## Champions
- Ellen van den Bersselaar, BIM-Connected

## Challenge description:
Due to (1) the increasing number of inhabitants in city centres, (2) the growing need for transport related to e-
commerce and (3) a rising number of restrictions such as environmental zones, there is an increasing amount of
pressure on logistics management within cities. This also applies to the municipality of Utrecht, with an
important addition being the vulnerable historic city centre and underground with wharf cellars, which do not
allow heavy traffic (> 2 tonnes). One initiative that could help managing these assets, is an intelligent accessibility
system for commercial vehicles. The result could be to reduce issues such as congestion and nuisance, while on
the other hand improving safety and sustainability.
An intelligent access system works with data coming from commercial trucks' on-board computers and various
other mobility data sources and interacts with objects in the built environment so that a decision can be made
whether or not a truck is allowed access to a certain area or street. This means that a communicative model
should exist between a dynamic world of moving vehicles and a static world of buildings, gates, security
camera’s, etc. Based on the interactions between these dynamic and static objects, certain actions can be
triggered depending on restrictions for time, geographic zones, weight, fuel type, vehicle size, GPS, or other
properties.
For this to work properly, several sets of data from different sources need to be linked to each other, a correct
data model must be in place to be able to query the desired information, and most importantly, the results
should be presented in a manner so that the often-non-technical policy makers can interpret them. The
technologies provided by the semantic web stack can potentially offer a viable solution to set up the architecture
and tooling necessary for such an accessibility system that supports the Municipality of Utrecht in decision
making regarding their logistics.
## Challenger Research questions
Of course, this is not without difficulties. Often, the reality within (governmental) organizations is that data is
scattered through different source systems, often only available in human-readable text formats and not
structured according to one architecture, data model or ontology. Furthermore, knowledge about semantic web
standards and linked data is scarce, so we should not expect the users to be able to read a Turtle file or to enter
a SPARQL query. Therefore, the main research question is:
- How can we manage and visualize asset management data in the built environment using semantic web
technology if some of this data is dynamic in time and location?

- Sub question 1: How can semantic web technologies be used to manage assets if some of the data is dynamic in
time and location?
- Sub question 2: Is it possible to automatically restrict vehicles from entering certain zones in the city? What are
the rules and requirements for this?
- Sub question 3: How can SHACL be implemented in the information model behind the tooling? Is it possible to
activate certain restrictions for trucks based on their time-stamp data?
- Sub question 4: What are the steps needed for aligning different sets of data that originate from several sources,
including written text-based documents?
- Sub question 5: How can we visualize newly gained information that results from linking certain datasets? How can SPARQL and possibly OWL help with this and how does this work in a user-friendly manner?
- Sub question 6: In case of inferencing new information using OWL, how does this work in combination with
SHACL restrictions? Open world vs. closed world?

## Datasets and supplementary resources available
In the document 'User Manual' a thorough description of all the datasets and supplementary resources is available.

*Please notice the chapter 'Challenge guidelines" which separates the challenge into manageable parts fitted to the content of the LDAC Summer School lectures.*

## References
https://www.researchgate.net/publication/356493956_Intelligent_Access_Policy_ensuring_the_right_vehicle
_on_the_right_road_at_the_right_time
https://www.polisnetwork.eu/wp-content/uploads/2020/12/Smart-Loading-Zones-Alice-and-POLIS-Dec-17-
IS.pdf
