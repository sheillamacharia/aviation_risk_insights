# aviation_risk_insights
Examining a century's worth of aviation mishaps and accidents to produce useful information for aviation safety stakeholders.

# **Overview**

In order to find trends, assess the severity of accidents, and pinpoint risk factors related to various aircraft types, operators, and geographical areas, this project examines historical aviation accident data.  The objective is to offer data-driven insights that can enhance resource allocation and aviation safety decision-making.

# **Business Understanding**

# Stakeholder:

1. Aviation Safety Authorities (e.g., Civil Aviation Boards, ICAO, FAA)

2. Airlines and Operators

3. Aircraft Manufacturers

# Key Business Questions:

 1. What aircraft models and manufacturers exhibit lower accident rates?  
 2. Variations in accident severity among different aircraft types.  
 3. Which operational factors, such as year, country, and category, influence accident risk?

# **Data Understanding and Analysis**

# Source of Data:

This preprocessed and cleaned aviation accident dataset includes accident records with information on date, location, operator, aircraft type, country, fatalities, and severity.

# Description of Data (key columns):

 - Date of occurrence of the accident/incident
 - Location of occurrence 
 - Country of occurrence 
 - Type of aircraft involved 
 - Aircraft registration number 
 - Operating organization/airline
 - Aboard/Fatalities – total number of individuals on board and total number of fatalities
 - Cate (Accident Category) – classification of the event
 - Year – the year of occurrence extracted

# **Visualizations**
# 1. Accidents by Aircraft Type

- Visualization: Bar chart of accidents grouped by aircraft type

- Insight: A small number of aircraft types dominate the majority of accidents, highlighting priority models for deeper investigation.

# 2. Accident Severity by Aircraft Type

- Visualization: Severity rate = Fatalities / Aboard, compared across aircraft types (boxplot or heatmap)

- Insight: Some aircraft types not only have more accidents but also deadlier ones, pointing to differences in safety outcomes.

# 3. Operational Risk Factors

- Visualization:

  - Line chart of accident trends over time (Year vs. Accident Count)

  - Map of accident distribution by Country

  - Bar chart of accidents by Operator

- Insight: Operational and geographic patterns show certain operators and regions carry higher risks.

# **Conclusion**

# Summary of Key Findings:

 1. Aircraft Type Matters: Most accidents involve a small subset of aircraft types.  Certain models have higher rates of severity in addition to being more common.

 2. Patterns of Severity  Differ: The severity of accidents varies among aircraft types; certain models have higher fatality ratios, so interventions should give priority to these models.

 3. Operational & Geographic Risks: Patterns indicate that certain operators and geographical areas experience a higher concentration of accidents, indicating that risk could be decreased by focused regulatory supervision and training.

# Business Implication:
Stakeholders can lessen the possibility and severity of future accidents by concentrating safety measures on high-risk aircraft types, operators, and geographical areas.

# Link to Interactive Dashboard

https://public.tableau.com/views/AviationAccidentRates/AircraftandOperationalRiskFactors?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link