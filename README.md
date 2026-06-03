# NYC Yellow Taxi Trip Data Analysis
##Project Overview: 
This project analyzes taxi trip data to uncover traffic congestion patterns and customer demand trends. The focus is on identifying which days of the week experience the most traffic, and understanding why short trips consume more duration despite low distance

---

## Project Objective:
1.   Analyze demand patterns in NYC taxi trips by day and hour to identify peak travel times and commuter behavior.
2.  Evaluate revenue trends through fare distribution, average trip costs, and detection of pricing outliers.
3.  Assess customer behavior by examining payment method preferences, trip durations, and distance–fare relationships.
4.  Perform data cleaning and feature engineering to ensure accuracy, consistency, and create new insights (e.g., trip duration, pickup hour).
5.  Communicate findings with interactive visualizations and actionable insights that demonstrate business impact and technical proficiency.

---

## Data Source:
1. Source - Dataset collected from NYC Government Portal
2. Link - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Location - New York City ( USA )
3. Year / Timeline - January 2026

---

## Tools & Technologies:
Python-Google Colab 
Libraries Used: 
•	NumPy 
•	pandas 
Visualization Libraries 
•	matplotlib.pyplot 
•	seaborn 
•	plotly.express 
Searching text patterns 
•	re 
Ignore warnings 
•	warnings

---
## Dataset Feature:

<img width="438" height="455" alt="image" src="https://github.com/user-attachments/assets/76b15322-7011-498b-8fef-a4d0241ddd53" />

---

## Data Pre-Processing and Cleaning:
To ensure accuracy and consistency in the taxi trip dataset, the following steps were performed:
1.	Handling Missing Values
o	Detected nulls in trip distance, duration, and payment type.
o	Applied median/mode imputation for numeric and categorical fields.
o	Dropped rows with critical missing data (pickup/dropoff times, fare, tip).
2.	Duplicate Removal
o	Identified duplicate records using duplicated() checks.
o	Removed redundant entries to avoid skewed demand counts.
3.	Data Formatting
o	Converted trip distance and duration into numeric formats.
o	Standardized categorical labels (e.g., payment types, gender, sentiment).
o	Corrected unrealistic values (negative fares, zero duration trips).
4.	Feature Cleaning & Engineering
o	Extracted pickup day and pickup hour from timestamps.
o	Created trip category (short ≤ 2 miles vs long > 2 miles).
o	Derived traffic indicator (duration vs distance ratio).
o	Added hashtag count / sentiment cleaning for text fields (if applicable).
5.	Outlier Handling
o	Removed trips with extreme distances or durations beyond realistic thresholds.
o	Applied log transformation to normalize skewed metrics (optional).

---

## Visualizations

Box plots, bar charts, line graphs, heatmaps, violin plots, pair plots.

Interactive dashboards (Plotly/Streamlit).

---

## Key Insights
Demand Patterns:

Peak demand during weekday rush hours and Saturday evenings.

Lowest demand in early mornings and Sundays.

Fare Behavior:

Median fares stable across weekdays, dip slightly on weekends.

Cash payments dominate, but prepaid cards show structured commuter usage.

Traffic Congestion:

Short trips take longer midweek due to congestion.

Weekend trips are faster, reflecting lighter traffic.

Revenue Drivers:

Longer trips contribute disproportionately to revenue.

Tips correlate more strongly with total fare than distance.

---

## Outcome
This project demonstrates:

Data wrangling and preprocessing for large datasets.

Exploratory and statistical analysis to validate insights.

Business‑oriented storytelling through visualizations.

Recruiter‑friendly documentation showcasing applied data analyst skills.

---

 ## Future Work
Build predictive models for fare estimation.

Apply clustering to identify customer segments.

Extend dashboard with real‑time traffic integration.

---

## Conclusion
This project serves as a comprehensive demonstration of the end-to-end data science lifecycle, applied to over 3.7 million NYC taxi trips from January 2026. By moving through the four pillars of analytics—Descriptive, Diagnostic, Predictive, and Prescriptive—we have transformed raw transactional logs into a strategic roadmap for operational improvement.

## Author
**Mr. Aswin M S**

**Data Analyst**
