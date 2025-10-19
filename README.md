# Maximizing-Online-Retail-Performance: Analyzing Traffic Patterns by Time and Source

🔗 **[View Interactive Tableau Dashboard](https://public.tableau.com/app/profile/jeneviv.okougha/viz/Bright_cartproject/Trafficanalysis)**  
Explore the live dashboard with filters for month, year, and traffic source.

## Table of Contents
  - [Description](#description)
  - [Business Introduction](#business-introduction)  
  - [Business Problem](#business-problem)  
  - [Aim](#aim)  
  - [Processes](#processes)  
  - [Key Insights](#key-insights)  
  - [Recommendations](#recommendations)
### Description
This project focuses on analyzing website traffic data for an online retail company that sells consumer electronics, home goods, and lifestyle products. The analysis was done entirely in Tableau, with the goal of uncovering user behavior patterns, identifying key traffic sources, and helping the business make data-driven marketing decisions.

<img width="1201" height="898" alt="Screenshot 2025-10-19 230626" src="https://github.com/user-attachments/assets/212cc8ab-e751-4575-b0d9-afd8ba3d9da6" />


<img width="1408" height="896" alt="Screenshot 2025-10-19 230606" src="https://github.com/user-attachments/assets/883581ab-c5fe-4fb9-a2f3-9195d016c819" />

### Business Introduction
The company operates a rapidly growing e-commerce platform offering a wide range of consumer goods. Since launching in 2010, it has built a strong digital presence and a diverse customer base. As the business expanded, understanding how and when customers visit the website became increasingly important for marketing and operations.
### Business Problem
##### Traffic Timing Uncertainty:
- Without understanding the platform’s peak engagement hours, the company struggles to schedule promotions, email campaigns, and website updates effectively.
##### Traffic Source Analysis:
- Marketing resources are not optimally allocated because the company cannot accurately measure the ROI and effectiveness of each traffic source.
##### Conversion Optimization:
- High website traffic during suboptimal times does not always lead to conversions, resulting in inefficient use of marketing budgets and reduced ROI.
##### Customer Behavior Insights:
- Limited understanding of when and where customers interact with the platform reduces the effectiveness of personalization and targeted promotional efforts.
### Aim
The aim of this project was to design an interactive Tableau dashboard that visualizes website traffic trends and highlights the relationship between different marketing channels, time periods, and user engagement.
The dashboard would serve as a central tool for the marketing team to monitor performance, identify high-performing channels, and make better-informed campaign decisions.
### Processes
#### Data Preparation 
The dataset included key fields such as date, time, traffic source, device type, sessions, page views, conversions, and revenue.  
Initial cleaning was done in **Excel** — removing duplicates, handling missing values, and standardizing date and time formats for easy import into Tableau.
Data Connection and Modeling**  
The cleaned dataset was connected to **Tableau Desktop**, where calculated fields were created to support deeper analysis.  
#### Some of the core metrics calculated included:  
- **Conversion Rate**
- **Bounce Rate**  
- **Traffic Sorce** 
- **Unique Page Views**
#### Parameter Creation 
To make the dashboard fully dynamic and allow users to explore data across time periods, I created several **parameters** in Tableau:  
- **Month Parameter:** Allows users to filter and compare traffic trends for specific months.  
- **Year Parameter:** Enables year selection for calculating and visualizing **Year-over-Year (YoY)** growth.  
- Combined use of both parameters supports **Month-over-Month (MoM)** comparisons to measure short-term performance shifts.  
These parameters help the marketing team quickly identify whether traffic or conversions are improving over time.
#### Calculated Fields for Trend Analysis 
Created custom calculations for key growth metrics:  
- **YoY Growth** = ((Current Year Value - Previous Year Value) / Previous Year Value)  
- **MoM Growth** = ((Current Month Value - Previous Month Value) / Previous Month Value) 
#### Visualization Development 
Built multiple Tableau views including:  
- Traffic trends by month and year  
- Channel performance (Organic, Paid, Social, Email)  
- Device comparison (Desktop, Mobile, Tablet)  
- Campaign-level analysis showing conversion and engagement metrics  

All views were then combined into a single, interactive **Tableau dashboard** with consistent colors, typography, and filter controls.
### Dashboard Testing and Refinement  
Ensured all filters, parameters, and calculations updated correctly.  
Tested responsiveness, adjusted color gradients, and fine-tuned tooltips for clarity.
### Tools Used 
- **Excel** – Data cleaning and preparation  
- **Tableau** – Data modeling, parameter creation, calculated fields, and interactive dashboard development

### Key Insights

- **2023 was the strongest performing year** — user activity, conversions, and engagement all improved compared to 2022.  

- **2024 showed a noticeable decline** — there were drops across new and returning users, conversions, and unique page views.  

- **Bounce Rate increased**, confirming weaker engagement quality. The 0% rate in 2022 likely reflects incomplete or missing tracking data.  

- **Mobile devices dominate** as the primary platform for user sessions, while desktop remains secondary and tablet usage is minimal.  

- **Organic and Direct traffic lead consistently**, with Social Media showing steady growth.  
  **Paid Ads underperform**, and **Referral traffic collapsed** in 2024, indicating potential issues with partner links or campaigns.  

- **Geographic patterns shifted over time** — in Canada, traffic alternated between Ontario and British Columbia; in the UK, Scotland gained share.  
  In the U.S., California and New York saw growth, while Texas experienced a decline.  

- **Engagement timing is clearly defined** — the highest activity occurs on **Sunday and Monday late evenings (around 11 PM)**.  
  Across all years, **Q4 displays a consistent decline** in overall engagement levels.

### Recommendations

#### Channels & Traffic
- **Strengthen Organic and Direct channels**, as they remain the most reliable sources for user acquisition and conversions.  
- **Scale Social Media efforts**, which show steady growth and strong potential for higher engagement.  
- **Optimize Paid Ads** by concentrating ad spend during peak engagement periods to improve ROI and conversion rates.  
- **Investigate the Referral collapse in 2024** to identify root causes and recover lost conversions and traffic quality.  

#### Timing & Campaigns
- **Run campaigns during Sunday and Monday late evenings (around 11 PM)** when user activity is highest.  
- **Add midweek promotions** to offset lower engagement observed on Wednesdays and Thursdays.  
- **Launch holiday and reactivation campaigns in Q4** to address the consistent decline in engagement toward year-end.  

#### Engagement & Experience
- **Adopt a mobile-first strategy** by improving load times, navigation flow, and checkout simplicity to enhance user satisfaction.  
- **Refine landing page design and ad targeting** to reduce bounce rates and improve session quality.  
- **Focus on key performing regions** such as Ontario, British Columbia, California, and New York, while addressing weaker engagement in Texas and the UK.
