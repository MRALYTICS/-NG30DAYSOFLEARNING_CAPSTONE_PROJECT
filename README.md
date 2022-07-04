# -NG30DAYSOFLEARNING_CAPSTONE_PROJECT

# INTRODUCTION/BACKGROUND
This project is for the #NG30DAYSOFLEARNING.
 Airplane Crashes and Fatalities Since 1908 (Full history of airplane crashes throughout the world, from 1908-present)
At the time this Dataset was created in Kaggle (2016-09-09), the original version was hosted by Open Data by Socrata at the at: https://opendata.socrata.com/Government/Airplane-Crashes-and-Fatalities-Since-1908/q2te-8cvq, but unfortunately that is not available anymore. The dataset contains data of airplane accidents involving civil, commercial and military transport worldwide from 1908-09-17 to 2009-06-08.


![image](https://user-images.githubusercontent.com/107101960/177205801-3c026c2c-857c-4c40-aa5b-349551a82c9b.png)

# Questions i ask myself/Objective:
Yearly how many planes crashed? how many people were on board? how many survived? how many died?
Highest number of crashes by operator and Type of aircrafts.
‘Summary’ field has the details about the crashes. Find the reasons of the crash and categorize them in different clusters i.e Fire, shot down, weather (for the ‘Blanks’ in the data category can be UNKNOWN) you are open to make clusters of your choice but they should not exceed 7.
Find the number of crashed aircrafts and number of deaths against each category from above step.
Find any interesting trends/behaviors that you encounter when you analyze the dataset.

# Prepare phase

# Data Sourcing:https://www.kaggle.com/datasets/saurograndi/airplane-crashes-since-1908
# Data licence:http://opendatacommons.org/licenses/odbl/1.0/
# TOOLS:Excel for data cleaning , powerbi for data vizualisation and story telling

# Process/Transformation:
Raw data
![Screenshot (229)](https://user-images.githubusercontent.com/107101960/177220559-49240700-01da-4306-b62b-fea536343599.png)
I changed the date format using "text to column" because i discovered my date is in text form
I deleted missing data
![Screenshot (230)](https://user-images.githubusercontent.com/107101960/177220972-814ad1f8-12a2-433f-b9f3-a73a228a0106.png)
I also removed the Time column because i found the column wasnt completee
i created a worksheet for military helicopter casualty
I removed the groung column because its not needed in my analyses

