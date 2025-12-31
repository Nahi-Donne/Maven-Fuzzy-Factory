# Maven Fuzzy Factory

This case study analyzes the commercial performance of Maven Fuzzy Factory, a toy company offering four distinct product lines, over the period from January 2012 to March 2015.

Following its launch in 2012, the company experienced substantial sales growth, driven primarily by its flagship product, “The Original Mr. Fuzzy,” which quickly gained strong market popularity. While the company has consistently acquired a large number of new customers each year, customer retention remains low, highlighting a key strategic challenge and an opportunity to improve long-term customer lifetime value.

Sales performance exhibits pronounced seasonality, with the fourth quarter—particularly December—consistently delivering peak revenue, reflecting holiday-driven demand patterns.

#### Key Business Implications

* Revenue growth is heavily concentrated in a single flagship product, indicating both strength in product-market fit and risk due to product dependency.
* Strong customer acquisition has not translated into repeat purchasing, limiting customer lifetime value.
* The clear Q4 peak indicates that marketing spend, inventory planning, and promotional strategies should be heavily weighted toward the holiday season to maximize returns.

![Product Analysis](./e-commerce2.png)

### 1. Product Revenue, Net Revenue, and Profitability Analysis

#### Metric Definitions and Methodology

The following standard financial definitions were applied:

* Net Revenue

 	**Net Revenue** = Gross Revenue − Total Refunds

* Gross Profit

 	**Gross Profit** = Gross Revenue − (Total Refunds + Cost of Goods Sold )

*Note: This represents gross profit (prior to operating expenses). Due to the absence of operating expense data, gross profit is used as a proxy for net profit for analytical purposes.*

* Profit Margin

 	**Profit Margin** = Gross Profit / Net Revenue	​

* Return Rate

 	**Return Rate** = Units Returned / Units Sold

 where:

* **Units Returned** = total number of items returned across all orders

* **Units Sold** = total number of items sold across all orders

#### 1.1. Revenue Growth and Profitability Performance

Using the above definitions, the analysis shows that net revenue increased consistently from January 2012 through March 2015, achieving a Compound Annual Growth Rate (CAGR) of 1.398, calculated as:

 	**CAGR =** (Ending Revenue Value / Beginning Revenue Value)^(1/𝑛) − 1
  
**Where n = 3 years**

In addition, the business achieved a revenue-weighted average profit margin of 61.93%, calculated as:

 		**∑ Gross Profit / ∑ Net Revenue**	​
    
**Insight**

The company is not only growing revenue but doing so with strong and improving operational efficiency, indicating effective cost control, pricing discipline, and limited revenue leakage from refunds and returns.

#### 1.2. Product-Level Insights

##### Net Revenue and Units Returned by Product

**The Original Mr. Fuzzy** is the dominant product across the full analysis period, generating the majority of total revenue over all three years. At the same time, it also accounts for the highest number of returned units.

Key observations include:

* Average annual returned units for The Original Mr. Fuzzy: 309 units
* Share of total returned units (Jan 2012 – Mar 2015): 71.46%, calculated as:

      **Total Returned Units (Mr. Fuzzy) / Total Returned Units (All Products)**

Total refund value attributable exclusively to The Original Mr. Fuzzy over this period: $61,837.63

**Insight**

Returns are highly concentrated in the top-selling product, which suggests targeted improvement opportunities rather than systemic issues across the product portfolio. Potential drivers include:

* Product quality or durability concerns
* Customer expectation or sizing mismatches
* Packaging or shipping-related damage

Focusing return-reduction efforts specifically on The Original Mr. Fuzzy is likely to deliver the highest impact on profitability.

![Product Analysis](./e-commerce2.png)

### 2. Customer Behavior Analysis
#### 2.1. Add to Cart

The fourth quarter consistently records the highest add-to-cart activity across the full analysis period (Jan 2012 – Mar 2015), with November and December top performer months. 

The add to cart yearly average rate is 20.08%, calculated as:

**Average Yearly Add-to-Cart Rate =**

∑ Add-to-Cart Sessions (2012–2015) / ∑ Total Sessions (2012–2015)

