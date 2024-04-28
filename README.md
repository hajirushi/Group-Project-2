# Team 2 MIST4610 Group 2 
47114 Group 2
# Team Members
1. Michael Chun [@hajirushi](https://github.com/hajirushi)
2. Teja Vegesna [@teja-vegesna](https://github.com/teja-vegesna)
3. Dylan Ladd [@DylanLaddUGA](https://github.com/DylanLaddUGA)
4. Michael Kushnerick [@michaelkushnerick](https://github.com/michaelkushnerick)
5. Pratik Patel [@PratikPatel4444](https://github.com/PratikPatel4444) 
6. Kyle O'Connor [@kyleoconnor5](https://github.com/kyleoconnor5)
# Dataset Description
Descriptions of the data set: The dataset we used for this project was
(https://data.cityofnewyork.us/Public-Safety/NYPD-Arrests-Data-Historic-/8h9b-rp9u). This dataset contained 24 columns and over 5.72 million rows of data. The columns used in the dataset are listed below along with what each column is used for in the dataset. The dataset originally had data from 2006; however, we decided to use data from more recently (1/1/2020 - 12/31/2023) to address if COVID had any impact on more recent crime. After manipulating the dataset to just contain the set dates we wanted the rows decreased from 5.72 million rows to just about 700,000. 


**Below is a description of what each column in the dataset is and what it is used for**

**Arrest Key**: A unique identifier for each arrest record.

**Arrest Date**: The date and time when the arrest occurred.

**PD Cd**: The internal code used by the NYPD to represent the specific offense.

**PD Desc**: A description of the offense corresponding to the PD Code.

**KY Cd**: The internal code used by the NYPD to classify the offense.

**OFNS Desc**: A description of the offense corresponding to the KY Code.

**LAW Code**: The internal code used by the NYPD to represent the law under which the arrest was made.

**LAW Cat Cd**: The category of law under which the arrest was made (e.g., felony, misdemeanor, violation).

**Arrest Boro**: The borough where the arrest occurred (e.g., Manhattan, Bronx, Brooklyn, Queens, Staten Island).

**Arrest Precinct**: The precinct where the arrest occurred.

**Jurisdiction Code**: The jurisdiction code indicating the agency responsible for the arrest.

**Age Group**: The age group of the individual arrested.

**Perp Sex**: The gender of the individual arrested (e.g., Male, Female).

**Perp Race**: The race of the individual arrested.

**X Coord Cd**: The X-coordinate of the location where the arrest occurred.

**Y Coord Cd**: The Y-coordinate of the location where the arrest occurred.

**Latitude**: The latitude coordinate of the location where the arrest occurred.

**Longitude**: The longitude coordinate of the location where the arrest occurred.

**Lon Lat**: The combined longitude and latitude coordinates.

**Zip Codes**: The zip code of the location where the arrest occurred.

**Community Districts**: The community district of the location where the arrest occurred.

**Borough Boundaries**: The boundary of the borough where the arrest occurred.

**City Council Districts**: The city council district of the location where the arrest occurred.

**Police Precincts**: The police precinct of the location where the arrest occurred.




# Question 1 Explained
Question: What trends emerge when analyzing the relationship between age and demographics and the prevalence of specific types of crime in New York City?



Importance:
This question would help with understanding which age groups are more susceptible to certain types of crimes, in turn this could help to inform law enforcement strategies and crime prevention efforts. By identifying the trends in crime prevalence it would allow for authorities to allocate resources to be more efficient in reducing crime. Examining the relationship between age and demographics would bring forward certain societal issues such as inequality, poverty and gaining access to important education and employment opportunities, identifying the societal issues and allocating the needed resources to stopping crime would lead to a decrease in long term crime rate. Finally by grasping the trends and enforcing the preventative measures it would allow for New York City to become safer as a whole.


# Question 2 Explained
Question: Does the borough and covid have an impact on the number and type of crime that takes place?

Importance:
This question is important because New York City has a large population, so it is necessary to break it down into smaller chunks such as boroughs. Each borough is distinct in terms of features such as the culture, attractions, and the people who live there, so it is important to individualize them versus grouping them as one. Because of these differences, the amount of crimes and type of crimes will differ vastly among the boroughs. Some places may have more serious crimes, where other boroughs may have a greater amount. It’s important to highlight the differences, as it allows for police forces to allocate their limited number of resources in a vast population to the places that need it the most. Examining trends and relationships will allow for an eventual decrease in crimes that will take place within each borough, overall decreasing the crime rate for New York City. It is also important to examine the differences between now and when the covid pandemic started. We want to see the differences in crime rate, with factors such as unemployment and lifestyle changes potentially increasing or decreasing the crime rate and types of crimes occurring. Understanding if these factors are important in terms of crime can signify whether the New York government should take action in regard to these issues for tackling the issue of crime.

# Data Manipulations
 Given the volume of data that was in the orginal dataset, 5.72 million rows, we decided to condense it to roughly 700,000 rows, excluding all data that was retrieved before Jan 1, 2020.  This allowed us to provide a more in-depth analysis of the arrests that occurred during and after the COVID-19 pandemic. In addition to this, the data in the chart’s were grouped based on similar arrest descriptions to remove clutter in the visualizations and make the data easier to comprehend.
