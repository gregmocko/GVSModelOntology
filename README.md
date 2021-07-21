# GVSModelOntology
The Ground Vehicle Simulation Ontology (GVSO) comprise 4 XXXX ontologies that represent terms with the domain of physics based simulation of groud vehicle.s The GVSO is a domain specific ontology that imports the Basic Formal Ontology (BFO) and the Common Core Ontologies (CCO). The GVSO is also based on the current state of the art as published in SAE standards. The ontologies within the GVSO include:

* Mission / KPI Ontology/ Testing Scenario (Vehicle Operation) - how a model is mapped to predict KPI, may consist of multiple integrated, captures the process of exercising a model to answer a question, predice a performance)
** vehicle test case
* Environment Ontology (Environment.owl) - reusable blocks to capture the environment in which the vehicle behaves.
* Ground Vehicle Ontology (GroundVehicle.owl) (the struture of the vechicle componentns, systems.) - like 3049
* Drive Cycle ???
* Model Ontology (Model.owl) (the definition of model interfaces, authorship, assumption) - 2998

* Simulation Ontology
* Ground Vehicle Ontology
* Ground Vehicle Testing Ontology

=======
Process
Step 0: Create integrated ontology GVOSO, Import Ontologies from Step 1 onward
Step 1: Create a ontology in OWL formate for the specific subontology.
Step 2: Import CCO from Minhal URL ....

For every change that is made to the Subontolgies, they will be committed to the GIThub so that we all are using hte correct ontology.
Do not download any ontology locally ....
Step 0: create integrated ontology and import all sub-ontology
While working on the ontology: 
Step 1: Create subontology as OWl file, import CCO/BFo using URL
Step 2: Save subontology to ontology folder, remove import,
Step 3: committ saved ontology to Github

Please check this. 


# Basic Formal Ontology
https://github.com/bfo-ontology/BFO/wiki


# Common Core Ontologies
https://github.com/CommonCoreOntology/CommonCoreOntologies

The CCO ontology is imported from the Merged ontology. 
