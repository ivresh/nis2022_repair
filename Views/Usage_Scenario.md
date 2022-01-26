# Usage Scenario

Usage scenario describes an example of how one or more people or organizations (actors) interact with a system. Unlike use cases, they provide an overview of the users' actions without describing the deep technical details. A system's usage scenario with detailed description is presented below.

![image](https://user-images.githubusercontent.com/58341842/151179719-1d697dd8-43fc-4d44-bfdb-c6eda43ca7dc.png)

## Desciption

The first component of the system is **authentication system**. It provides different rights for two groups of users: _tower operators and tower managers_. _Tower operators_ control the work of the towers and the telemetry work. Also they create the statistics of the selected parameters. _Tower managers_ analyze statistics, create dashboards and models, include the model prediction results and visualizations in the report.
Logically system can be divided in 3 main blocks: 
- **monitoring module** (where the telemetry control and management is being provided),
- **analytical system** (where the primary analytics and visualizations arebeing done), 
- **predictive module** (where necessary parameters are being chosen and model is being configured and run)

In the report part the results of predictive modelling are being interpreted. They and dashboards are added to the final report.

