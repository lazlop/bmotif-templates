# Description of Guideline 36 Templates and Shapes

## Templates

The templates provided are comprehensive models of G36 compliant systems based on the system diagrams included in the informative appendix of Guideline 36. These are intended to show highly detailed, exhaustively modeled versions of these systems. 

## Shapes

These shapes contain the ASHRAE G36 data requirements for air-side equipment, defined in Section 4 of Guideline 36 (ASHRAE, 2018). These requirements are modeled as classes that use SHACL constraints to define how the equipment should be modeled in 223, focusing on the data points needed for Guideline 36 control sequences. These classes can be used to ensure that a model has the metadata necessary to support Guideline 36 sequences. They can be used to validate existing models against the requirements of Guideline 36 or to support modeling of compliant systems. They can also be used to create templates or support tooling that creates models to match the defined constraints. We have also included SHACL inference rules to infer labels for equipment within an existing 223 model, where modeling of the equipment satisfies the constraints defined for the Guideline 36 classes. This can support querying and semantic interoperability between models created with and without use of this extension. Additionally, this section includes example models of the systems presented in the Informative Appendix A of Guideline 36. This content is intended to serve as an example of how the 223 standard can be extended to create higher level classes specific to an application, that can be useful for both validation and inference. It is also intended to provide examples of how equipment can be modeled using 223.

These shapes will also be documented in an informative annex to the ASHRAE 223P standard. 

## Models

Example system models were created using these templates. These templates have also been used to model a real large office building. All models are also stored at models.open223.info
