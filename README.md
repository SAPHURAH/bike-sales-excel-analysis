#  Bike Sales Analysis Dashboard — Excel

##  Project Overview

This project analyzes customer purchasing behavior using Microsoft Excel. The goal was to identify patterns and factors associated with bicycle purchases and transform the findings into an interactive dashboard that can support business decision-making.

The analysis covers customer demographics, income, education, occupation, commute distance, region, age, and other characteristics to understand which customer groups are more likely to purchase a bike.

This project demonstrates a complete data-analysis workflow, from data cleaning and transformation to exploratory analysis, pivot tables, visualization, and dashboard development.

---

##  Objectives

The main objectives of this project were to:

* Analyze customer demographics and purchasing behavior.
* Identify characteristics associated with bike purchases.
* Compare customers who purchased bikes with those who did not.
* Examine the relationship between income and bike purchasing.
* Analyze purchasing patterns across age groups, regions, occupations, and commute distances.
* Build an interactive Excel dashboard to communicate the findings clearly.
* Generate business insights that could support customer targeting and marketing decisions.

---

##  Tools & Technologies

* **Microsoft Excel**
* Pivot Tables
* Pivot Charts
* Excel formulas
* Data cleaning and transformation
* Data visualization
* Dashboard design
* Exploratory Data Analysis (EDA)

---

##  Dataset

The dataset contains customer information related to bicycle purchasing behavior.

The original dataset contains approximately 1,000 usable customer records and includes variables such as:

* Customer ID
* Marital Status
* Gender
* Income
* Number of Children
* Education
* Occupation
* Home Ownership
* Number of Cars
* Commute Distance
* Region
* Age
* Purchased Bike

The target variable is **Purchased Bike**, which indicates whether a customer purchased a bike.

---

##  Data Preparation

Before conducting the analysis, the data was prepared and transformed in Excel.

The main preparation steps included:

1. Reviewing the original dataset for consistency.
2. Creating a working sheet for analysis.
3. Converting abbreviated categorical values into more descriptive labels.

   * `M` → `Married`
   * `S` → `Single`
   * `F` → `Female`
   * `M` → `Male`
4. Creating an **Age Bracket** variable to group customers into:

   * Adolescent
   * Middle Age
   * Old
5. Checking the structure and consistency of the data.
6. Creating pivot tables to summarize purchasing behavior.
7. Developing charts and an interactive dashboard from the analysis.

---

##  Analysis Performed

The analysis investigated bike purchases across several customer characteristics.

### Income

Customers who purchased bikes had a higher average income than customers who did not.

| Customer Group      | Average Income |
| ------------------- | -------------: |
| Purchased Bike: Yes |        $52,055 |
| Purchased Bike: No  |        $45,479 |
| Overall Average     |        $48,767 |

This suggests that income may be associated with a customer's likelihood of purchasing a bike.

### Age

Age was grouped into three categories.

| Age Group  | Purchased | Total | Purchase Rate |
| ---------- | --------: | ----: | ------------: |
| Adolescent |        39 |   110 |         35.5% |
| Middle Age |       383 |   701 |         54.6% |
| Old        |        59 |   189 |         31.2% |

The middle-aged group had the strongest purchasing behavior in the dataset.

### Commute Distance

Customers with shorter commute distances generally showed stronger purchasing behavior.

The 0–1 mile group recorded the highest number of purchases, with **200 purchases**, while customers commuting more than 10 miles recorded only **33 purchases**.

### Region

The Pacific region had the strongest bike-purchase rate.

| Region        | Purchased | Total | Purchase Rate |
| ------------- | --------: | ----: | ------------: |
| Europe        |       148 |   300 |         49.3% |
| North America |       220 |   508 |         43.3% |
| Pacific       |       113 |   192 |         58.9% |

### Education

Customers with a Bachelor's degree recorded the highest number of purchases among the education categories, with **169 purchases**.

### Occupation

Professional customers recorded the highest number of bike purchases among the occupation groups, with **150 purchases**.

---

##  Key Insights

The analysis revealed several notable patterns:

1. **Income appears to be an important factor.** Customers who purchased bikes had a higher average income than those who did not.

2. **Middle-aged customers were the strongest customer segment**, accounting for the highest purchase rate among the age groups analyzed.

3. **Shorter commute distances were associated with stronger purchasing behavior**, particularly among customers commuting 0–1 miles.

4. **The Pacific region had the highest purchase rate**, suggesting that regional factors may influence customer demand.

5. **Customers with Bachelor's degrees formed a significant purchasing segment.**

6. **Professional workers recorded the highest number of purchases among occupations.**

7. **Gender differences were relatively small**, suggesting that bike marketing should not rely heavily on gender alone for customer targeting.

---

##  Dashboard

The final Excel dashboard summarizes the analysis using charts and interactive filtering.

The dashboard allows users to explore purchasing behavior and compare customer groups across different demographic and behavioral characteristics.

### Dashboard Components

The dashboard presents visual analysis of factors including:

* Income
* Gender
* Age
* Age Bracket
* Commute Distance
* Region
* Education
* Occupation
* Bike Purchase Status

---

##  Business Recommendations

Based on the analysis, businesses selling bicycles could consider the following strategies:

### 1. Target middle-aged customers

Middle-aged customers demonstrated the strongest purchasing behavior and could be an important target market.

### 2. Develop income-based marketing strategies

Customers with higher average incomes showed stronger purchasing behavior. Premium or higher-value bicycle products could therefore be targeted toward higher-income segments.

### 3. Focus on short-distance commuters

Customers with shorter commute distances showed relatively strong purchase behavior. Marketing campaigns could emphasize bicycles as convenient transportation for short commutes.

### 4. Investigate regional opportunities

The Pacific region recorded the highest purchase rate. Businesses could investigate whether this market has stronger demand and consider increasing marketing activity there.

### 5. Target professional customers

Professional workers recorded the highest number of purchases among occupations, making them another potentially valuable customer segment.

---

##  Project Structure

```text
bike-sales-excel-analysis/
│
├── README.md
│
├── data/
│   └── Excel_Project_Dataset.xlsx
│
├── dashboard/
│   └── Bike_Sales_Dashboard.png
│
└── documentation/
    └── Project_Analysis_Notes.md
```

---

##  Skills Demonstrated

This project demonstrates practical experience in:

* Data cleaning
* Data transformation
* Exploratory data analysis
* Excel formulas
* Pivot Tables
* Pivot Charts
* Dashboard development
* Data visualization
* Business analysis
* Insight generation
* Communicating data-driven findings

---

##  Conclusion

This project demonstrates how Excel can be used to transform raw customer data into meaningful business insights.

Through data cleaning, transformation, pivot-table analysis, visualization, and dashboard development, the project identified customer segments and behavioral patterns associated with bicycle purchases.

The analysis provides a foundation for businesses to better understand their customers and develop more targeted marketing strategies.


