# Description of HPFlex-MPC Templates and Shapes

## Templates 

These templates were used to support the deployment of a practical, low-cost, portable load-shifting MPC that has been deployed at 5 small and medium commercial buildings in ther US for control of packaged RTUs. These templates are used to enable a simple-survey driven MPC configuration procedure, making the MPC accessible to non-experts. These templates model the systems of interest for the MPC, and are also used to map 223P models into MPC specific data models for ease of use and interoperability.  

## Shapes

These shapes have been generated from the defined templates for validation and inference. These shapes are used with a manifest to validate that a building has the expected systems as well as the points necessary to configure the MPC. The shapes also are used to infer annotations for all the properties within a model, aligning the semantic data model with an mpc specific data model. This has been used to align multiple ontologies and allow the MPC to be configured using either s223 or brick. These inferred annotations along with the templates are used to query an existing semantic model into python data classes, that provide a familiar interface for interacting with the data and configuring the MPC. 