# Earned-Salaries-Compared-to-their-Tenure-in-Baltimore-City

Using open data from Open Baltimore to predict the annual earned salary based on the tenure in Excel
## Background
With the data from [Open Baltimore](https://data.baltimorecity.gov/), I tried to predict the annual salary by regressing the annual earned salary over the tenure in Baltimore City. 

Open Baltimore contains salary data for each officers working in the government. For each individual, there is name, job titile, department, identifier, hired data, annual salary, gross salary.

## Approach
I calculated the tenure for each individuals based on their employed date. I built regression model for health department and the general services department. The predication for general services department is better than that for health department.

The reasons why that happpened is probaly the wide range of job positions in the health department made it difficult to find a good fit.

## Conclusion
The chart below shows the relationship between the tenure and annual earned salary for health department:

![alt text](https://github.com/lshan6/Baltimore-Health-Dept.-Earned-Salaries-Compared-to-their-Tenure-in-Baltimore-City-/blob/master/baltimore%20city.PNG)

The chart below shows the relationship between the tenure and annual earned salary for General Services department:

![alt text](https://github.com/lshan6/Baltimore-Health-Dept.-Earned-Salaries-Compared-to-their-Tenure-in-Baltimore-City-/blob/master/generalservices.PNG)
