# oibsip_task2
# Project Description
The aim of this data analytics project is to perform customer behavior analysis for an e commerce company. By analyzing customer behavior and purchase patterns, the goal is to understand customer behavior. This analysis can inform targeted marketing strategies, improve customer satisfaction, and enhance overall business strategies

# Customer Behavior Analysis Project

This project provides a comprehensive analysis of consumer behavior using a rich dataset comprising demographics, purchasing habits, engagement patterns, and decision-making factors. It is aimed at uncovering insights that can support better marketing strategies, improve customer engagement, and inform data-driven business decisions.

---

## Dataset Overview

The dataset includes 1,000 entries with the following types of data:

- **Demographics**: Age, Gender, Income Level, Marital Status, Education Level, Occupation, Location.
- **Purchase Behavior**: Purchase Amount, Frequency of Purchase, Purchase Channel, Product Category.
- **Engagement & Loyalty**: Brand Loyalty, Customer Satisfaction, Engagement with Ads, Loyalty Program Membership.
- **Influencing Factors**: Social Media Influence, Discount Sensitivity, Return Rate, Purchase Intent.
- **Technology & Preferences**: Device Used for Shopping, Payment Method, Shipping Preference.
- **Temporal Factors**: Time Spent on Research, Time to Decision, and Time of Purchase.

---

## Libraries Used

- `pandas`: Data manipulation and exploration
- `numpy`: Numerical operations
- `matplotlib`: Static data visualizations
- `seaborn`: Enhanced statistical visualizations
- `datetime`: Handling date/time data

---

## Data Cleaning & Preprocessing

Key cleaning steps included:

- **Conversion of Data Types**:
  - `Purchase_Amount`: Converted from object to float
  - `Time_of_Purchase`: Converted from object to datetime
- **Handling Missing Values**:
  - Identified and inspected missing or improperly formatted values
  - Ensured categorical "None" values weren't treated as null (`NaN`)
- **Standardization**:
  - Stripped currency symbols and commas from monetary fields
  - Verified consistency in categorical fields (e.g., case sensitivity, whitespace)

---

## Descriptive Analysis & Visualizations

Several visualizations created to uncover behavioral patterns and trends:

### Age Distribution
Histogram and boxplot visualizing the age range and identifying potential outliers.

### Purchase Category
Bar chart displaying the **Top 10 Product Categories** based on frequency of purchase.

### Social Media Influence
Count plot illustrating the levels of influence social media has on customer purchasing decisions.

### Engagement with Ads
Count plot showing how actively customers engage with advertisements (None, Low, Medium, High).

### Discount Sensitivity
Pie chart showing the proportion of customers under each discount sensitivity level, annotated with average purchase amount per group.

---

## Insights & Recommendations

Based on the analysis, here are some key takeaways:

- **Age Group Behavior**: Younger consumers tend to engage more with ads and social media, while older customers show higher brand loyalty and satisfaction.
- **Purchase Channel Preferences**: A balanced mix of online and in-store purchases exists, suggesting multi-channel strategies should be maintained.
- **Social Media & Ad Engagement**: High social media influence correlates with higher ad engagement, indicating potential for targeted digital marketing.
- **Product Categories**: Some categories dominate in frequency, offering opportunities for product bundling and promotional focus.
- **Discount Sensitivity**: A significant portion of customers are deal-driven, reinforcing the value of promotional strategies and loyalty programs.

---
