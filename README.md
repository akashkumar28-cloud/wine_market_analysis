
# 🍷 Wine Market Analysis

## 1. Project Title 
### 🍷 Wine Market Analysis: Global Wine Insights Dashboard

  An interactive Power BI dashboard designed to analyze global wine markets, pricing, ratings, wine varieties, countries, wineries, and value-for-money              opportunities.

 ## 2. Short Description 
 
   The Wine Market Analysis Dashboard is a visually engaging and analytical Power BI report designed to help users explore and compare over 130K wines across 44      countries and 708 varieties. The dashboard focuses on highlighting data-driven insights into global wine pricing, ratings, varieties, countries, and wineries.     It helps identify market trends, premium and luxury wine segments, highly rated wines, and value-for-money opportunities and data-driven strategists who seek      to understand trends and characteristics of wine market globally.

  ## 3. Tech Stack
  #   Technologies & Tools
   #### The project was developed using the following tools and technologies:

*  Microsoft Excel – Used for initial data cleaning, missing-value treatment, duplicate removal, and data preparation.
*  PostgreSQL – Used to store and manage the cleaned wine dataset.
*  SQL – Used for data exploration, business analysis, aggregations, filtering, sorting, and deriving analytical insights.
*  Power Query – Used for data transformation, cleaning, and preparation within Power BI.
*  Power BI Desktop – Used to create interactive dashboards and visualizations.
*  DAX (Data Analysis Expressions) – Used to create calculated measures, calculated columns, KPIs, price segments, rating categories, and value analysis.
*  Data Visualization – Used charts, cards, slicers, maps, tables, and other visuals to communicate insights.
*  File Format – .pbix for development and .png for dashboard previews.
*  Git & GitHub – Used for project version control, documentation, and portfolio presentation.

  ## 4.  Data Source: GV Cloud Secure (Internship Project)

   The dataset was provided during my internship at GV Cloud Secure and contains wine-level information covering wines from multiple countries, wineries,             varieties, regions, prices, and ratings. The dataset includes attributes such as country, winery, variety, province, region, designation, price, points, title.    The data was cleaned and transformed to handle missing values, remove duplicates, standardize categorical fields, and create analytical fields such as **Price     Category, Rating Category, and Value Score**. The prepared dataset was subsequently analyzed using **PostgreSQL and SQL** and visualized through an                interactive **Power BI dashboard**.
   
   **Note:** The original dataset was provided as part of an internship project and is not publicly included in this repository due to data confidentiality.

  ## 5. Highlights

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
    
   This project transforms the raw wine dataset into an interactive analytical solution that helps answer key business questions around pricing, quality, market      performance, and value.**The key business questions are:**

 ## Does higher price guarantee better quality?

   Higher price does not guarantee better quality. The analysis shows a moderate positive relationship between price and rating (correlation ≈ 0.40). Although        Luxury wines have the highest average rating, moderately priced wines can also achieve strong ratings, demonstrating that price alone is not a reliable            indicator of wine quality.
   The average rating does increase across price segments:

Price Segment     	 Avg. Price	                Avg. Rating
  Budget	             $15.07	                      86.58  
Mid-Range	             $32.10	                      88.91
 Premium	             $69.02	                      91.05 
  Luxury	             $184.82	                    92.82

   So, more expensive wines tend to receive higher ratings on average, but the relationship is not strong enough to say that price guarantees quality.

  ## Which countries produce the highest-rated wines?
  
  Austria is the strongest high-volume country, while several premium wine regions achieve exceptionally high ratings. Among countries with a meaningful number of   wines in the dataset, Austria has the highest average rating at approximately 90.10, followed by Germany at 89.85, Canada at 89.37, and Hungary at 89.19.

   ## Which wines appear overpriced or underpriced based on their price and rating?

   Yes. The analysis identifies both potential overpriced and underpriced wines. Using the median price of $25 and median rating of 88 points as benchmarks,          11,790 wines are classified as potentially overpriced, while 12,760 are identified as potentially underpriced/high-value opportunities. This highlights            meaningful pricing inefficiencies within the market.
   So approximately:

 * 9.1% are potentially overpriced. * 
 * 9.8% are potentially underpriced/high-value. * 
 * 81.1% fall into the normal category.

  ## Which price segment offers the best balance of quality, affordability, and value?
  
   The Mid-Range segment offers the strongest overall balance.

   The actual segment results are:

   Price Segment	       Wines	     Avg. Price	  Avg. Rating	  Avg. Value Score   
      Budget	           46,341	       $15.07	      86.58	           6.16      
   **Mid-Range      	   63,856	       $32.10	      88.91	           2.98**    
     Premium	           16,408	       $69.02	      91.05	           1.36     
      Luxury	            3,366	       $184.82	    92.82	           0.75

Budget has the highest mathematical Value Score, but its average rating is lower. Premium and Luxury have higher ratings but substantially higher prices and       lower Value Scores.
    
  #  Walkthrough of Key Visuals

  # Executive Summary
  The Executive Summary provides a high-level overview of the wine market.

  ##  KPI Cards
  Provides a high-level overview of total wines, average price, average rating, countries, wineries, varieties.

  ## Key Visuals
  
  ## Wines by Country
  Shows the distribution of wines across different countries and identifies the major wine-producing markets represented in the dataset.

  ## Wines by Price Category
  Compares the number of wines across:
  Budget
  Mid-Range
  Premium
  Luxury

  This provides an overview of the market's price structure.

## Business purpose
  The Executive Summary gives decision-makers a quick understanding of the overall size, pricing structure, and quality profile of the wine market.

# Price vs Rating
   This page investigates one of the most important business questions:
   Does higher price guarantee better quality?

