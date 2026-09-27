<img width="2400" height="480" alt="Banner" src="https://github.com/user-attachments/assets/89b016a8-a683-44bb-b868-c042adb6a947" />
 
# Retail Sales & Customer Analytics Dashboard-Going Beyond Numbers

##  1.Overview & Aim
My aim was to go beyond simply creating charts and KPIs. I wanted to explore how I could create a traditional sales dashboard in Excel environment which could include more of the retail and customer experience, not just the numbers.

Many dashboards focus on presenting sales, profit and trends, but I wanted to add another layer by looking at the story behind those results. That meant combining sales performance with customer feedback and using the dashboard to answer questions, highlight patterns and add more context to what the numbers were showing.

By bringing the retail and survey data together, I was able to look at sales, profit, customer behaviour and customer experience in one place and explore the data from both a commercial and customer perspective.

As a summary, I have looked at monthly and yearly sales performance, profitability of products, product segment analysis, geographic performance and customer experience insights.
________________________________________
##  2.Dataset
###  a.Dataset
The main retail dataset contains more than 50,000 transaction-level records and is a well-known data source for retail sales analysis. The dataset details can be found in references.

b.Customer Survey Database
A separate customer database was created for approximately 795 customers.
The database contains survey-based customer experience measures including:
Measure	Description
Shipment Speed Score	Customer rating of delivery/shipment speed
Product Quality / Experience Score	Customer perception of product quality
Service Experience Score	Customer rating of service
Product Range	Customer opinion of the available product range
Store Accessibility	Customer rating of accessibility
Overall Score	Average customer experience score
Experience Level	Customer experience classification
Strongest Area	Highest-rated aspect of the experience
Weakest Area	Lowest-rated aspect of the experience
Preferred Ship Mode	Customer shipping preference

I also created additional calculated fields where required to support the analysis, including year and week information. Moreover, an “Overall Experience Score” was calculated using the survey measures. I also assigned customers to experience groups: Poor, Fair, Good, and Excellent. This customer database was then connected to the retail dataset using Customer ID as the primary key.
________________________________________
## 3.Business Questions 
1. How is the business performing overall?
2. How is performance changing over time?
3. Which product categories are driving sales?
4. Which products are performing strongly, and which are underperforming?
5. Where are sales happening?
6.What are Customer Experience Survey showing us?
7.Does Experience Level influence sales?
8.Are loyalty orders growing?
________________________________________
## 4.Features

### a.KPIS
Most dashboards present headline figures such as Total Sales or Total Profit and then move straight on to the next chart. But in a real business environment, managers rarely look at those numbers in isolation. They are also asking: “What was the target?” “How close are we to it? “Are we ahead or behind?” “And how much is left to achieve?

Because of that, each KPI in my dashboard was designed to include more context around performance. Alongside the actual result, I included the relevant target, and an indication of how far the business was from reaching it.

This makes the KPI section less about simply reporting what has happened and more about showing performance against expectations, which is much closer to how these numbers would be viewed in a real retail environment.

### b.Dynamic Geographic Map
A dynamic geographic section was developed to analyse quantity and sales performance across different countries and regions. Supporting lookup formulas and region classifications were used to prepare the information required by the map. I also added a dropdown menu so users can easily switch between continents and explore the geographic data without having to adjust the map manually.

### c. Digital Clock
One of the VBA features I added was a live digital clock within the dashboard. This was an idea that came later in the project, and I discovered that it could be created in Excel environment. Please find the link for it below and I also added the YouTube link below for people who would like to do that in their projects

### d.Slide Bar
I also enhanced the dashboard with an interactive navigation banner, using a YouTube tutorial as a starting point and adapting the design and functionality.

### e.Other Techniques
I built the project in Microsoft Excel, using a mix of Excel Tables, PivotTables, PivotCharts, slicers, formulas, VBA, macros, geographic visualisations and custom KPI dashboard displays. In addition, I used Power Query to help clean, transform, merge the datasets and prepare the final data before building the analysis and dashboard, which made the workflow more structured and easier to manage.
________________________________________
## 5.Key Findings from the Project
The main goal of this project was to show the analytical process, not to force a final business recommendation. Even so, the dashboard highlighted several useful patterns in the data.
________________________________________
#### a.Sales Show Consistent Growth with Clear Seasonal Peaks
The data shows year-on-year sales growth across all four years. Monthly sales naturally fluctuate, but there is a general upward trend as each year progresses.

From a retail perspective, this pattern makes sense. Sales tend to build around key promotional and seasonal periods, while events such as Halloween and Christmas are expected to create stronger peaks toward the end of the year.

Seeing these seasonal peaks reflected in the data was a positive sign that the sales pattern followed what we would normally expect in a retail environment.
________________________________________
### b.Technology Leads Sales Across the Four-Year Period
Technology clearly stood out as the strongest category in the dataset over the span of four years. The dashboard alone does not tell us exactly why it performed better, but it gives me a good starting point for further questions around demand, pricing, promotions, or marketing activity. Maybe the business practices in this product segment could be applied to other segments to drive sales forward.
________________________________________
### c.Customer Experience Highlights Clear Strengths and Areas for Improvement
Our combined data from the Customer Database and Dataset shows that customers are appreciating the Product Range and Product Quality/Experience, giving them high scores. However, Store Accessibility and Service Experience scored below the overall average.

Store accessibility is difficult for a business to fix in the short term, as relocation can be a costly endeavour. Service experience, however, could be improved more quickly through better service quality, clearer procedures, improved tools, and other operational improvements.
________________________________________
### d.Loyalty Orders Show Consistent Growth
Loyalty orders are growing across all four customer groups, which is a positive sign. Gold customers stand out the most, with the highest number of orders each year, while the other groups also display steady growth over time.

What I’d take from this is that loyalty programs seem to be encouraging repeat purchases and the gold customers are clearly the most engaged group and worth looking at more closely.
________________________________________
### e.Customer satisfaction and sales should be viewed together carefully
One finding that stood out was that higher customer experience scores did not always mean higher sales. Looking at the charts, spending stays relatively similar across some of the experience groups rather than increasing as satisfaction improves.

The second chart looks at how total revenue of sales is distributed across the different customer experience groups such as Poor, Fair, Good and Excellent. The Fair group accounts for the largest share of revenue across the customer segments, showing that the customers generating the most sales were not necessarily those with the highest experience ratings.
________________________________________
## 6.Skills Demonstrated
I believe that below skills are used while creating the dashboard;
•	Data Analysis
•	Retail Analytics
•	Customer Analytics
•	Power Query
•	Excel Dashboard Development
•	Data Visualisation
•	KPI Reporting
•	Customer Segmentation
•	Data Modelling
•	Business Analysis
•	VBA
•	Problem Solving
•	Self-directed Learning
________________________________________
## 7.Conclusion
I enjoyed building this dashboard because it let me look beyond sales figures and explore what customers were experiencing too. It also reminded me that a chart can raise useful questions, even when it doesn’t give a clear answer on its own.

## References
# Link to SideBar Tutorial
https://www.youtube.com/watch?v=fJ7-7irXah8&t=14s
# Link to Dataset :
https://www.kaggle.com/datasets/vivek468/superstore-dataset-final
# Link to Digital Clock Tutorial
https://www.youtube.com/watch?v=Gx3W4o9lPbg

Feel free to reach me at; Linkedin:www.linkedin.com/in/alp-tuna

My Website:https://alptheanalyst.wixsite.com/alptuna

My E-Mail:alptuna.professional@gmail.com
