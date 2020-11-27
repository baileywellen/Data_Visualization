# Class Objectives - Descriptions, Photos, and Links   
      
## <a id = "obj_1"> </a>Objective 1  
**Install and Run Tableau: Install Tableau Desktop and be able to create, open, save, and share a workbook.**  
In Tableau Lab 1, I loaded the data in, made a simple visual out of it (sum of sales by category) and saved the workbook.  

![Lab 1 - Simple Graph](./images/Lab1_image.PNG)  

[Download Lab 1](./tableau_workbooks/Lab1.twbx)  

## <a id = "obj_2"> </a>Objective 2  
**Add data to Tableau workbook: Bring a variety of data sources into Tableau and utilize basic data processing in Tableau**  
In Tableau Lab 2, I loaded data into Tableau and created an inner join on the data. This allowed me to pull the two tables -- Dealers and Transactions -- together to display more comprehensive graphs.  
  
![Lab 2 - Connecting Data Sources](./images/Lab2_Data.PNG)  
[Download Lab 2](./tableau_workbooks/Lab2.twbx) 

## <a id = "obj_3"> </a>Objective 3  
**Create basic visualizations: Use Tableau to create a variety of visualizations as appropriate to for the data being used.**  
In Tableau Lab 3, I used a [police fatal shootings dataset](https://www.kaggle.com/andrewmvd/police-deadly-force-usage-us?select=fatal-police-shootings-data.csv) from Kaggle. This data includes demographic information about the victim (race, gender, age, mental illnesses, etc) as well as information about the shooting (did the victim have a weapon, was the officer wearing a body cam, etc). I thought that the victim's race and what weapon they had would be interesting, so I created visualizations below to clearly display this information. 
  
![Lab 3 - Visualizations](./images/Lab3_Race.PNG)  
![Lab 3 - Visualizations](./images/Lab3_Weapons.PNG)  
[Download Lab 3](./tableau_workbooks/Lab3.twbx)  


## <a id = "obj_4"> </a>Objective 4  
**Perform calculations in Tableau: Calculate fields and create functions in Tableau**  
For this lab, I used data on [CO2 Emissions by state](https://www.eia.gov/environment/emissions/state/) from the U.S. Energy Information Administration. Because CO2 stays in the environment for a long period of time, it makes the most sense to compare cumulative emissions by state. In the image below, I show the calculation that I created (sum of CO2 Emissions by State from 2010 to 2017), and a glimpse at a possible graph that we can make to compare emissions by state over the last 7 years.  
   
![Lab 4 - Calculations](./images/Lab4_Calculations.PNG)  
[Download Lab 4 ("CO2_Emissions_byState.twbx") ](./tableau_workbooks/CO2_Emissions_byState.twbx)  

## <a id = "obj_5"> </a>Objective 5  
**Work with tables in Tableau: Be able to create and process table calculations in Tableau**  
For this lab, I created a parameter called "Years to Show" and a related Calculated Field called "ShareLabels" which only displays the first n years of data, where n is equal to "Years to Show". I added a slider to the first graph (shown below) which allows the user to change the Years to Show parameter and choose how many data points she or he wants to view. In the following three worksheets, I did further analysis to determine which regions and which departments needed the most attention. You can see my rationale [in this document](./documents/Lab5_Description.pdf) , but my analysis leads me to believe that Departments G and H of the Western Division and Department F of the Midwestern division need the most attention.    
  
![Lab 5 - Table Calculations](./images/Lab5_Calc.PNG)  

[Download Lab 5](./tableau_workbooks/Lab5.twbx)  
 
## <a id = "obj_6"> </a>Objective 6  
**Create maps in Tableau: Use Tableau to do basic geospatial analysis.**  
My work for this lab shows the Average AQI by month in 2019, with a slider to choose a specific month or all months. I made sure to set the legend/color scheme to a static range so that it does not change as we change the filter. If the scale were to change at each month, I don’t believe this interactive display would show any valuable information. However, with a static range, this worksheet shows how the air quality of the United States changes throughout the calendar year. It also shows how individual states compare to those around them and whether they follow trends throughout the year, which could help us find the right questions to ask for further analysis. This information about how air quality changes over space and time could be valuable, and is best displayed through a map like this one.  
![Lab 6 - Mapping](./images/Lab6_AQI.twbx)  
[Download Lab6](./tableau_workbooks/Lab6.twbx) or [Read the Description](./documents/Lab6_Description.pdf)

## <a id = "obj_7"> </a>Objective 7
**Mapping with ArcGIS online: Use the online version of ESRI's ArcGIS for basic geospatial processing.**  
In the maps below, I display the mean Air Quality Index (AQI) in the United States for March-May 2019 with March-May 2020. In ArcGIS, I interpolated this data across the United States to estimate what the air quality is in between the observations points that we have.  

[See my Air Quality Map Online](https://arcg.is/1rHu98)   
**Spring 2019 AQI:**  
[2019 AQI](./images/AQI_Spring_2019.png)  
**Spring 2020 AQI:**  
[2020 AQI](./images/AQI_Spring_2020.png)  

## <a id = "obj_8"> </a>Objective 8  
**Do statistical analysis in Tableau: Use Tableau for basic statistical analysis**      
In the first tab (Square Feet Confidence Interval), I see that the average square feet for houses with attached garages is much higher than square feet for houses with detached or no garage. This offers a possible reason why houses with attached garages had a higher sold price, and confirms our hunch that there were confounding factors behind our previous graph.

In addition, we see some counties which would likely have a small p value if we ran a significance test - notably, Milwaukee and Ozaukee are outside of the confidence interval for attached garages; Kenosha, Racine, and Walworth are out of the confidence interval for detached; and Washington is well above the confidence interval for the no garage category. The 95% confidence interval tool in Tableau helps us to visualize and estimate a significance test.  

Another feature of this workbook is that we can filter by year - using this capability, we can see whether some counties may differ from the mean in one year and not the others, or compare how the distance from the mean of individual counties may change year to year. Below is a picture of this workbook with all years (2005 - 2010) selected.  

![Lab 8 - Statistics](./images/Lab8_Stats.PNG)  
[Download Lab8](./tableau_workbooks/Lab8.twbx)  

## <a id = "obj_9"> </a>Objective 9  
Create Interactive Dashboards: Use Tableau to create a dashboard.      
[Download Lab 9](./tableau_workbooks/Lab9.twbx)    

## <a id = "obj_10"> </a>Objective 10  
Publish data visualizations with Tableau: Use Tableau to make visualizations available to the public      
None so far  

## <a id = "obj_11"> </a>Objective 11  
Clean and prepare data for Tableau: Clean and combine data in Tableau to prepare it for analysis. This will include some basic database concepts      
[See in class workbook](./tableau_workbooks/InClass9-28.twbx)  

## <a id = "obj_12"> </a>Objective 12
Using alternate tools: Everything that we do can be done with other software. Demonstrate that by using both Tableau and another tool to produce/process the same visualization (Due to T6-Alt, ArcGIS online is NOT eligible for this objective).       
[See Lab7 - "fatal-police-shootings.xlsx"](./documents/fatal-police-shootings.xlsx)  

## <a id = "obj_13"> </a>Objective 13  
Demonstrate an understanding of data context.  
Final Project - "Has Air Quality Improved since the COVID-19 Pandemic?"  
[Watch my Project Presentation on Youtube](https://youtu.be/pEjmn405S2U)  
[Download Final Project Tableau File 1](./tableau_workbooks/Final_Project.twbx)  
[Download Final Project Tableau File 2](./tableau_workbooks/Final_Joined.twbx)  

## <a id = "obj_14"> </a>Objective 14  
Choose an appropriate and effective visual   
![Image of Effective Visual](./images/AQI_Effective_Visual.PNG)  
*See Final Project in Objective 13*   

## <a id = "obj_15"> </a>Objective 15  
Minimize clutter and focus the audience attention.  
![Image of Minimizing Clutter](./images/AQI_Minimize_Clutter.PNG)  
*See Final Project in Objective 13*     

## <a id = "obj_16"> </a>Objective 16   
Apply elements of design to visualization.  
*See Final Project in Objective 13*   
 
## <a id = "obj_17"> </a>Objective 17  
Create a data-based story.  
None so far 
