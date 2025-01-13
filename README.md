# British Airways Review Dashboard

# Project Overview
British Airways, one of the most recognized airlines, is it truly great? This project aims to analyze customer reviews of British Airways using publicly available data. The primary objective is to extract meaningful insights and present them in an interactive Tableau dashboard. The dataset includes customer feedback on various aspects such as overall rating, cabin staff service, entertainment, food, ground service, seat comfort, and value for money.

## Objectives
1. To visualize customer ratings and identify trends over time.
2. To compare ratings across different aircraft types and countries.
3. To provide insights into specific metrics such as entertainment, food, and cabin staff service.
4. To support decision-making by highlighting key areas for improvement.

## Dashboard
<a href="https://public.tableau.com/app/profile/advait.athalye/viz/BritishAirwaysReview_17365784653580/Dashboard1">
<a href="https://github.com/advaitathalye/British-Airways-Data-Analysis-Dashboard/blob/main/Tableau%20dashboard.PNG">

## Questions Answered
1. How has the overall customer rating changed over time?
2. Which countries report the highest and lowest ratings?
3. What are the differences in ratings across various aircraft types?
4. How do specific metrics such as cabin staff service or food compare to the overall rating?

## Datasets
The project utilizes two datasets:
1. <a href="https://github.com/advaitathalye/British-Airways-Data-Analysis-Dashboard/blob/main/ba_reviews.csv"> BA reviews </a>
    Contains customer reviews and ratings from March 2016 to October 2023.
2. <a href="https://github.com/advaitathalye/British-Airways-Data-Analysis-Dashboard/blob/main/Countries.csv"> Countries </a>
    Provides geographical data for mapping country-level insights.

## Process Description
### Data Cleaning
Handling Missing Values: Removed or imputed missing values in columns critical to the analysis, such as overall rating and specific metrics.
Standardization: Ensured consistency in column names and data types across the datasets.
Merging Datasets: Combined the `ba_reviews` and `Countries` datasets to enable geographical analysis.

### Data Visualization
 Created an interactive Tableau dashboard with key visualizations:
  - Time Series Analysis: Displayed the trend of average overall rating by month.
  - Geographical Analysis: Visualized average ratings by country on a map.
  - Aircraft Comparison: Compared ratings across different aircraft types.
  - Metric Selector: Enabled users to filter by specific metrics such as cabin staff service or entertainment.

### Filters/Parameters
The dashboard includes the following filters and parameters to enhance interactivity and allow users to explore the data:
Metric Selector: Allows users to choose a specific metric (e.g., overall rating, cabin staff service, food) to focus on.
Month of Date: Filters data by month, enabling time-based trend analysis.
Traveller Type: Segments data by traveler categories, such as business or leisure travelers.
Seat Type: Filters reviews based on seat categories (e.g., economy, business class).
Type of Aircraft: Allows comparison of ratings across various aircraft models, such as A319, A320, and Boeing 747.

## Key Visualizations
1. Average Overall Rating by Month:
   Displays trends over time, highlighting periods of high and low customer satisfaction.
2. Average Overall Rating by Country:
   Shows geographical differences in customer satisfaction.
3. Average Overall Rating by Aircraft:
   Compares customer experience across different aircraft types.
4. Interactive Metric Selector:
    Allows users to focus on specific aspects such as food or seat comfort.

## Metrics
Overall Rating: Average customer satisfaction score.
Cabin Staff Service: Ratings for crew performance.
Entertainment: Feedback on in-flight entertainment.
Food and Beverages: Ratings for meals and drinks provided.
Ground Service: Evaluation of airport services.
Seat Comfort: Feedback on seating.
Value for Money: Customer perception of the ticket cost versus the service provided.

## Repository Structure
```
British-Airways-Dashboard/
├── README.md: Project documentation
├── ba_reviews.csv: Review dataset
├── Countries.csv: Country data
├── Dashboard.twbx: Tableau workbook file
└── Images: Screenshots of key visualizations
```

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/British-Airways-Dashboard.git
   ```
2. Open `British Airways Review.twbx` in Tableau to explore the interactive dashboard.
3. View the insights directly from the provided visualizations.

## Conclusion
This project provides actionable insights into customer satisfaction trends for British Airways. The visualizations help identify areas needing improvement and support data-driven decision-making.
