# Fintech Product Analytics: User Engagement, Retention & Feature Adoption

## Project Overview

This project analyzes user behavior and product performance using event-level data from a fintech platform. The analysis focuses on user engagement, revenue performance, customer retention, and feature adoption to identify opportunities for improving the product experience and conversion.

Using Python and Pandas, the project calculates key product metrics and compares customer behavior across different periods and segments.

## Business Objectives

- Measure monthly and daily active users.
- Analyze revenue performance using ARPU and Average Order Value (AOV).
- Monitor purchase conversion and order frequency.
- Evaluate 30-day and 90-day customer retention.
- Compare retention across registration cohorts and customer segments.
- Measure search feature adoption and its relationship with conversion.
- Evaluate conversion among users who interact with the promotional page.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Key Analyses

### 1. User Engagement

Calculate Monthly Active Users (MAU) and Daily Active Users (DAU) to understand activity patterns over time.

### 2. Revenue & Conversion Metrics

Calculate key metrics, including:

- **Active Users:** Distinct users recorded in the event dataset.
- **Unique Purchasers:** Distinct users associated with a booking.
- **Conversion Rate:** Unique purchasers divided by active users.
- **Total Revenue:** Sum of recorded sales amounts.
- **ARPU:** Total revenue divided by active users.
- **AOV:** Total revenue divided by unique bookings.
- **Order Frequency:** Unique bookings divided by unique purchasers.

### 3. Customer Retention

Measure 30-day and 90-day retention based on whether customers return as active users after registration. The analysis also compares retention by registration cohort, gender, and device type.

### 4. Cohort Analysis

Group users by registration month and compare their retention performance over the observation period.

### 5. Feature Adoption

Calculate search feature adoption rates overall and by month to understand how widely the feature is used.

### 6. Feature Adoption & Conversion

Compare 30-day booking conversion between users who use search and users who do not. A similar comparison is performed for promotional-page interaction.

These comparisons describe observed associations and do not establish that feature usage causes higher conversion.

## Key Findings

The notebook's recorded interpretation reports the following:

- The dataset contains **1,499 active users** across the 2019 observation period.
- Average monthly active users are **688.25**.
- Among the selected January–September registration cohorts, **308 of 470 users** returned within 30 days, while **354 of 470 users** returned within 90 days.
- The notebook reports approximately **43% conversion** among search users and **19% conversion** among users who did not use search, based on its stated comparison.

These findings should be validated against the final notebook outputs before being used for business decisions. The final promotional-page comparison and its uplift values should also be reviewed before reporting conclusions.

## Business Recommendations

- Monitor MAU and DAU to identify changes in user engagement.
- Investigate factors associated with 30-day and 90-day retention.
- Compare retention across registration cohorts and device types.
- Evaluate whether search and promotional-page experiences are associated with higher booking conversion.
- Use controlled experiments to assess whether product changes improve conversion or retention.

## Limitations

- The dataset covers January through December 2019.
- The retention definition measures recorded activity, not necessarily a completed purchase.
- Feature adoption and conversion comparisons are observational and may be affected by differences between user groups.
- Revenue metrics depend on the meaning and granularity of the source `sales_amount` and `booking_id` fields.
- The analysis does not by itself establish causal relationships.

## Author

**Risty Anugrah Dwi Septiana**

Informatics Engineering Graduate | Data Analyst Enthusiast

- GitHub: [Ristyanugrah](https://github.com/Ristyanugrah)
- Portfolio: [Data Analytics Portfolio](https://github.com/Ristyanugrah/data-analytics-portfolio)
