# Primary objectives

Primary objective  of the developed system architecture are:

| # | Primary Objective |
| --- | --- |
| PO-1 | Monitoring of the MBS performance |
| PO-2 | Predictive analysis of the MBS performance |
| PO-3 | Data acquisition and storage |

# Architectural requirements

Architectural requirements of the developed system are listed in the table below and described in details 

| # | Architectural Requirement | Corresponding PO |
| --- | --- | --- |
| 1 | MBS status monitoring | PO-1 |
| 2 | Operating conditions monitoring | PO-1 |
| 3 | External factors monitoring | PO-1 |
| 4 | Maintenance monitoring | PO-1 |
| 5 | Predictive maintenance | PO-2 |
| 6 | Scheduling and orchestration | PO-3 |
| 7 | Data collection and storage| PO-3 |


# 1. MBS status monitoring

Provide the working status of the MBS to the monitoring system

# 2. Operating conditions monitoring

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

# 3. External factors monitoring

Provide comprehensive monitoring of climatic, morfometric and technogenic factors that may have an influence on MBS performance

# 4. Maintenance monitoring

Provide monitoring of the performed maintenance according to the plan. Tracking the results of maintenance, including identified problems and issues.

# 5. Predictive maintenance

Provide data analysis and ML algorithms to learn from historical and live data to analyze failure patterns find optimum resource utilization and predicting failure before they happen
The techniques of predictive maintenance include:
- Prediction of Remaining Useful Life (with regression models)
- Prediction of failure within pre-decided timeframe (with classification models)
- Flagging anomalous behaviour

# 6. Scheduling and orchestration

Provide the automatic and uninterrupted execution of the monitoring processes according to the current schedule 

# 7. Data collection and storage

Provide the collection and storage of the data needed for monitoring processes

