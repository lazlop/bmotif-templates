# Description of Hot Water Reset Shapes and Templates

## Templates 

These templates were used to model a real building for the purpose of deploying an energy-efficient supervisory control strategy resetting supply hot water temperature setpoints. 

## Shapes

These shapes are used for validation that a system has the necessary equipment and points to deploy the hot water reset strategy. They align with queries within the application to ensure that those queries won't fail, and that the application can be successfully configured. They may be used to debug a model to ensure information is represented correctly to support portable application configuration. These shapes were applied within a python application pipeline, and without this pipeline, may lead to irrelevant validation errors on equipment not needed for the reset application. 

## Models

The models directory includes an anonymized model of a real medium-large building created using these templates, where the application was deployed. 
