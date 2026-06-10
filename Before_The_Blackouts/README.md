Project Title: **Before the Blackout: A Data-Driven Approach to Detect Electrical Infrastructure Stress**


##  Project Overview

Electricity demand is continuously increasing due to rapid urbanization and industrial growth. High electricity consumption places significant stress on electrical infrastructure such as transformers, substations, and distribution networks.

This project presents a data-driven approach to predict electricity demand and identify potential infrastructure stress conditions before failures occur. By analyzing historical electricity consumption and environmental data, the system classifies infrastructure conditions into Normal, Warning, and Critical levels and generates early alerts to help prevent blackouts.



##  Objectives

- Predict electricity demand using Machine Learning.
- Detect abnormal electricity consumption patterns.
- Classify infrastructure stress levels.
- Generate early warnings for potential overload conditions.
- Visualize electricity demand and stress patterns.



##  Problem Statement

Electrical infrastructure stress is often identified only after equipment failures or power outages occur. There is a need for an intelligent monitoring system that can analyze historical electricity consumption data and provide early warnings of potential infrastructure stress before blackout conditions arise.



## Proposed Solution

The proposed system uses historical electricity consumption data along with environmental factors such as temperature and humidity to:

1. Predict future electricity demand.
2. Detect infrastructure stress levels.
3. Visualize stress patterns through graphs.



## System Workflow

Data Collection  
↓  
Data Preprocessing  
↓  
Feature Engineering  
↓  
Load Prediction using Machine Learning  
↓  
Stress Classification    
↓  
Visualization and Reporting

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Google Colab

---

## Dataset Features

### Input Features
- Temperature
- Humidity
- Date and Time
- Power Consumption Zone 1
- Power Consumption Zone 2
- Power Consumption Zone 3

### Derived Features
- Hour
- Month
- Total Power Consumption

---

## Machine Learning Model

### Linear Regression

**Input Features:**
- Temperature
- Humidity
- Hour
- Month

**Target Variable:**
- Total Power Consumption

**Output:**
- Predicted Electricity Load



## Stress Level Classification

Stress Level	Description
Normal	Safe operating condition
Warning	 High load condition
Critical	Possible infrastructure overload


The stress levels are determined using percentile-based thresholds from predicted electricity demand.



##  Output Visualizations

### 1. Stress Level Distribution
Displays the number of Normal, Warning, and Critical conditions.

### 2. Actual vs Predicted Load
Compares actual electricity demand with predicted demand.

### 3. Critical Stress Detection
Highlights critical infrastructure stress points.



Sample Output

ELECTRICAL INFRASTRUCTURE STRESS MONITORING SYSTEM

Total Records Analyzed : 52416

Normal Conditions   : 26208
Warning Conditions  : 18345
Critical Conditions : 7863

 Predicts the stress level



## Novelty of the Project

- Early detection of infrastructure stress before failures occur.
- Data-driven prediction instead of reactive monitoring.
- Automatic classification of stress conditions.
- Provides proactive alerts to reduce blackout risks.
- Supports smart grid and smart city applications.


##  Advantages

- Prevents unexpected power outages.
- Improves infrastructure reliability.
- Supports preventive maintenance.
- Enables data-driven decision making.
- Easy to implement and scale.

## Future Scope

- Integration with IoT sensors for real-time monitoring.
- Deployment as a web-based dashboard.
- Use of advanced Deep Learning models such as LSTM.
- Smart city and smart grid integration.
- Real-time alert notifications through SMS or Email.





