# Airplane-Crash-since-1920-EDA
# Introduction 
This exploratory data analysis of the airplane crash data analyzes the crash trend for over 100 years beginning from the year 1920 to 2020. It is particularly interesting to observe the trend of airplane crashes and the reasons behind them, as air travel is the one of the most common transport medium these days. It is also important to examine our progress in overcoming the crashes.

# Data Description 
Dataset consist of 4967 observations (crashes) and 13 features. Below you can find the dataset column descriptions:
• Date: Date of accident, in the format - January 01, 2001
• Time: Local time, in 24 hr. format unless otherwise specified
• Location: Place of crash
• Airline/Op: Airline or operator of the aircraft
• Flight #: Flight number assigned by the aircraft operator
• Route: Complete or partial route flown prior to the accident
• AC Type: Aircraft type
• Reg: ICAO registration of the aircraft
• cn / ln: Construction or serial number / Line or fuselage number
• Aboard: Total aboard (passengers / crew)
• Fatalities: Total fatalities aboard (passengers / crew)
• Ground: Total killed on the ground
• Summary: Brief description of the accident and cause if known
# Data Cleaning
The Following steps were taken for data cleaning: –
1. It was observed that same values in the operator and type fields were recorded in both upper and lower case. All the values in these fields were converted to upper case.
2. The Date and Time values were Strings. These values were converted to date and time format.
3. Extracting Country, State and city from the location column. Challenges - For some countries (e.g. United States), country name is not present only state name is present.
# Exploratory data analysis 
## Summaries and Findings.
1. United States has seen significantly more number of crashes and fatalities resulting from them than any other country. 
2. Although there have been many incidents in United States, the number of fatalities are low.
3. There was a peak observed in number of incidents and fatalities during the period 1965-1975 and since there has been decline in both these metrics.
4. Aeroflot and Military - U.S. Air Force are worst operators as they have been responsible for a large number of aircraft crashes.
5. Douglas Dc-3 types of aircraft are most prone to crashes.
6. Text analysis for summary of incidents show that major incidents are due to pilots, engine failures, approach, during take-off, on the runway, mountains and altitude.
