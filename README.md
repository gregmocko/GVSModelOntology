# GVSModelOntology
The Ground Vehicle Simulation Ontology (GVSO) comprise 4 XXXX ontologies that represent terms with the domain of physics based simulation of groud vehicle.s The GVSO is a domain specific ontology that imports the Basic Formal Ontology (BFO) and the Common Core Ontologies (CCO). The GVSO is also based on the current state of the art as published in SAE standards. The ontologies within the GVSO include:

* Simulation Modeling Ontology (SimMod.owl) - Based on J2998. Represents the modeling, simulation, composition process, and querying of the three ontologies below.
* Ground Vehicle Architecture Ontology (VehArch.owl) - Based on J3049. Decomposes the systems and subsystems of a GV and the signals and physical quantities they exchange.
* Ground Vehicle Operations Ontology (VehOps.owl) - Derived from TOP documents. Decomposes the process of operating a GV to output a KPI in order to evaluate vehicle performance or execute a mission.
* Environment Ontology (Env.owl) - Derived from TOP documents, J3049, and EnvO. Represents the necessary information to describe the environment in which a GV operates.

=======
Process



For every change that is made to the Subontolgies, they will be committed to the GIThub so that we all are using hte correct ontology.
Do not download any ontology locally ....

Step 0: Create integrated ontology and import all sub-ontology
While working on the ontology: 

Step 1: Create subontology as OWl file, import BFO & CCO using URL

Step 2: Create/Save/Push Sub-ontology to ontology folder on Github, prior to Push remove CCO & BFO import 

Step 3: Commit saved ontology to Github

Questions - when an ontology is saved will it have the same url?

# Basic Formal Ontology
https://github.com/bfo-ontology/BFO/wiki


# Common Core Ontologies
https://github.com/CommonCoreOntology/CommonCoreOntologies

The CCO ontology is imported from the Merged ontology. 
