# Starbucks Nutrition Insights Dashboard | Power BI



## Project Overview



This project presents an interactive Power BI dashboard that analyses the nutritional profile of Starbucks beverages. The dashboard helps users compare drinks based on calories, caffeine, carbohydrates, protein, saturated fat, cholesterol, sodium, vitamins, minerals, and dairy/non-dairy options.



The project is designed as a real-world consumer analytics dashboard. It supports healthier beverage choices for health-conscious customers, lactose-intolerant consumers, and anyone who wants to compare nutritional trade-offs before choosing a Starbucks drink.



## Business Problem



Starbucks offers a wide range of beverages across different categories, preparation styles, and milk options. For customers, it can be difficult to quickly identify which drinks are higher in calories, caffeine, carbohydrates, saturated fat, or cholesterol.



This dashboard aims to answer practical consumer questions such as:



- Which beverage categories contain the highest caffeine?

- Which drinks are heavier in calories and carbohydrates?

- How are beverages distributed across dairy, non-dairy, and other options?

- What is the relationship between saturated fat and cholesterol?

- Which drinks may be more suitable for health-conscious or lactose-intolerant consumers?



## Tools Used



- Power BI Desktop

- Power Query

- Microsoft Excel

- Data cleaning and transformation

- Data modelling

- Interactive dashboard design

- Business intelligence reporting



## Dataset



The dataset contains nutritional information for Starbucks beverages, including:



- Beverage category

- Beverage name

- Milk type

- Calories

- Total carbohydrates

- Total fat

- Saturated fat

- Cholesterol

- Protein

- Caffeine

- Sodium

- Vitamins and minerals



## Data Preparation



The dataset was cleaned and transformed in Power Query before building the dashboard. Column names were standardised, numeric columns were converted into the correct data types, missing values were handled, and duplicate records were removed where necessary.



Additional restructuring was completed to support better filtering and analysis. A dairy classification was created to group beverages into Dairy, Non-Dairy, and Other categories. This helped make the dashboard easier to use and allowed nutritional comparisons from a consumer health perspective.



## Dashboard Preview



!\[Dashboard Overview](images/overview.png)



## Key Dashboard Visuals



### Beverage by Dairy Category



This treemap shows how Starbucks beverages are distributed across Dairy, Non-Dairy, and Other categories. It highlights the variety of milk-based and non-dairy drink options available to customers.



!\[Beverage by Dairy Category](images/beverage-by-dairy-category.png)



### Caffeine by Beverage Category



This visual compares average caffeine levels across beverage categories. Coffee-based drinks show the highest caffeine levels, while smoothies and some blended drinks contain much lower caffeine.



!\[Caffeine by Beverage Category](images/caffeine-by-beverage-category.png)



### Calories and Carbohydrates by Beverage Category



This chart compares average calories and carbohydrates across beverage categories. Frappuccino and smoothie categories generally show higher calorie and carbohydrate values compared with lighter options such as coffee and tea-based drinks.



!\[Calories and Carbohydrates by Beverage Category](images/calories-and-carb-by-beverage-category.png)



### Saturated Fat and Cholesterol by Beverage Category



This scatter plot explores the relationship between saturated fat and cholesterol across beverages. Milk-heavy drinks generally show higher fat and cholesterol values, while lighter beverage options are positioned lower.



images/saturated-fat-and-cholesterol-by-beverage -category.png



## Key Insights



- Coffee-based beverages have the highest average caffeine levels.

- Frappuccino and smoothie categories generally contain higher calories and carbohydrates.

- Dairy-based beverages are more strongly associated with saturated fat and cholesterol.

- Non-dairy options provide useful alternatives for lactose-intolerant or health-conscious customers.

- Simple drinks such as brewed coffee and tea are generally lighter choices compared with milk-heavy or blended beverages.

- The dashboard allows users to compare drinks interactively using beverage category, beverage name, and dairy category filters.






## Repository Structure

```text
starbucks-nutrition-powerbi-dashboard/
│
├── README.md
├── data/
│   └── starbucks.xlsx
├── dashboard/
│   └── Starbucks_Nutrition_Dashboard.pbix
├── reports/
│   └── Starbucks_Nutrition_Insights_Business_Report.pdf
└── images/
    ├── overview.png
    ├── beverage-by-dairy-category.png
    ├── caffeine-by-beverage-category.png
    ├── calories-and-carb-by-beverage-category.png
    └── saturated-fat-and-cholesterol-by-beverage-category.png
```



## Project Outcome



This project demonstrates how Power BI can transform raw nutritional data into a clear and interactive dashboard. It shows practical skills in data cleaning, data transformation, dashboard design, business storytelling, and insight generation.



The final dashboard can help consumers make more informed Starbucks beverage choices based on nutrition, caffeine preference, and dairy suitability.







