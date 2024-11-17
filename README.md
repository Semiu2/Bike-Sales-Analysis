# Bike-Sales-Analysis
## Project Objective
The objective of this project is to analyze historical bike sales data from 2020 to 2024 to identify key trends, customer demographics, payment preferences, and store performance. This analysis aims to uncover actionable insights to optimize revenue, improve sales strategies, and enhance overall business performance.

## Data Source
<a https://www.kaggle.com/datasets/jayavarman/bike-sales-data-of-100k

## Time Period:
Data spans from 2020 to 2024


### Key Metrics:
- Annual and monthly Revenue
- Sales by Age, Gender and Location
- Performance of salespersons and store


## Data Processing
Steps taken to clean and prepare the data for analysis:

### Data Cleaning:

- Checked and removed Duplicate values
- Categorized age groups into predefined brackets (adolescent, Middle age and Old) using nested If function =IF(K3>55,"Old",IF(K3>=31,"Middle Age",IF(K3<31,"Adolescent","Invalid")))
- Extraction of month and year from Date column using the Text function.
- Created the Revenue column

## Key Findings

### Revenue:
Total revenue has seen steady growth from 2020 to 2023, peaking at $165.6M in 2022.
A sharp decline to $120.6M in 2024 suggests external market pressures or operational inefficiencies.
Stable Revenue: Between 2020 and 2023, the revenue remained consistent, with minor fluctuations (+1.24% in 2022 and -0.64% in 2023).
- Significant Decline in 2024: Revenue dropped by 26.68% in 2024, contributing only 15.5% to the total revenue.
- Highest Revenue Year: 2022 had the highest revenue ($165,560,749).
- Overall Contribution: Each year contributed approximately 21% to the grand total, except 2024, which saw a sharp decline.

### Customer Demographics:
Middle-aged customers dominate sales, contributing 47,046 units, far exceeding adolescent and older customer brackets.
Gender distribution is balanced, with female customers purchasing slightly more bikes (50,227) compared to males (49,773).
### Payment Preferences:
Cash, Credit Card, and Apple Pay are the most used payment methods, while Google Pay and PayPal have minimal adoption. Diversifying payment incentives could expand customer flexibility.
### Sales Performance by Salesperson:
The top salesperson (ID: 422) achieved 143 sales, significantly outperforming others.
Other salespersons show marginal differences, indicating the potential for overall skill enhancement.
### Store Performance:
Stores in New York and Houston generate the highest average revenue at $7,826 and $7,805, respectively.
San Antonio lags behind with the lowest average revenue of $7,696, signaling opportunities for targeted improvements.

## Key Recommendations

### Revenue Recovery:
Investigate factors contributing to the revenue decline in 2024 and implement customer retention strategies like discounts, loyalty programs, or new product lines.
### Customer Targeting:
Focus on marketing campaigns for middle-aged customers, while introducing affordable options for adolescents to expand the customer base.
### Payment Method Optimization:
Promote and incentivize Google Pay and PayPal usage to encourage digital adoption.
### Salesforce Improvement:
Train underperforming sales staff using techniques from top-performing salespeople (e.g., ID: 422).
Regularly monitor and reward top-performing employees to sustain high productivity.
### Location-Based Strategies:
Study high-performing locations (New York, Houston) to replicate successful strategies in lower-performing locations like San Antonio.




