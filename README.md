# -NG30DAYSOFLEARNING_CAPSTONE_PROJECT

# INTRODUCTION/BACKGROUND
This project is for the #NG30DAYSOFLEARNING.
 Airplane Crashes and Fatalities Since 1908 (Full history of airplane crashes throughout the world, from 1908-present)
At the time this Dataset was created in Kaggle (2016-09-09), the original version was hosted by Open Data by Socrata at the at: https://opendata.socrata.com/Government/Airplane-Crashes-and-Fatalities-Since-1908/q2te-8cvq, but unfortunately that is not available anymore. The dataset contains data of airplane accidents involving civil, commercial and military transport worldwide from 1908-09-17 to 2009-06-08.

![Screenshot (244)](https://user-images.githubusercontent.com/107101960/178094902-a1e2c90b-eb45-463c-bb20-6bee7ca78d4e.png)

# Questions i ask myself/Objective:
* Yearly how many planes crashed?

* How many people were on board? 

* How many survived? how many died?


* Highest number of crashes by operator and Type of aircrafts.




# Prepare phase
 Data Sourcing:https://www.kaggle.com/datasets/saurograndi/airplane-crashes-since-1908


Data licence:http://opendatacommons.org/licenses/odbl/1.0/


# TOOLS:Excel for data cleaning , powerbi for data vizualisation and story telling

# Process/Transformation:
Raw data(EXCEL)
![Screenshot (229)](https://user-images.githubusercontent.com/107101960/177220559-49240700-01da-4306-b62b-fea536343599.png)
* I changed the date format using "text to column", because i discovered my date is in text form

 I Formatted the date to derive;
* the year(excel)

* the month(excel)

* Days of the week(excel0

* I deleted missing data, replaced the text with unknown and numbers with zero(powerbi)

* I deleted cn/in and registeration column

* I split the text to column BY delimeter as in the location column to derive the country
![Screenshot (245)](https://user-images.githubusercontent.com/107101960/178096280-e623f738-4a3a-4f05-8491-e88e10035135.png)



# ANALYSIS
 * I Created a column for fatality rate using dax in powerbi
 * i also created a column for those that survived
 
 
 
 
 
 # FINDINGS
 
 * The first recorded plane crash in human hsitory was in 1908 by type Flyer wright iii
 * Japan has the highest death as country from plane crash with 520 deaths in the year 1985
 * Russia has the highest cummulative fatalities from plane crash with 6.6k deaths
 * Boeing B-747-SR46 Recorded the highest death as an airplane in the year 1985
 * Douglas DC-3 recorded the highest cumulative fatalities with 4793 fatalities
 * Aeropilot has an operator   recorded the highest cummulative fatalities with over 70000 fatalities
 * The year 1972 recorded the highest fatalities with 2973 fatalities with 3965 aboard
 * Tenrife-Las

 
 
 

 




