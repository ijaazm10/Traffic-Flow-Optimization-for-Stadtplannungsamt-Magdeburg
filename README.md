# Traffic-Flow-Optimization-for-Stadtplannungsamt-Magdeburg
Traffic Flow Optimization project for Magdeburg's City Planning Office. This repository contains a simulation model and research-backed recommendations to alleviate congestion and improve traffic flow within the city.

# Traffic Flow Optimization for Stadtplannungsamt Magdeburg
This project enhances traffic flow efficiency and reduces congestion in Magdeburg, Germany. It uses a traffic simulation model and data analysis to recommend immediate and long-term traffic planning improvements.

Project Overview
Motivation: Traffic congestion negatively impacts commutes, safety, and the environment in urban areas.
Approach: A Java-backed AnyLogic simulation model replicates real-world traffic scenarios. Extensive experimentation and analysis identify optimal traffic light coordination and infrastructure adjustments.
Outcomes: The project significantly reduced traffic congestion and improved traffic flow efficiency in Magdeburg.
Key Components
Traffic Simulation Model: A detailed AnyLogic model with Java integration accurately replicates Magdeburg's traffic network, enabling experimentation with various traffic scenarios and optimization strategies.
Experimentation and Analysis: Four experiments validated the model and assessed different traffic management approaches. Rigorous analysis, including the use of Excel, identified key factors influencing traffic flow and areas for improvement.
Recommendations: Data-driven recommendations address immediate congestion relief and long-term traffic planning, including traffic light coordination, infrastructure adjustments, and potential policy changes.
Repository Contents
Simulation Model: AnyLogic model files (.alp) and associated Java code.
Data: Raw and processed traffic data (e.g., vehicle inter-arrival times, turning probabilities, traffic light timings).
Analysis Spreadsheets: Excel spreadsheets with data analysis and calculations.
Reports: Detailed reports summarizing project findings, recommendations, and supporting data.
Presentations: Slides summarizing project milestones and key results.
Data Collection and Analysis
Data Sources: Historical traffic data from the city of Magdeburg (2019) and additional data collected manually during peak evening hours (3 PM to 5 PM).
Data Types:
Input Data: Probability of vehicles turning into different lanes, road capacity, average vehicle length, traffic light timings, and vehicle inter-arrival times.
Output Data: Number of vehicles exiting the node, average time spent by vehicles in the system, and average queue length.
Data Analysis: Statistical analysis was performed using histograms, Q-Q plots, and the chi-squared goodness-of-fit test to determine the probability distributions of inter-arrival times.
Model Validation
Validation Process: The simulation model was validated by comparing its outputs to real-world data collected during peak hours.
Validation Results: The model's output generally aligned with real-world observations, with minor discrepancies in queue length and throughput for Ummendorfer Street.
Model Refinement: The model was refined by adding pedestrian crossings, adjusting road lengths, correcting turning probabilities, changing car properties, and creating a custom distribution for Große Diesdorfer Straße.
Experiments and Recommendations
Four experiments were conducted to evaluate potential improvements to traffic flow:

1. Moving Tram Lines: Relocating tram lines to free up space at the lower intersection.
2. Merging Intersections: Combining Hannoversche Straße and Kümmelsberg to simplify the northern intersection.
3. Adjusting Traffic Lights: Modifying traffic light timings and removing a traffic light at the lower intersection.
4. Building an Underpass: Constructing an underpass for vehicles from Große Diesdorfer Straße and Diesdorfer Graseweg to bypass the lower intersection.
Based on the experiment results, the project recommends implementing the third experiment (adjusting traffic lights) due to its positive impact on throughput and cost-effectiveness.
