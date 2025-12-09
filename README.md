# QuickBites Crisis – End-to-End Power BI Case Study
## Problem Statement
QuickBite Express is a Bengaluru-based food-tech startup (founded in 2020) that connects customers with nearby restaurants and cloud kitchens.
In June 2025, QuickBite faced a major crisis. A viral social media incident involving food safety violations at partner restaurants, combined with a week-long delivery outage during the monsoon season, triggered massive customer backlash. Competitors capitalized with aggressive campaigns, worsening the situation.
 

# The challenges were severe: 

A large portion of active users disengaged within a short period. 

Daily orders saw a sharp decline compared to earlier months. 

Customer satisfaction scores fell sharply, signaling trust issues. 

Many partner restaurants shifted to competing platforms. 

Customer acquisition costs rose significantly. 

QuickBite has allocated a major recovery budget, overhauled food safety protocols, and upgraded its delivery infrastructure.
 

# The management expects detailed insights into the following: 

Customer Segments: Identify which customers can be recovered and which need new strategies. 

Order Patterns: Analyse order trends to uncover behavioral changes across phases (pre-crisis, crisis, recovery). 

Delivery Performance: Assess delivery times, cancellations, and SLA compliance to pinpoint operational gaps. 

Campaign Opportunities: Recommend targeted initiatives to rebuild trust and loyalty across demographics. 

Restaurant Partnerships: Predict which partnerships are most valuable for long-term retention. 

Feedback & Sentiment: Monitor real-time ratings, reviews, and sentiment to guide ongoing recovery efforts. 


## 🎯 2. Project Goals

- Measure revenue, churn, SLA breach, and customer satisfaction across **Pre-Crisis, Crisis, Recovery** phases  
- Identify **high value lost** and **recoverable** customer groups  
- Analyse **order patterns, cancellations, COD behavior**  
- Evaluate **delivery performance** and SLA issues  
- Assess **restaurant partner retention** and campaign opportunities  
- Provide **clear recommendations** for management

---

## 🛠️ 3. Tools & Tech

- **Power BI** – Data modelling & dashboards  
- **Excel/CSV** – Raw data files  
- Basic **DAX** for measures (churn, revenue at risk, retention score, AOV, SLA, etc.)

---

## 🗂️ 4. Data Sources

Files stored in the Dataset folder:

dim_customer.csv
dim_delivery_partner_.csv
dim_menu_item.csv
dim_restaurant.csv
fact_delivery_performance.csv
fact_order_items.csv
fact_orders.csv
fact_ratings.csv


> Note: Data is anonymised / sample-based for portfolio purpose.

---

## 📊 5. Dashboard Pages

1. **Executive Summary**  
   - Total revenue, revenue at risk, churned users, SLA breach  
   - Revenue by phase (Pre-Crisis, Crisis, Recovery)  
   - Churn by city & average delay

2. **Customer Recovery & Churn**  
   - Total customers, churned, loyal, recoverable  
   - Revenue at risk (₹31.02M)  
   - Customer segments: Needs New Strategy, High Value Lost, Warm Recoverable, Highly Recoverable  
   - Recency vs Total Spend scatter

3. **Order Patterns & Behaviour**  
   - Orders & AOV trend by month  
   - Cancellations by phase & by COD vs prepaid  
   - Peak order hours by weekday  
   - Cuisine-wise order contribution

4. **Delivery Efficiency & SLA Performance**  
   - Average delivery time, delay, on-time %, SLA breach %  
   - SLA breach by city  
   - Orders and delay trend  
   - Distance vs delay scatter

5. **Restaurant Partnership & Retention**  
   - Total vs active restaurants  
   - Restaurant revenue ranking  
   - Retention score by restaurant  
   - Repeat orders vs revenue

6. **Campaign Opportunities**  
   - Recoverable customers by acquisition channel and city  
   - Total customers by segment (Needs Strategy, High Value Lost, Warm, Highly Recoverable)

7. **Feedback & Sentiment**  
   - Total reviews by phase  
   - Average rating & sentiment by phase  
   - Low rating %  
   - Word cloud of most common negative comments

---

## 🔍 6. Key Insights (Short Version)

- Revenue crashed during crisis and is **still far below Pre-Crisis**  
- **76K out of 105K** customers have stopped ordering  
- **₹31 crore** revenue is at risk from high-value churned users  
- SLA breach rose from **56% → 88%**, and still ~87% in recovery  
- COD share increased, showing **low trust in prepaid orders**  
- High-value lost and warm recoverable customers (~34K) are the **best recovery target**  
- Customer ratings and sentiment remain **negative** even in recovery phase

---

## ✅ 7. How to Open the Report

1. Download `QuickBites_Crisis.pbix` from this repo  
2. Open it using **Power BI Desktop**  
3. Explore each page using the left-side tabs (Executive, Customer, Delivery, Restaurant, etc.)

---