Approximately one in five sessions results in add-to-cart activity, indicating solid mid-funnel engagement.

#### 2.2. Product Contribution to Customer Volume

The “Customers per Year by Product” chart shows that **The Original Mr. Fuzzy** significantly outperforms other products in attracting customers. The remaining products contribute relatively similar but much lower volumes.

Monthly conversion rates show a steady upward trend throughout the year, peaking in Q4, consistent with seasonal purchase intent and promotional activity.

#### 2.3. Repeat Purchase and Purchase Frequency

The “Repeat Purchase Rate by Product” visual is empty, while the “Purchase Frequency by Product” chart shows values well below 1 for all products.

This indicates that:

* Customers do not repurchase the same product
* Overall purchase frequency remains low

This behavior aligns with expectations for non-consumable goods such as toys.

##### Metric Definitions

To understand the difference between those two metrics here are the formula used to determine each and why we used them:

**Repeat Purchase Rate (by Product) =** 

Customers purchasing the same product ≥ 2 times​ / Total Customers purchasing the product

Measures SKU-level loyalty.

Interpretation

&nbsp;  - High value → consumable, collectible, or replenishable product

&nbsp;  - Low or zero → one-time purchase product

**Purchase Frequency (by Product) =** 

Unique customers who bought the product / Total orders containing the product

&nbsp;	​
Measures average purchase count per customer.

Interpretation

&nbsp;   - Value = 1 → every customer bought it once

&nbsp;   - Value < 1 → not all customers bought it

&nbsp;   - Value > 1 → repeat buying exists
The difference is: 

Repeat Purchase Rate highlights a lack of SKU-level loyalty while
Purchase Frequency quantifies how limited that loyalty is.

![Product Analysis](./e-commerce2.png)

### 3. Web Sessions \& Funnel Performance Interpretation
#### 3.1. Traffic and User Growth

The platform experienced strong year-over-year growth, with an average of 118,218 sessions per year. Session growth slightly outpaced user growth, suggesting increased repeat visitation.

#### 3.2. Add-to-Cart and Order Execution

**Mid-funnel engagement is solid and improving. Approximately 20% of sessions result in add-to-cart activity, and growth in executed orders indicates improving funnel efficiency and/or higher-quality traffic.**

#### 3.3. Checkout Completion and Cart Abandonment Rate

Approximately two-thirds of users who reach checkout successfully complete their purchase, reflecting a relatively healthy checkout flow.
However, nearly two out of every three carts are abandoned, indicating that a significant portion of users drop off before reaching checkout.

The Formula used:

**Checkout Completion Rate =** 

∑ Orders Executed (2012-2015) / ∑ Checkout Sessions (2012-2015)
	
**Cart Abandonment Rate =**
	1 - (∑ Orders Executed (2012-2015) / ∑ Add to Cart Sessions(2012-2015)

#### 3.4. Repeat Session Rate by Device Type

Mobile users exhibit a slightly higher repeat session rate, indicating stronger engagement or convenience-driven repeat visits on mobile devices.

#### 3.5. Conversion Rate by UTM Source

Search and direct traffic are the strongest converting channels, while social traffic significantly underperforms, suggesting awareness-driven rather than purchase-driven intent from social sources.

![Product Analysis](./e-commerce2.png)

---
## 🛠️ Tools & Technologies
- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query**
- **Excel / CSV Data Source**
- **GitHub** for version control and project sharing

---

## 📁 Dataset
Dataset Information <br>
The dataset used in this project was obtained from [Maven Analytics](https://mavenanalytics.io/data-playground/toy-store-e-commerce-database). <br>

> *Note: The dataset is for educational purposes only.*

#### 📁 VIDEO GAME SALES ACROSS THE WORLD/

├── README.md                                     – Summary overview <br>
├── Game_Sales_Project                            – Power BI Report <br>
└── vgchartz-2024                                 – Sales Dataset <br>
  

## 👤 Author
**Dieudonné Nahimana**  
🌐 [LinkedIn Profile](https://www.linkedin.com/in/nahimana-dieudonn%C3%A9-99b4a9200/)





