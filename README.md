# Energy-Usage-Simulation-for-RCT:    

link to full colab: https://github.com/AniaSupady/Energy-Usage-Simulation-for-RCT/blob/main/Energy_Usage_Simulation_for_RCT.ipynb


**Analyzing Demand Response Programs Using Randomized Controlled Trials (RCTs)**

This code demonstrates the analysis of energy usage data from a simulated demand response program using Randomized Controlled Trials (RCTs). RCTs are a powerful and well-studied method in the field of experimental design and evaluation, particularly in assessing the impact of interventions like demand response programs.

This repository contains Python code for analyzing energy usage and temperature patterns across different treatment groups in a simulated dataset. The analysis includes generating synthetic data, aggregating energy usage and temperature at hourly intervals, and visualizing the results using matplotlib.

**Necessary Assumptions for Conducting Demand Response Programs Using RCTs**

Before implementing and analyzing a demand response program using RCTs, several critical assumptions must be carefully considered and ideally met to ensure the validity and reliability of the findings:

- Random Assignment:

Assumption: Households are randomly assigned to treatment (intervention) and control (no intervention) groups.  

Rationale: Random assignment minimizes selection bias, ensuring that any observed differences in outcomes between groups can be attributed to the intervention rather than pre-existing differences.

-  Homogeneous Treatment Effect:

Assumption: The impact of the demand response intervention is consistent across different households.  

Rationale: If there are significant variations in how households respond to the intervention (e.g., based on income levels, household size, energy usage patterns), it may confound the results. Methods like subgroup analysis can help explore heterogeneity.

-  Temporal Stability:

Assumption: The demand response program's effectiveness remains stable over time during the study period. 

Rationale: Changes in external factors (e.g., economic conditions, weather patterns) or internal factors (e.g., program fatigue, technological advancements) could affect outcomes if not accounted for.

-  Measurement Validity and Reliability:  

Assumption: Accurate and consistent measurement of key variables (e.g., energy usage, temperature) across treatment and control groups.  


Rationale: Measurement errors or inconsistencies can lead to biased estimates of the program's impact. Robust data collection methods and quality assurance protocols are essential.  






**Key Components**  

-  Data Generation and Simulation:  

Parameters such as household count, hours in a day, and treatment group allocation are set.

Energy usage is simulated based on household characteristics and treatment conditions.

Temperature data is generated to simulate varying weather conditions.

-  Data Processing and Aggregation:  

Energy usage and temperature data are aggregated at the hourly level for both control and treatment groups.

Hourly aggregation allows for comparison and visualization of average energy usage and temperature patterns.

-  Visualization:  

Matplotlib is used to create line plots that overlay temperature and energy usage for control and treatment groups.
Secondary axes are utilized to show energy usage alongside temperature, facilitating comparison.

-  Statistical Analysis:  

Statistical metrics such as average treatment effect during peak hours are calculated and displayed.

Checks are implemented to ensure data integrity, including handling of negative energy usage values.

-  Usage  

This code serves as a demonstration of analyzing energy consumption patterns and their relationship with temperature variations. It can be adapted and expanded for similar analyses in energy management, climate impact studies, or related fields.
