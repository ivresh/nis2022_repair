# Usage Scenario

Usage scenario describes an example of how one or more people or organizations (actors) interact with a system. Unlike use cases, they provide an overview of the users' actions without describing the deep technical details. A system's usage scenario with detailed description is presented below.

![image](https://user-images.githubusercontent.com/58341842/152159329-156fbe37-64e9-4004-9573-95484d4edfca.png)

## Description

The first component of the system is **authentication system**. It provides different rights for two groups of users: 
- **Tower operators** 
They control the work of the towers and the telemetry work and create the statistics of the selected parameters. 
- **Tower managers**
They analyze statistics, create dashboards and models, include the model prediction results and visualizations in the report.

Logically system can be divided in 3 main blocks: 
- **monitoring module** (where the telemetry control and management is being provided),
- **analytical system** (where the primary analytics and visualizations arebeing done), 
- **predictive module** (where necessary parameters are being chosen and model is being configured and run)

In the report part the results of predictive modelling are being interpreted. They and dashboards are added to the final report.

[Back to contents](../README.md)