## Key Visuals

## Price vs Rating
   The scatter plot compares wine price against rating and helps identify the relationship between price and perceived quality.
   The analysis shows a moderate positive relationship, with a price-rating correlation of approximately 0.40.

## Average Rating by Price Segment
   Compares average ratings across:
   Budget — 86.58
   Mid-Range — 88.91
   Premium — 91.05
   Luxury — 92.82
   This shows that average quality tends to increase with price, but the relationship is not strong enough to conclude that price guarantees quality.

## Average Price by Price Category
   Shows how dramatically the average price increases across segments.
   For example:
   Budget: $15.07
   Mid-Range: $32.10
   Premium: $69.02
   Luxury: $184.82
   
## Price per Rating Point
   This helps evaluate how much consumers are paying relative to the rating received.

## Business insight
   Higher-priced wines generally receive higher ratings, but price alone does not guarantee quality. The moderate correlation of approximately 0.40 indicates that    other factors also influence wine ratings.

# Regional Analysis
   The Regional Analysis page evaluates wine performance geographically.

## Key Visuals

## Average Rating by Country
   Compares average wine ratings across countries.
   Austria is one of the strongest major-country performers, with an average rating of approximately 90.10.

## Average Price by Country
   Shows differences in average wine prices across countries.
   This helps identify countries positioned toward higher-priced or more affordable wine markets.

## Average Rating by Top Regions
   Highlights regions producing highly rated wines.

## Business insight
   The analysis reveals significant geographic differences in wine quality. Austria performs strongly among major countries, while several specialized regions        achieve average ratings around 96 points or higher, highlighting potential premium wine-producing markets.

# Variety Analysis
  The Variety Analysis page evaluates wine performance at the top-variety level.

## Key Visuals

 ## Top Varieties by Average Rating
    Identifies varieties with the highest average ratings.

## Top Varieties by Average Price
   Shows varieties commanding higher average prices.
   This can indicate varieties associated with premium positioning.

## Top Varieties by Number of Wines
   Shows which varieties have the largest representation in the dataset.
   This provides context around market presence.

## Best Value Varieties
   This is one of the most important visuals.

The analysis uses:

Value Score = Average Rating ÷ Average Price

To make the comparison more reliable, you have applied a minimum threshold of 100 wines per variety.

The leading value performers include:

Torrontés — Value Score 6.14
Viura — 5.51
Verdejo — 5.30
Bonarda — 5.20
Portuguese White — 5.18
Business insight

Among varieties with at least 100 wines, Torrontés provides the highest quality-to-price value, followed by Viura, Verdejo, Bonarda, and Portuguese White. Portuguese White and Pinot Grigio are particularly interesting because their value performance is supported by large numbers of wines.

This is much stronger than simply saying "Torrontés is the best" because you are considering sample size.

# Value Analysis
  The Value Analysis page focuses on identifying pricing opportunities and potential market inefficiencies.

## Key Visuals

 ## Top Wines by Value Score
    Identifies individual wines with strong ratings relative to their prices.
    This helps identify products that deliver high perceived quality at comparatively lower prices.

## Average Value Score by Price Category
   Compares the quality-to-price relationship across Budget, Mid-Range, Premium, and Luxury categories.
   This helps demonstrate how value changes as wine prices increase.

## Price vs Rating — Outlier Analysis
   This visual identifies wines that deviate from expected price-quality relationships.
   The classification uses the median benchmarks:
   Median Price = $25
   Median Rating = 88
 **Potentially Overpriced**
   Price > $25 + Rating < 88

**Potentially Underpriced / High Value**
  Price < $25 + Rating > 88

**Normal**
  Other combinations.

The analysis identifies:
11,790 potentially overpriced wines
12,760 potentially underpriced/high-value wines
105,421 normal wines

## Business insight
   Approximately 9.1% of wines are classified as potentially overpriced, while approximately 9.8% are identified as potential underpriced/high-value                  opportunities. This indicates meaningful price-quality mismatches within the market.

  #  Business Impact & Insights

  ## Pricing Strategy
     The Price vs Rating and Outlier Analysis can help businesses identify whether their products are appropriately priced relative to perceived quality.

## Business impact:
   Helps identify potential overpricing and underpricing opportunities and supports more informed pricing decisions.

## Product Portfolio Optimization
   The Variety Analysis identifies varieties that provide strong quality-to-price performance.

## Business impact:
   Businesses can prioritize high-value varieties when developing or expanding product portfolios.

## Regional Market Strategy
   Regional Analysis highlights countries and regions associated with stronger wine ratings.

## Business impact:
   Businesses can identify high-performing wine-producing regions for sourcing, premium positioning, partnerships, or market expansion.

## Segment Strategy
   The analysis of Budget, Mid-Range, Premium, and Luxury categories helps businesses understand the trade-off between price and quality.

## Business impact:
   The Mid-Range segment's combination of large market presence, reasonable pricing, and strong ratings suggests an attractive opportunity for businesses             targeting quality-conscious but price-sensitive consumers.

## Value-Based Product Positioning
   The Value Score identifies wines that deliver relatively high ratings at lower prices.

## Business impact:
   These products can potentially be positioned as "high-quality value" offerings for consumers who seek quality without paying luxury-level prices.

## Data-Driven Decision Making
   Instead of relying on assumptions such as:
   **"Expensive wine = better wine"**
   the dashboard provides evidence based on 129,971 wines across countries, regions, wineries, varieties, prices, and ratings.

## Business impact:
   Enables stakeholders to make pricing, product, regional, and segment decisions using data rather than intuition alone.



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
    

  
