# California Community College Enrollment Trends (2016–2024)

## Overview  
This exploratory data analysis (EDA) examines enrollment trends across California Community Colleges (CCC) from 2016 to 2024 using publicly available data from the California Community Colleges Chancellor’s Office (CCCCO) [Data Mart](https://datamart.cccco.edu/datamart.aspx).  

The analysis examines how total enrollment changed before, during, and after the COVID-19 pandemic while tracking shifts across student demographics such as age, gender, and ethnicity. It also looks at enrollment type differences—full-time versus part-time students—to understand how learning preferences and participation patterns evolved over time.

Through visualizations and year-over-year comparisons, this project highlights recovery trends, demographic shifts, and possible implications for statewide access to higher education. The goal is to provide clear insights that can inform strategies around student engagement, retention, and targeted access across California’s community college system.

### Objectives  
- Observe enrollment trends over eight academic years to identify overall growth or decline  
- Assess the impact of the COVID-19 pandemic on statewide enrollment and recovery patterns  
- Compare demographic changes by age, gender, and ethnicity  
- Explore differences in enrollment types (full-time vs. part-time)  
- Provide insights that can inform strategies to improve access, engagement, and retention  

## Table of Contents  
- [Project Background](#project-background)
- [Data Structure Overview](#data-structure-overview)
- [Executive Summary](#executive-summary)
- [Insights Deep Dive](#insights-deep-dive)
- [Recommendations](#recommendations)
- [Project Structure](#project-structure)

## Project Background  
The California Community Colleges Chancellor’s Office (CCCCO) [Data Mart](https://datamart.cccco.edu/datamart.aspx) provides detailed statewide data on students, faculty, staff, and institutional outcomes. The dataset includes information on student demographics, enrollment status, academic programs, and course participation across all 116 community colleges.  

This project draws on Data Mart’s term-level enrollment data to analyze academic years 2016–2017 through 2023–2024. The dataset enables a detailed look at enrollment patterns over time and how statewide recovery efforts, policy changes, and shifting student needs have shaped access to higher education in California.  

## Data Structure Overview  
Source: California Community Colleges Chancellor’s Office (Data Mart)  
Period Covered: 2016–2017 to 2023–2024 academic years  
Format: CSV file containing term-level and demographic-level enrollment data  

**Key Fields**:  
- Academic Year  
- Term  
- College  
- Gender  
- Age Group  
- Ethnicity  
- Full-/Part-Time Status  
- Headcount  

**Tools and Techniques**:  
- **Python Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Data Cleaning:** Handling missing values, correcting data types, and normalizing demographic categories  
- **Visualization:** Time series plots, demographic distributions, and heatmaps for enrollment shifts  


 
## Executive Summary  


### Systemwide Trends  
Total statewide enrollment declined from **2.08 million students in 2019** to **1.75 million in 2021**, marking a **15.8% decrease** during the COVID-19 pandemic. By 2024, enrollment rebounded to approximately **1.88 million students**, a **9% shortfall** compared to pre-pandemic levels. The sharpest single-year drop occurred between **Spring 2020 and Spring 2021 (-8.2%)**.  

### Top 5 Colleges by 2024 Enrollment  
1. **Mt. San Antonio College** – 115,270 students  
2. **Santa Ana College** – 102,073 students  
3. **East Los Angeles College** – 91,786 students  
4. **Bakersfield College** – 81,232 students  
5. **American River College** – 74,710 students  

Together, these institutions represented **15.2%** of total statewide enrollment in 2024.  

### Demographic Insights  
- **Latino/Hispanic students** remained the largest group, comprising **47–49%** of statewide enrollment. Their headcount declined **16%** between 2019 and 2021.  
- **Asian students** experienced a smaller **7% decline**, while **White students** fell by about **12%**.  
- **Students aged 30 and above** had the steepest decline (-22%) and have yet to return to pre-pandemic participation levels.  
- **Full-time students** recovered faster than part-time, indicating renewed engagement among degree- and transfer-seeking learners.  

### Term-Level Patterns  
- **Spring 2021** recorded the lowest enrollment of the dataset, while **Fall 2023** marked the strongest rebound.  
- **Summer terms** remained comparatively stable, suggesting that shorter or flexible sessions helped sustain engagement during the pandemic.  

### Year-over-Year Observations  
- Enrollment declined consecutively from 2019 to 2021, followed by increases of **4.3% (2023)** and **2.5% (2024)**.  
- The strongest recoveries occurred among large metro-area colleges in **Los Angeles, Orange, and San Diego** counties.  

### Conclusion  
California’s community college system is **recovering but still below its pre-pandemic baseline**. Continued improvement will depend on outreach to **older and part-time learners**, expansion of **flexible and hybrid learning options**, and **data-driven strategies** that address demographic and regional disparities. These findings underscore the importance of targeted re-engagement to ensure equitable and sustained recovery across the state’s higher-education landscape. 

## Insights Deep Dive  
WIP

## Recommendations  
Based on the enrollment trends and demographic shifts observed between 2016–2024, several strategies can support a more equitable and sustainable recovery across California’s community colleges:  

1. **Re-engage Older and Part-Time Learners**  
   - Launch targeted outreach campaigns and flexible re-enrollment pathways for students aged 30 and above, who experienced the sharpest enrollment declines (-22%).  
   - Expand evening, weekend, and short-term course options to better align with working learners’ schedules.  

2. **Invest in Hybrid and Flexible Learning Models**  
   - Maintain and expand online or hybrid course offerings that gained traction during the pandemic.  
   - Provide institutional support for digital learning tools, faculty training, and accessibility resources to reduce participation barriers.  

3. **Strengthen Retention and Student Support Services**  
   - Improve academic advising, tutoring, and mental health services to support persistence beyond initial enrollment.  
   - Use early alert systems and predictive analytics to identify students at risk of withdrawal or non-completion.  

4. **Address Demographic Disparities**  
   - Develop culturally responsive outreach for Latino/Hispanic and underrepresented students, who together account for nearly half of statewide enrollment.  
   - Partner with community-based organizations to increase access to financial aid, basic needs programs, and transfer counseling.  

5. **Focus on Data-Driven Policy and Resource Allocation**  
   - Use longitudinal data to monitor recovery by region, term, and demographic segment.  
   - Direct funding and program support to districts showing the slowest recovery, ensuring equitable growth across all 116 colleges.  

By combining targeted outreach, flexible scheduling, and sustained investment in student support and data-driven decision-making, California’s community college system can continue progressing toward full recovery and greater educational equity statewide.
