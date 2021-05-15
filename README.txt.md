# CIS 9440 Project - NYC Canine Waste Bag Dispensers
- author(s): Vivian Chen, Jason Chin
- date created: 5/13/2021
- class: CIS 9440

Project Objective: Follow the Kimball Lifecycle to design and develop a public, cloud-based Data Warehouse with a functioning BI Applications

Project Tools:
The tools used to build this Data Warehouse were: (change this to make applicable to your project)
1. For data integration - Excel (Power Query)
2. For data warehousing - Google BigQuery
3. For Business Intelligence - Tableau

## Kimball Lifecycle Project Stages

### Project Planning

Motivation for project:
NYC has a large dog population, and dog waste in public areas has always been an issue. Unremoved waste in public areas result in a $250 dollar fine in NYC. 
This project hopes to distribute canine waste bag dispensers appropriately throughout the city to reduce unremoved canine waste. We envision that our audience 
will notice a significant difference when comparing areas already with canine waste bag dispensers to areas without. From there, they can identify other areas 
with high incidents of uncleaned waste, and decide on whether or not that area would be a good place to place a waste bag dispenser. Overall, we think that 
this can alleviate some of the city’s problems with canine waste and promote an effective use of city resources.


Description of the issues or opportunities the project will address:

Issue: 
1.NYC 311 Canine Waste Requests

Opportunities: 
1.Visualize the benefits of canine waste bag dispensers.
2.Identify areas where canine waste bag dispensers can be installed strategicallly, to reduce service calls, increase sanitation, and save city resources.


Project Business or Organization Value:
Save city resources concerning canine waste issues and promote a more sanitary NYC.

Data Sources:
1.Canine Waste Dispensers: https://data.cityofnewyork.us/Recreation/Canine-Waste-Dispensers/5npv-j6gn

2.NYC Dog Licensing: https://data.cityofnewyork.us/Health/NYC-Dog-Licensing-Dataset/nu7n-tubp

3.311 Service Requests: https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9
...

### Business Requirements Definition

List of Data Warehouse KPI's:
1.Number of waste bag dispensers / zip code
2.Number of dog licenses / zip code
3.Number of canine violations / zip code
4.Number of dog licenses issued / year
5.Total service requests / total dog licenses by zip code
6.Total service requests / year
7.Total waste bag dispensers installed / year
...

### Dimensional Model

This project's Dimensional Model consists of (3) Facts and (2) Dimensions

![Dimensional Model](/img/dimensional_model.JPG)

This project's Kimball Bus Matrix:

![Kimball Bus Matrix](/img/kimball_bus_matrix.JPG)

### Business Intelligence Design and Development

List of Visualizations for each KPI:

1.Number of waste bag dispensers / zip code:
We used a map to visualize this so that the user can easily see which 
parts of New York have waste bag dispensers, as well as the number of 
waste bag dispensers in comparison to other zip codes.

2.Number of dog licenses / zip code:
We used a map to visualize this so that the user can easily see which 
parts of New York have dog licenses, as well as the number of dog 
licenses in comparison to other zip codes.

3.Number of canine violations / zip code:
We used a map to visualize this so that the user can easily see which 
parts of New York have canine violations, as well as the number of canine 
violations in comparison to other zip codes.

4.Number of dog licenses issued / year:
We used a bar graph to visualize this because a bar graph makes it easy 
to compare numbers between a few years.

5.Total service requests / total dog licenses by zip code:
We used a line chart to visualize this so that the user can see the trend 
throughout the years.

6.Total service requests / year: We used a bar graph to visualize this because a bar graph makes it easy 
to compare numbers between a few years.

7.Total waste bag dispensers installed / year:
We used a line chart to visualize this so that the user can see the trend 
throughout the years.
...

BI Application Wireframe design:

![Wireframe Design](/img/wireframe_design.JPG)

Picture of final Dashboard:


![Dashboard](/img/Dashboard.JPG)

### Deployment

The project was deployed on Tableau Public: 
https://public.tableau.com/profile/jason.chin4507#!/vizhome/WasteDispensersDogLicensesand311CanineRequestsinNYC/ProjectDashboard?publish=yes

