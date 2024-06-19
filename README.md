# project--phase-1
## Aviation Accident Analysis
Welcome to the Aviation Accident Analysis repository. This project aims to provide a comprehensive analysis of aviation accidents using data from the National Transportation Safety Board (NTSB). The dataset includes information on civil aviation accidents and selected incidents in the United States and international waters from 1962 to 2023. The analysis focuses on identifying trends, patterns, and key factors contributing to aviation accidents and findings 
# Business Understanding
## Stakeholders

1.Aviation Safety Authorities: Interested in understanding the causes and trends of aviation accidents to improve safety regulations and protocols.

2. Airline Companies: Focused on identifying risk factors to enhance safety measures and reduce accident rates.

3. Insurance Companies: Concerned with assessing risk and determining insurance premiums based on accident data.

4. General Public: Interested in understanding aviation safety and the factors that contribute to accidents.

## Key Business Questions
1. What are the primary causes of aviation accidents?
2. How have aviation accident rates and severity changed over time?
3. What are the common factors (e.g., weather, aircraft type, pilot experience) associated with aviation accidents?

# Data Understanding and Analysis
## Source of Data
The data for this project is sourced from the National Transportation Safety Board (NTSB) and includes detailed information on civil aviation accidents and selected incidents from 1962 to 2023. The dataset contains various attributes related to the accidents, such as date, location, aircraft type, weather conditions, and causal factors.

## Description of Data
1. EventID: Unique identifier for each accident.
2. EventDate: Date of the accident.
3. Location: Location of the accident.
4. AircraftType: Type of aircraft involved in the accident.
5. InjurySeverity: Severity of injuries (e.g., Fatal, Serious, Minor, None).
6. AircraftDamage: Extent of aircraft damage (e.g., Destroyed, Substantial, Minor).
7. WeatherCondition: Weather conditions at the time of the accident (e.g., VMC, IMC).
8. BroadPhaseOfFlight: Phase of flight during which the accident occurred (e.g., Takeoff, Cruise, Landing).
9. PilotExperience: Experience level of the pilot (e.g., Total flight hours).
10. CausalFactors: Factors contributing to the accident (e.g., Pilot error, Mechanical failure).
## Tableau dashboard:
https://prod-uk-a.online.tableau.com/#/site/gathogosammy882d6659e9b/views/dashboard_pdf/Dashboard1?:iid=7
## visulizations
1.  graph showing trends of accidents
  -Before 1980, there were no aeroplanes.
  -The year 1980 recorded the highest number of accidents. As the years progress, the number of accidents is reducing due to improvements in skilled manpower and technology, though more research needs to be done.
2. Accidents over time and aircraft category
   -The matplot shows the highest number of accidents per aircraft category,
  Where airplane and helicopter had most accidents in the distribution category.
3. Accidents over time by make
   - CESSNA has the most accidents compared to other aircraft.
4. Analysis at what point the accident happened
   -This visualization shows that the occurrence of accidents in the phase of flight is unknown but most cases happen when landing and take off.
5. Distribution of Total Fatal, serious and minor injuries
   -plotting: Two subplots are created:
    1.) The first subplot shows the total number of incidents by phase of flight.
    2.) The second subplot shows the total number of fatal, serious, and minor injuries by phase of flight, differentiated by color (hue). This visualization will help you understand the distribution of incidents and injuries across different phases of flight.

## Data Preprocessing
1 .Handling Missing Values: Missing values were addressed by either imputing with appropriate statistics (mean, median) or removing records with excessive missing data.

2. Data Aggregation: Data was aggregated to analyze trends over time, accident rates by aircraft type, and other relevant metrics.
## summary Conclusions
## Recommendation 
1. Data Cleaning and Preparation:
a) Handle Missing Values: Identified  and addressed missing values by either imputing them with appropriate statistics (mean, median, mode) or removing records with significant missing data.
b) Data Aggregation: Aggregate the data by relevant dimensions such as year, accident severity, and aircraft type.
2. Interactive Dashboard Development:
a) Visualization Tools:
   - Used tools like Tableau, Power BI, or a web-based solution (e.g., Plotly Dash) to create an interactive dashboard.
b) User Interaction: Ensured the dashboard allows users to filter data by various dimensions (e.g., year, aircraft type, accident cause) to explore the data interactively.
3. Insights and Analysis:

Trend Analysis: Analyzed trends over time to identify any significant changes in the number and severity of accidents.
4. Stakeholder Engagement
  - Training and Support
## Next Steps
* Data Preparation:

-Clean and preprocess the dataset, addressing missing values and aggregating data as necessary.
-Conduct exploratory data analysis (EDA) to identify key patterns and insights.
* Dashboard Development:
- Design and develop the interactive dashboard using a suitable visualization tool.
- Include various filters and interactive elements to allow stakeholders to explore the data dynamically.
## Thank You
Thank you for your time and attention. If you have any questions, please feel free to ask.

Name: Samuel Gathogo
