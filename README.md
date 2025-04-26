# KNL Limited HR Analytics Dashboard


## Problem Statement

This dashboard helps the organisation to analyze their employee absent rate through a one year period. It shows what categories of employees have higher reliability, the distribution of absent rates across employees of various cities, departments, division, store location and business units. It gives an overview of what aspect to look into to investigate further as to why certain groups are more efficient than some others. Since by using this dashboard, the problem has been identified, factors reponsible can be further spotted more definitely with additional information.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is an Excel file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Merge First name and Last name column to form a single column called "Employee Name".
- Step 5 : Group age into age bins using conditional column in power query editor

     Image description: (https://github.com/user-attachments/assets/da665bdb-01cd-49ae-b9a6-5701cd8958b9)

- Step 6 : A dashboard template was created on power point and imported into Power BI to house the elements of the analysis.
- Step 7 : Visual filters (Slicers) were added for six fields named "City", "Division", "Business unit", "Store Location", "Department", & "Job Title".
- Step 8 : Six card visuals were added to the canvas, total employees, average absent hours, total job title, total cities, total departments and average length of service.        
- Step 9 : Clustered bar chart visuals where used to show employee distribution over different age bins, average absent hours across the different age bins, top 5 departments with the highest employee count and top 5 departments with the highest average absent hours record. 
- Step 10 : A donut chart visual was used to show gender distribution across employees. 
- Step 11 : A matrix visual was used to show absence distribution over different age bins and division. Conditional formatting was used to spotlight the distribution of absent hours through these segments. Colors with the highest absent hours are darker, those with lower absent hours are lighter.

 
 # Report Snapshot (Power BI DESKTOP)


Link: (https://github.com/BlessedOnothoja/KNL-HR-analytics/blob/0b558eb2ba50f94af3ce388da99b4d239bbbc8fb/KNLHRDashboard.jpg)




# Insights

A single page report was created on Power BI Desktop.

The following inferences can be drawn from the dashboard;

### [1] Total Number of Employees = 8,336

   Number of Male Employees = 4,216 (50.58%)

   Number of Female Employees = 4,120 (49.42%)

   
The 40-49 age bin has the largest proportion of employees (3,189) compared to the other age bins. In this group, there are 1,611 males and 1,578 female employees.


           thus, though the difference between the proportion of male to female employee is not very significant, it is clear that this organization have more males than female employees.

           Overall,though the male employees are more than the females, Average absent hours from the female employees(78hrs) outweighs that from the male employees(67hrs). More information is needed to determine further the reason for this difference.
           
### [2] Average Absent hours and Age Groups

 The average absent hours differs amongst employees of different age groups. While the 70-79 age group with the lowest proportion of employee(26 employees) have a high average absent houurs of 193hrs, age group 40-49 with the largest proportion of employee was significantly lower (68hrs).

 There were 101 employees below the 20 age group. None of this employees had a record of absent through the one year analysis period.






    We may want to look into age related illnesses as possible reason for the high rate of absence among the 70-79 age group, however, more infromation is required to ascertain this. Furthermore, drawing inference from this analysis, the age group below 20 are the most reliable group in this workforce.
  
 
  
  The dashboard display will change on application of different filters. To return back to status quo, simply hold Gtrl and click on the Reset arrow on the bottom left of the dashboard.  
  



 
  
  ### [3] Average Absent hours and departments
  

Though Customer service department had the highest number of employees(1,737 employees), Recruitment department(whose employee count is not part of the top 5) topped the list in terms of average absent hours.

      A survey can be carried out to further investigate what kind of absent hours employees request for in other to understand the distribution more clearly.

 
 ### [4] Average absent hours across Organization's Division
 
 Apart from the age group below 20, the stores division recorded absent hours across employees of everyother age group. 

Both in Stores and in the entire Division,these absent hours tend to decline significantly as the age group moves towards the younger employees. Employees of 70-79 have average absent hours of 193.22hrs, those of 60-69 recorded 159.40hrs, those of 50-59 recorded 108.54hrs, those of 40-49 recorded 68.86hrs, those of 30-39 recorded 25.34hrs, those of 20-29 recorded 3.46hrs, those of below 20 recorded 0hrs.
 
 
 
         thus, the younger employees tends to have a higher tendency to be more efficient than the older ones.
 
 
# KNL HR Analytics-Dashboard.md.txt
Displaying # KNL HR Analytics-Dashboard.md.txt.
