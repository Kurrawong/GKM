# Geoscience Knowledge manager

This repository contains public work items related to development of the ontology and knowledge base for the Loop 3D geology project.

Ontology developed by Boyan M. Brodaric and Stephen M. Richard.

License  [CC-BY](https://creativecommons.org/licenses/by/4.0/)

The wiki for this repository contains notes from team meetings. 

Please add issues or comments on the ontology in the issue tracker.


## File:
 - **GSO_OFR_01Mar2021.docx**  Draft GSC Open File report describing the ontology
 - **TimeIntervalRelation.pdf**  Diagram to help clarify Allen temporal relations between intervals and instants.


## Directory:
**Loop3D-GSO** contains the ontology files and associated documentation

### Files: 
 - **GSO-Common.ttl**  OWL file with high level framework ontology
 - **GSO-Geology.ttl**  OWL file with framework for geoscience
 - **GSO-Master.ttl**  OWL file, ontology that imports all modules to assemble entire GSO ontology
#### Sub directories:
**Modules**  Contains 28 module ontologies implementing aspects of geoscience building on framework in Common and Geology.

**Examples**  Contains a collection of instance documents (the .ttl files) demonstrating representation of various geologic scenarios.  This collection is likely to grow and change over time.
#### other files 
 - **GeologyScenarioForTesting.pptx** (and .pdf) invented cross section that is used for various example documents
 - **EasternRinconMountainsXSec.png** schematic cross section of Eastern Rincon Mountains, Arizona, used for various example documents
