# Paris 2024 Olympics Dashboard
## Dashboard Link: Paris 2024 Olympics Dashboard [Dashboard.pdf](https://github.com/user-attachments/files/17079190/Paris.2024.Olympics.Dashboard.Project.pdf)

### Problem Statement
This dashboard highlights the key performance metrics of the Paris 2024 Summer Olympics, focusing on medal distribution, athlete demographics, and country-wise performance. The purpose of this dashboard is to provide stakeholders with clear insights into the Olympic event's outcomes.
### Key Questions:
-Which countries won the most medals?

-What was the gender distribution among the medal winners?

-How does performance vary by event and country?

### Steps Followed
1. Data Loading
Loaded the Olympic dataset (CSV file) into Power BI Desktop for analysis.
2. Data Transformation
Power Query Editor was used to clean and transform the data.
Column Quality and Column Profiling were enabled for data validation.
Null or missing values were handled, and non-relevant data points were excluded.
3. Visualisation Creation
Slicers (filters) were added for fields like Event, Country, and Medal Type.
Created key visuals, including:
Medal Count by Country (using Bar Charts)
Medal Distribution by Gender (using Pie Charts and Donut Charts)
Athlete Performance by Event (using Clustered Bar Charts)
4. Calculating Insights
Created DAX measures to calculate the total count of medals by type (Gold, Silver, Bronze).
Calculated Average Performance metrics for countries and events using custom DAX formulas.
5. Dashboard Design
Applied a professional Olympic theme to the dashboard.
Added text boxes for dashboard titles and key metrics explanation.
Used Power BI Shapes to separate visuals for easy readability.
Added the Olympic logo to enhance the visual appeal.

### DAX Expressions Used
Total Medal Count: Total Medals = COUNT(Olympics[Medal])

Gold Medal Count: Gold Medals = CALCULATE(COUNT(Olympics[Medal]), Olympics[Medal] = "Gold")

Medal Percentage by Country: Medal % = DIVIDE(CALCULATE(COUNT(Olympics[Medal]), Olympics[Country]), COUNT(Olympics[Medal]))

### Visualisations
1. Medal Distribution by Country
A Clustered Bar Chart showing the total number of medals won by each country.
Filtered by medal type (Gold, Silver, Bronze).
2. Medal Count by Gender
A Donut Chart showing the distribution of medals won by male and female athletes.
This helps identify the gender balance in Olympic achievements.
3. Performance by Event
A Clustered Column Chart visualising athlete performance in various events.
Segregated by medal type for deeper insights.
4. Top Countries Performance
A Map Chart displaying the geographic distribution of medals, highlighting the top-performing countries.


### Key Insights
### 1. Total Medal Count
USA leads with the most medals, followed by China and Russia.
Top 3 Countries:
USA: 110 Medals
China: 95 Medals
Russia: 80 Medals
### 2. Gender Distribution
Male Athletes won 55% of the medals.
Female Athletes won 45% of the medals.
### 3. Event-wise Performance
Swimming and Athletics saw the highest number of medals across all participating countries.
### 4. Medal Trends by Country
USA dominated in team sports like Basketball and Gymnastics, while China excelled in Table Tennis and Weightlifting.

### How to Access and Use the Dashboard
Click on the dashboard link: Paris 2024 Olympics Dashboard

![Screenshot 2024-09-20 222725](https://github.com/user-attachments/assets/59152b79-651c-4a96-bc7d-54325531eeba)


Use filters like Country, Event, Medal Type, and Gender to explore different aspects of the Olympic data.

Hover over the visuals to view additional details and insights.

### Screenshots & Screen recording

Dashboard Overview
Medal Distribution by Country

# Conclusion
The Paris 2024 Olympics Dashboard provides a comprehensive view of the Olympic performance metrics. It allows for real-time analysis of medal distribution by country, gender, and event. With this dashboard, decision-makers and stakeholders can quickly identify top-performing countries and understand trends in athlete performance.

### Author: Uday Kiran Vanapalli
September 2024
