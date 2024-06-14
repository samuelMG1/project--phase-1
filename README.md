# project--phase-1
Welcome to the Aviation Accident Analysis repository. This project aims to provide a comprehensive analysis of aviation accidents using data from the National Transportation Safety Board (NTSB). The dataset includes information on civil aviation accidents and selected incidents in the United States and international waters from 1962 to 2023. The analysis focuses on identifying trends, patterns, and key factors contributing to aviation accidents and findings 
Business Understanding
Stakeholders

Aviation Safety Authorities: Interested in understanding the causes and trends of aviation accidents to improve safety regulations and protocols.
Airline Companies: Focused on identifying risk factors to enhance safety measures and reduce accident rates.
Insurance Companies: Concerned with assessing risk and determining insurance premiums based on accident data.
General Public: Interested in understanding aviation safety and the factors that contribute to accidents.

Key Business Questions
What are the primary causes of aviation accidents?
How have aviation accident rates and severity changed over time?
What are the common factors (e.g., weather, aircraft type, pilot experience) associated with aviation accidents?

Data Understanding and Analysis
Source of Data
The data for this project is sourced from the National Transportation Safety Board (NTSB) and includes detailed information on civil aviation accidents and selected incidents from 1962 to 2023. The dataset contains various attributes related to the accidents, such as date, location, aircraft type, weather conditions, and causal factors.

Description of Data
EventID: Unique identifier for each accident.
EventDate: Date of the accident.
Location: Location of the accident.
AircraftType: Type of aircraft involved in the accident.
InjurySeverity: Severity of injuries (e.g., Fatal, Serious, Minor, None).
AircraftDamage: Extent of aircraft damage (e.g., Destroyed, Substantial, Minor).
WeatherCondition: Weather conditions at the time of the accident (e.g., VMC, IMC).
BroadPhaseOfFlight: Phase of flight during which the accident occurred (e.g., Takeoff, Cruise, Landing).
PilotExperience: Experience level of the pilot (e.g., Total flight hours).
CausalFactors: Factors contributing to the accident (e.g., Pilot error, Mechanical failure).

Data Preprocessing
1 .Handling Missing Values: Missing values were addressed by either imputing with appropriate statistics (mean, median) or removing records with excessive missing data.
2.Data Aggregation: Data was aggregated to analyze trends over time, accident rates by aircraft type, and other relevant metrics.

