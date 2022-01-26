# Primary objectives

Primary objective  of the developed system architecture are:

| # | Primary Objective |
| --- | --- |
| **PO-1**| **Monitoring of the MBS performance** |
| **PO-2** | **Predictive analysis of the MBS performance** |
| **PO-3** | **Data acquisition and storage**|

# Architecture Characteristics

| # | Characteristic | Description |
| --- | --- | --- |
| 1 | **Automation** | Necessary for operating in real-time environment to provide uninterrupted and continuous performance of the system |
| 2 | **Collaboration** | Providing a shared access to the data as to the companywide asset  |
| 3 | **Fault-tolerance** | System's ability to continue operating without interruption despite the failure of one or more of its components. |
| 4 | **Flexibility** | Supporting of multiplicity of business needs and ability to adapt for the new demands and requirements |
| 5 | **Integration** | Providing an opportunity of engagement and interaction with other systems and processes of the company |
| 6 | **Security** | Complying with privacy regulations and handling the risks of data leakage |
| 7 | **Scalability** | Ability to support higner workloads without critical changes of the system's structure |
| 8 | **Resilence** | System's ability to recover and restore its capabilities in case of outage|

# Architectural requirements

Architectural requirements of the developed system are listed in the table below and described in details 

| # | Architectural Requirement | Corresponding PO |
| --- | --- | --- |
| 1 | MBS status monitoring | **PO-1**|
| 2 | Operating conditions monitoring | **PO-1** |
| 3 | External factors monitoring | **PO-1** |
| 4 | Maintenance monitoring | **PO-1** |
| 5 | Predictive maintenance | **PO-2** |
| 6 | Scheduling and orchestration | **PO-3** |
| 7 | Data collection and storage| **PO-3** |


## 1. MBS status monitoring

Provide the working status of the MBS to the monitoring system

## 2. Operating conditions monitoring

Provide constant monitoring of the parameters characterizing technical condition of the MBS
- Inner temperature
- Fuel level
- Input/Output power
- Power supply
- Load dispatch
- Radiation level
- Frequency band
- Height above ground
- Vibration level
- Elements misalignment
- Presence of obstructions/cracks

## 3. External factors monitoring

Provide comprehensive monitoring of climatic, morfometric and technogenic factors that may have an influence on MBS performance

## 4. Maintenance monitoring

Provide monitoring of the performed maintenance according to the plan. Tracking the results of maintenance, including identified problems and issues.

## 5. Predictive maintenance

Provide data analysis and ML algorithms to learn from historical and live data to analyze failure patterns find optimum resource utilization and predicting failure before they happen
The techniques of predictive maintenance include:
- Prediction of Remaining Useful Life (with regression models)
- Prediction of failure within pre-decided timeframe (with classification models)
- Flagging anomalous behaviour

## 6. Scheduling and orchestration

Provide the automatic and uninterrupted execution of the monitoring processes according to the current schedule 

## 7. Data collection and storage

Provide the collection and storage of the data needed for monitoring processes

# Stakeholders and users of the system
- Monitoring system operator
- Control service operator
- Maintenance and repair technician
- Data Engineer
- Data Analyst
- Security officers

[Contribution guidelines for this project](../README.md)
