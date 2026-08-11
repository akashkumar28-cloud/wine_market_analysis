
# 🍷 Wine Market Analysis

## 1. Project Title 
### 🍷 Wine Market Analysis: Global Wine Insights Dashboard

  An interactive Power BI dashboard designed to analyze global wine markets, pricing, ratings, wine varieties, countries, wineries, and value-for-money              opportunities.

 ## 2. Short Description 
 
   The Wine Market Analysis Dashboard is a visually engaging and analytical Power BI report designed to help users explore and compare over 130K wines across 44      countries and 708 varieties. The dashboard focuses on highlighting data-driven insights into global wine pricing, ratings, varieties, countries, and wineries.     It helps identify market trends, premium and luxury wine segments, highly rated wines, and value-for-money opportunities and data-driven strategists who seek      to understand trends and characteristics of wine market globally.

  ## 3. Tech Stack
  #  🛠️ Technologies & Tools
   #### The project was developed using the following tools and technologies:

* 📗 Microsoft Excel – Used for initial data cleaning, missing-value treatment, duplicate removal, and data preparation.
* 🐘 PostgreSQL – Used to store and manage the cleaned wine dataset.
* 🗄️ SQL – Used for data exploration, business analysis, aggregations, filtering, sorting, and deriving analytical insights.
* 🔄 Power Query – Used for data transformation, cleaning, and preparation within Power BI.
* 📊 Power BI Desktop – Used to create interactive dashboards and visualizations.
* 🧮 DAX (Data Analysis Expressions) – Used to create calculated measures, calculated columns, KPIs, price segments, rating categories, and value analysis.
* 📈 Data Visualization – Used charts, cards, slicers, maps, tables, and other visuals to communicate insights.
* 📁 File Format – .pbix for development and .png for dashboard previews.
* 🐙 Git & GitHub – Used for project version control, documentation, and portfolio presentation.

  ## 4. 📂 Data Source: GV Cloud Secure (Internship Project)

   The dataset was provided during my internship at GV Cloud Secure and contains wine-level information covering wines from multiple countries, wineries,             varieties, regions, prices, and ratings. The dataset includes attributes such as country, winery, variety, province, region, designation, price, points, title.    The data was cleaned and transformed to handle missing values, remove duplicates, standardize categorical fields, and create analytical fields such as **Price     Category, Rating Category, and Value Score**. The prepared dataset was subsequently analyzed using **PostgreSQL and SQL** and visualized through an                interactive **Power BI dashboard**.
   **Note:** The original dataset was provided as part of an internship project and is not publicly included in this repository due to data confidentiality.

  ## 5. 📊 Highlights

  ####  Business Problem

   The organization lacks clarity on the key factors influencing wine ratings and whether higher prices are justified by perceived quality. With a diverse wine       portfolio spanning multiple countries, regions, varieties, and price segments, it is difficult to identify which products and markets perform best and where       pricing opportunities exist.

   The organization needs to understand the relationship between price and perceived quality, identify high-performing countries, regions, and varieties, evaluate    quality-to-price value, and detect potentially overpriced or underpriced products.

   Without these insights, the organization may face inconsistent pricing strategies, inefficient product positioning, and missed opportunities to strengthen its     wine portfolio.

 #### Goal of the Dashboard

   The goal of the dashboard is to provide an interactive analytical solution that helps the organization evaluate wine quality, pricing, regional performance,       variety performance, and product value.

 ##### The dashboard enables decision-makers to:

  * Evaluate the relationship between price and wine ratings.
  * Identify high-performing countries and regions.
  * Discover high-value wine varieties.
  * Detect potentially overpriced and underpriced products.
  * Compare Budget, Mid-Range, Premium, and Luxury segments.
  * Identify opportunities to improve product positioning and portfolio strategy.
    
   This project transforms the raw wine dataset into an interactive analytical solution that helps answer key business questions around pricing, quality, market      performance, and value.

 ## Does higher price guarantee better quality?

   Higher price does not guarantee better quality. The analysis shows a moderate positive relationship between price and rating (correlation ≈ 0.40). Although        Luxury wines have the highest average rating, moderately priced wines can also achieve strong ratings, demonstrating that price alone is not a reliable            indicator of wine quality.
   The average rating does increase across price segments:

Price Segment     	 Avg. Price	                Avg. Rating
  Budget	             $15.07	                      86.58
Mid-Range	             $32.10	                      88.91
 Premium	             $69.02	                      91.05
  Luxury	             $184.82	                    92.82

   So, more expensive wines tend to receive higher ratings on average, but the relationship is not strong enough to say that price guarantees quality.

   #### 📊 Walkthrough of Key Visuals

    #### 📌 KPI Cards
     Provides a high-level overview of total wines, average price, average rating, countries, wineries, varieties.

    #### 🌎 Country Analysis
     Compares wine production, average price, average rating, and Value Score across countries.

    #### 🏭 Winery Analysis
     Identifies top-performing wineries based on ratings, pricing, and value.

    #### 🍇 Variety Analysis
     Highlights highly rated grape varieties and varieties offering strong quality-to-price performance.

    #### 💰 Price Analysis
     Segments wines into Budget, Mid-Range, Premium, and Luxury categories to analyze pricing patterns.

    #### ⭐ Rating Analysis
     Compares wine quality across countries, wineries, varieties, and price category.

    #### 💡 Value Analysis
     Uses Value Score to identify wines that provide relatively high ratings compared with their prices.

    #### 🚨 Price-Rating Outlier Analysis
     Highlights potentially overpriced wines (high price + low rating) and potentially underpriced/value wines (low price + high rating).

    ### 💼 Business Impact & Insights

    * **Consumer Decision Making:** Identify highly rated wines at affordable prices.
    * **Pricing Strategy:** Evaluate whether wine prices are supported by ratings.
    * **Winery Performance:** Compare wineries based on quality, price, and value.
    * **Market Analysis:** Compare wine markets across countries and regions.
    * **Premium Market Strategy:** Identify opportunities in Premium and Luxury segments.
    * **Value Identification:** Find wines offering strong value for money.

    ## 6. 📊 Screenshots

    ### Executive Overview
    ![Executive Overview](./page%201.png)

    ### Price vs Rating
    ![Price vs Rating](./page%202.png)

    ### Regional Analysis
    ![Regional Analysis](./page%203.png)

    ### Variety Analysis
    ![Variety Analysis](./page%204.png)

    ### Value Analysis
    ![Value Analysis](./page%205.png)
    

  
