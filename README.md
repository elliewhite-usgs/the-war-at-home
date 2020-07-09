# The Militerization of U.S. Police; Department of Defense 1033 Program 

Total Police Acquisition   |  Total Police Shootings
:-------------------------:|:-------------------------:
![Total Police Acquisition](https://github.com/whiteellie/police-militarization/blob/master/q1_value_states_hexbin.png) |  ![Total Police Shootings](https://github.com/whiteellie/police-militarization/blob/master/q7_shootings.png)


# The 1033 program
According to the Law Enforcement Support Office (LESO) 
> The LESO Program, facilitates 10 US Code 2576a, which originated from the National Defense Authorization Act of Fiscal Year 1997. This law allows transfer of excess Department of Defense property that might otherwise be destroyed to law enforcement agencies across the United States and its territories.  

> No equipment is purchased for distribution.  All items were excess which had been turned in by military units or had been held as part of reserve stocks until no longer needed. 

> Since its inception, the program has transferred more than $6.8 billion worth of property. In Fiscal Year 2017, $504 million worth of property (based on initial acquisition cost) was transferred to law enforcement agencies.

> Requisitions cover the gamut of items used by America’s military -- clothing and office supplies, tools and rescue equipment, vehicles, rifles, and other small arms. Of all the excess equipment provided through the program, only five percent are small arms and less than one percent are tactical vehicles.

> More than 7,000 law enforcement agencies have enrolled in the program. 

# The Data
* This data set is provided by the Law Enforcement Support Office (LESO) at: https://www.dla.mil/DispositionServices/Offers/Reutilization/LawEnforcement/PublicInformation/. 
* This data set is supposed to be up to date for the life of the program. At the times of download (02/21/2019) the data ranged from 1990-05-03 to 2018-12-31.
* According to the DoD, "Some of the items DLA transfers under the LESO program were purchased, in some cases, up to 50 years ago.  Therefore, the acquisition cost is the value of the item when it was last purchased."
* Lookup tables for demilitarization codes and demilitarization integrity codes are included and notes on demilitarization codes can be found here: https://www.dla.mil/HQ/InformationOperations/Offers/Services/FIC/DEMILCoding/DEMILCodes.aspx
* Other data sets (e.g., population, demographics, police violence, etc.) were gathered from different sources and joined to this data set. 
* These data sets are not mine. My only contribution is the spatial processing and plots. 

# The processing 
* Record of the data processing and plots are provided in policing.Rmd file. 
* Multiplied the "Acquisition Value" column by the "Quantity" column to find the total acquisition value. The current maps are showing total value now, since it is more accurate. 
* Please contact white.elaheh@gmail.com for any comments, questions, and concerns.

# Questions I want to answer
* Q1. Which state aquired the most in value?
* Q2. Which state aquired the most in value per capita?
* Q3. Are the acquizitions hapenning in places with more people of color?
* Q4. How many items did each state get?
* Q5. What items was sent the most?
* Q6. What items where each state getting?
* Q7. Does the amount of acquizitions correlate with the number of police homocides?

# Incomplete tasks 
* cumulated value .gif by year
* fix colors on plots


