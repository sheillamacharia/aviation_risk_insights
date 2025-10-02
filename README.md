# aviation_risk_insights
Investigating a century of aviation accidents and incidents to generate actionable insights for stakeholders in aviation safety.

# **Overview**

This project analyzes historical aviation accident data to uncover patterns, evaluate accident severity, and identify risk factors associated with different aircraft types, operators, and regions. The goal is to provide data-driven insights that can help improve aviation safety decision-making and resource allocation.
# **Business Understanding**

# Stakeholder:

1. Aviation Safety Authorities (e.g., Civil Aviation Boards, ICAO, FAA)

2. Airlines and Operators

3. Aircraft Manufacturers

# Key Business Questions:

1. Which aircraft models or manufacturers are associated with higher or lower accident rates?

2. How does accident severity (measured by fatalities-to-aboard ratio) vary across different aircraft types?

3. What operational or environmental factors (e.g., operator, geography, time) contribute most to accident risk?

# **Data Understanding and Analysis**

# Source of Data:

Aviation accident dataset (cleaned and preprocessed) containing accident records with details on date, location, operator, aircraft type, country, fatalities, and severity.

# Description of Data (key columns):

- Date – Date of accident

- Location – Accident location

- Country – Country where accident occurred

- Operator – Airline or operator involved

- Type – Aircraft type/model

- Fatalities – Number of deaths in the accident

- Fatal Flag – Indicates whether the accident was fatal (1) or not (0)

- Year – Extracted year of accident

- Cat – Accident category/classification

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

1. Aircraft Type Matters: A small subset of aircraft types account for the majority of accidents. Some models not only appear frequently but also have higher severity rates.

2. Severity Patterns Differ: Accident severity is not uniform across aircraft — specific types show higher fatality ratios, meaning interventions should prioritize these models.

3. Operational & Geographic Risks: Trends show accident concentration in specific regions and among certain operators, suggesting targeted regulatory oversight and training could reduce risk.

# Business Implication:
By focusing safety measures on high-risk aircraft types, operators, and regions, stakeholders can reduce the likelihood and severity of future accidents.

# Link to Interactive Dashboard

https://public.tableau.com/views/AviationAccidentRates/AircraftandOperationalRiskFactors?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link