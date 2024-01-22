## Healthcare Dashboard
 [Please click here to view the dashboard](https://app.powerbi.com/view?r=eyJrIjoiMmYwY2EyYmMtMDI1My00ZjkzLWEwMzYtOTc0NjMzNTFiZjQwIiwidCI6IjQ0MGFiNGIyLTE2YzMtNGQ3Yi04NjZkLTdlZWY4YmFmY2Y3MCJ9)
 <br />
**Generated Data:** Please note that the data used in this project has been randomly generated, and the distribution may not accurately mirror actual scenarios. 
<br />
**Dashboard Overview:**
•	The dashboard contains two report pages – one dedicated for financials and another for patient satisfaction analysis.
<br />
•	In the Financials report, the MTD/YTD buttons can be used to switch data between Month-to-Date (MTD) and Year-to-Date (YTD) in all visualizations, except the Net Income Trend chart.
<br />
•	In the Patient Satisfaction report page, the NPS gauge chart is designed to dynamically change colors based on the NPS score for the chosen filter selections.
<br />
o	Color Logic:
	Red: NPS less than 0
	Yellow: NPS between 0 and the goal value
	Green: NPS greater than or equal to the goal value

### Data Model
Please note that I have added all the columns used in the dashboard and excluded some which are not used (but available in the data files) to keep the ERD simple. 
![JK Clinics Data Model](https://github.com/JK15/Healthcare_Dashboard_PowerBI/blob/main/JK%20Clinics%20Data%20Model.png)

### DAX Expressions
The following document contains all the DAX expressions used in the dashboard including measures (*DAX Measures* tab), calculated columns and calculated table (*DAX Calculated Columns|Table* tab). 
<br />
[DAX Expressions](https://github.com/JK15/Healthcare_Dashboard_PowerBI/blob/main/DAX%20Expressions.xlsx)

### Dashboard Screenshots
Financials dashboard
![Financials Dashboard](https://github.com/JK15/Healthcare_Dashboard_PowerBI/blob/main/Financial%20Dashboard.png)
Patient Satisfaction Dashboard
![Patient Satisfaction Report](https://github.com/JK15/Healthcare_Dashboard_PowerBI/blob/main/Patient%20Satisfaction%20Dashboard.png)

### OneDrive link to access the Power BI(.pbix) file
!(https://1drv.ms/f/s!AmieWPzQY7Kji1aPH9hYORGi8l1R?e=bjWMXd)

### Opportunities for Improvement
The current dashboards show only a fraction (less than 10%) of insights that can be derived from a healthcare clinic establishment. There is a significant opportunity to enhance these dashboards providing a complete picture of the various functions within the business. The following improvements would aid the decision-makers in making informed decisions to improve care quality, financial performance, and the satisfaction of both staff and patients.
1.	Refining the data model - Adding more detailed data to the existing model such as treatment specifics, schedules, resource availability
2.	Additional dashboards for deeper analysis – Building new dashboard for providing insights into doctor performance, the effectiveness of various treatment options, insurance claim details. 
3.	An overview dashboard for executives – Creating an high-level dashboard that offers a bird’s eye view of the activities across different functions.
