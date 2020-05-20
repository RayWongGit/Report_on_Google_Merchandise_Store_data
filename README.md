### Introduction

In this project, we analyze the Google Merchandise Store data and then generate a dashboard for our insights. 

### Project Strcture

#### Part One: Use Advanced Displays, Create Segments & Apply View Settings

**A. Primary Views**

An industry best practice is to ensure that there are three different views for whatever property we are working in:

- unfiltered (all the data, never mess with it)
- test (where you can try things out before making them live)
- working (where you’ll implement your work once it’s been tested and it’s getting the results you want) 

**B. Filter**

Another industry best practice is to make sure that the property we’re working in is excluding internal traffic in at least one of its views (ideally, the Production view or a copy of it.)

**C. Data Exploration**

Using the best practices above, explore the following GA Reporting Areas: 

Audience, Acquisition, Behavior, & Conversion. 

**D. Segmentation**

Using the technique of segmentation, we are able to anser more specific questions. In this part we create 3 new segmentations below:

One based on audience characteristic (such as technology or demographics)
One based on geography
One based on user behavior

#### Part Two: Creating Custom Reports, Dashboards, and Custom Alerts
In this part we generate dashboards in Data Studio to present the insights we found.

We connect to the Google Analytics and build the dashboard on the Master View.

The dashboard contains charts below:

- A Time Series chart: configured to show unique pageviews, sessions, and users.
- A Pie chart: configured to show revenue, broken down by product categories. 
- Another Pie chart: configured to show what sources are driving new users to the site.
- Scorecard: configured to display average order value.
- A Date Range Control that governs all of the charts, set to the range of August 1st-September 5th, 2018.


### Tools

- Google Analytics - Demon account
- Data Studio