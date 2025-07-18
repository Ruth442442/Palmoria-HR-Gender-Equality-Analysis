
# Palmoria HR Analytics – Gender Equality Case Study

![Palmoria Dashboard]

The Palmoria Group, a manufacturing company based in Nigeria, is embroiled in issues bordering on **gender inequality** in its 3 regions. A recent media headline — _"Palmoria, the Manufacturing Patriarchy"_ — sparked public concern and internal pressure.

## Background

With plans to scale across regions and even internationally, the CEO, **Mr. Ayodeji Chukwuma**, assigned the CHRO, **Mr. Yunus Shofoluwe**, to investigate the claims. You have been hired as an **HR Analytics Consultant** to analyze the HR data and recommend urgent actions.



# Palmoria HR Analytics – Gender Equality Case Study
The Palmoria Group, a manufacturing company based in Nigeria, is embroiled in issues bordering on **gender inequality** in its 3 regions. A recent media headline — _"Palmoria, the Manufacturing Patriarchy"_ — sparked public concern and internal pressure.

## Background

With plans to scale across regions and even internationally, the CEO, **Mr. Ayodeji Chukwuma**, assigned the CHRO, **Mr. Yunus Shofoluwe**, to investigate the claims. You have been hired as an **HR Analytics Consultant** to analyze the HR data and recommend urgent actions.

## Objectives

- Analyze employee data to uncover gender-related inequalities  
- Visualize insights using interactive dashboards  
- Make evidence-based recommendations to management  


## Case Scenario Instructions

- Assign generic gender status to employees who didn’t disclose it  
- Remove employees without salary (they’re no longer with the company)  
- Exclude rows where departments are marked “NULL”  


## Key Analysis Questions

1. **What is the gender distribution** in the company (by region and department)?
2. **What do employee ratings** look like across genders?
3. **Is there a gender pay gap**? If yes, in which departments and regions?
4. **Does Palmoria comply** with the regulation mandating a **minimum salary of $90,000**?
    - Show salary distribution by $10,000 bands
    - Visualize salary bands by region
5. **Bonus Allocation**
    - Calculate bonus based on performance rules
    - Show total salary (base + bonus) per employee
    - Compute total bonus payout per region and overall



## Power BI Dashboard Highlights

**Total Employees Analyzed:** 946  
**Compliance Rate:** 30.87% (only 30.87% earn at least $90,000)  
**Gender Distribution:**  
  - Male: 465 (49.15%)  
  - Female: 441 (46.62%)  
  - Unknown: 40 (4.23%)  

## Salary Disparities

**Overall Salary Including Bonus:**  
  - **Total:** $71.92M  
  - **Without Bonus:** $69.72M  
  **By Region:**  
  - **Kaduna:** $27.48M  
  - **Abuja:** $24.92M  
  - **Lagos:** $19.53M  

  **Median Salary by Gender (All Regions Combined):**  
  - **Male:** $73,366  
  - **Female:** $72,500  
  - **Unknown:** $75,360  
  - **Gap (Male vs. Female):** ~$866 in favor of males  

  **By Department – Notable Gaps:**  
  **Legal:**  
    - Male: $84,640  
    - Female: $78,650  
    - Gap: ~$5,990  
    **Sales:**  
    - Male: $80,690  
    - Female: $68,640  
    - Gap: ~$12,050  
    **Accounting:**  
    - Male: $77,030  
    - Female: $72,550  
    - Gap: ~$4,480  

## Bonus Insight

**Bonus amounts are based on performance ratings**, with higher ratings receiving higher bonuses.  
**Average employee rating by gender:**  
  - **Male:** 3.17  
  - **Female:** 2.90  
  - **Unknown:** 3.00  

**Total Company-Wide Bonus Paid:** ~$2.2M  
  (Estimated from difference between overall salary with and without bonus: $71.92M – $69.72M)  
**Regions with Highest Total Bonus Paid:**  
  1. **Kaduna:** $27.48M total (includes largest bonus allocation)  
  2. **Abuja:** $24.92M  
  3. **Lagos:** $19.53M  

  **Key Observation:**  
  - Male employees not only received **higher salaries**, but also **higher performance ratings**, which led to **higher bonuses** across all regions.



## Project Files

- `Palmoria_HR_Dashboard.pbix` – Power BI file  
- `Palmoria_HR_Data.csv` – Cleaned dataset  
- `Bonus_Rules.csv` – Bonus calculation criteria  
- `Screenshot (216).png` – Dashboard preview image  
- `README.md` – Project documentation  



## Recommendations

- Conduct periodic **gender pay audits**
- Enforce the **$90K minimum salary rule** consistently
- Improve **transparency in bonus allocation**
- Address underrepresentation of women in **high-paying departments**
- Investigate rating bias in departments with poor female scores

