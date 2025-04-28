# KNL Absenteeism Analytics Dashboard


## Problem Statement

This dashboard helps the organisation to analyze their employee absent rate through a one year period. It shows what categories of employees have higher reliability, the distribution of absent rates across employees of various cities, departments, division, store location and business units. It gives an overview of what aspect to look into to investigate further as to why certain groups are more efficient than some others. Since by using this dashboard, the problem has been identified, factors reponsible can be further spotted more definitely with additional information.

## Tools and Methodology
### Tools : 
Power Query: This was used for data cleaning, standardization and validation.

DAX: This was used to generate calculated measures required to properly identify relationships between variables.

Power BI: Interactive dashboard creation and visualization

### Methodology:
Data cleaning/Standardization/validation: A thorough data cleaning process was carried out on the data set. This includes removing of duplicates, data standardization through the entire dataset. Details of all data cleaning process was documented appropriately.

Exploratory data analysis: DAX was used to create calculated measures which where neccessary to aggregate and meaningfully show relationship between variables.

Visualization: A two page interactive dashboard was built to clearly answer possible stakeholder's questions.

## Dashboards

Page 1 link: (https://github.com/BlessedOnothoja/KNL-HR-analytics/blob/e70cf8bf2c2a49d99f96e2b9c3c01f83944176b3/Absenteeism%20page1.jpg)

Page 2 link:(https://github.com/BlessedOnothoja/KNL-HR-analytics/blob/e70cf8bf2c2a49d99f96e2b9c3c01f83944176b3/Absenteeism%20Page2.jpg)
 





## Insights

A single page report was created on Power BI Desktop.

The following inferences can be drawn from the dashboard;

### [1] Total Number of Employees = 8,336

   Number of Male Employees = 4,216 (50.58%)

   Number of Female Employees = 4,120 (49.42%)

   
The 40-49 age bin has the largest proportion of employees (3,189) compared to the other age bins. In this group, there are 1,611 males and 1,578 female employees.


           thus, though the difference between the proportion of male to female employees is not very significant, it is clear that this organization have more males than female employees.

           Overall,though the male employees are more than the females, Average absent hours from the female employees(78hrs) outweighs that from the male employees(67hrs). More information is needed to determine further the reason for this difference.
           
### [2] Average Absent hours and Age Groups

 The average absent hours differs amongst employees of different age groups. While the 70-79 age group with the lowest proportion of employee(26 employees) have a high average absent houurs of 193hrs, age group 40-49 with the largest proportion of employee was significantly lower (68hrs).

 There were 101 employees below the 20 age group. None of this employees had a record of absent through the one year analysis period.






    We may want to look into age related illnesses as possible reason for the high rate of absence among the 70-79 age group, however, more information is required to ascertain this. Furthermore, drawing inference from this analysis, the age group below 20 are the most reliable group in this workforce.
  
 
  
  The dashboard display will change on application of different filters. To return back to status quo, simply hold Gtrl and click on the Reset arrow on the bottom left of the dashboard.  
  



 
  
  ### [3] Average Absent hours and departments
  

Though Customer service department had the highest number of employees(1,737 employees), Recruitment department(whose employee count is not part of the top 5) topped the list in terms of average absent hours.

      A survey can be carried out to further investigate what kind of absent hours employees request for in other to understand the distribution more clearly.

 
 ### [4] Average absent hours across Organization's Division
 
 Apart from the age group below 20, the stores division recorded absent hours across employees of everyother age group. 

Both in Stores and in the entire Division,these absent hours tend to decline significantly as the age group moves towards the younger employees. Employees of 70-79 have average absent hours of 193.22hrs, those of 60-69 recorded 159.40hrs, those of 50-59 recorded 108.54hrs, those of 40-49 recorded 68.86hrs, those of 30-39 recorded 25.34hrs, those of 20-29 recorded 3.46hrs, those of below 20 recorded 0hrs.
 
 
 
         thus, the younger employees tends to have a higher tendency to be more efficient than the older ones.

### [5] Location analysis

The largest proportion of the organization's employees is in Vaucouver. Vaucouver hold 21.4% workforce of the entire organization, followed by Victoria which only hold 8.3% of the workforce.

None of the top 15 countries(in terms of workforce volume) are part of the top 10 countries with the highest absenteeism count.

Wyndel which had the highest average absent hours on the record has only 7 employees, while Blue Rivers which follows Wyndel closely on this chart, has only 2 employees.

                There is no direct proportionality between staff volume and high absenteeism. While the data set does not contain enough information to evidence the reason while the smaller stations are more prone to absenteeism, we may infere that there may be possible poor working conditions in this locations.


 
 
## Conclusion/Recommendations
- From the analysis, it is clear that younger employees are more reliable than the older ones. The organization should encourage and streamline HR process to bring in more younger employees.

- A survey should be used to understand the distribution of individual employees perculiar situation and how the absent rate can be effectively managed to maintain organization's productivity.

- Smaller cities should be investigated to understand their working conditions and ways in which they can be assisted to be more stable.
- Further investigation should be carried out to understand the perculiarities of female employees and why they are more absent than their male counterparts.

Power BI Visualization:https://github.com/BlessedOnothoja/KNL-HR-analytics
