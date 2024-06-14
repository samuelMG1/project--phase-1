# project--phase-1
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

## Data Preprocessing
1 .Handling Missing Values: Missing values were addressed by either imputing with appropriate statistics (mean, median) or removing records with excessive missing data.

2. Data Aggregation: Data was aggregated to analyze trends over time, accident rates by aircraft type, and other relevant metrics.

