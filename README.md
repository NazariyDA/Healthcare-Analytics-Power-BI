# <img width="25" height="25" alt="image" src="https://github.com/user-attachments/assets/0d6b8573-170b-4ebd-b469-c1a7263a3c23" /> Analytics of the Healthcare center
Welcome to the GitHub repository for my exciting Power BI project - Analysis the financial performance of the Healthcare center <img width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/2ad13dce-d7a9-4f22-90c1-b4fc355697b4" />

:pushpin: Data source  [Healthcare Analytics](./Dashboard%20Resources.zip)

🧩 Used technologies: **Power BI** with **Power Query** (data cleaning and transformation)

## <img width="25" height="25" alt="image" src="https://github.com/user-attachments/assets/190d7aa4-6ac1-4060-bf2b-7c58be120a0c" /> Objectives of this project
**KPIs:** Identify and present the key performance indicators (KPIs)

**Detailed Analysis:** Ensure the analysis is thorough and detailed, covering all relevant aspects of the healthcare center's finance and the performance of healthcare providers.

**Dashboard Creation**: Create a comprehensive dashboard  that includes:
* Financial Overview: Summarize the financial health of the healthcare center.
* Provider Insights: Analyze the performance and efficiency of healthcare providers.

**Visualization:** Use appropriate visualizations to effectively communicate the findings.
* Interactivity: Ensure the dashboard is interactive and user-friendly.
* Clarity: Present the data in a clear and concise manner, makes it easy for stakeholders to understand the insights.

## <img width="25" height="25" alt="image" src="https://github.com/user-attachments/assets/2e00bec0-d629-4368-9657-90e933350f74" /> General overview
The database contains **5,000** visits (from January 1, 2024 to May 14, 2025). The total cost of services is **£ 3,356,075**, with an average of **£ 674.86** per visit. The dashboard covers financial metrics, regional distribution (map), procedures/diagnoses/departments (bar charts), length of stay (LOS), visit types (pie chart), and monthly trends (line chart).


<img width="818" height="456" alt="image" src="https://github.com/user-attachments/assets/474bef16-bbf3-431f-be3d-11f6fbf1270c" />
<img width="818" height="456" alt="image" src="https://github.com/user-attachments/assets/7e98fde3-7688-4680-ad89-c357bc410c82" />
<img width="818" height="456" alt="image" src="https://github.com/user-attachments/assets/21ade5cd-17fe-4754-b995-eeab3ac3fc2a" />
<img width="818" height="456" alt="image" src="https://github.com/user-attachments/assets/a68cdad1-0731-419c-b582-78c99a1ae500" />

## <img width="25" height="25" alt="image" src="https://github.com/user-attachments/assets/6793dbc4-3d2d-4088-bf15-df94174bfd8f" /> **Conclusions and Recommendations Based on the Analysis of the Medical Center's financial performance.**

* ### Financial Metrics 

| Metric             | Total Amount  | Average per Visit  |
|--------------------|---------------------|---------------------------|
| Billing Amount     | £ 3,356,075           | £ 674.86                    |
| Medication Cost    | £ 546,039             | £ 109.21                    |
| Treatment Cost     | £ 2,630,406           | £ 526.08                    |
| Insurance Coverage | £ 2,225,924           | £ 456.04                    |
| Out-of-Pocket      | £ 1,130,151           | £ 227.26                    |
| Room Charges       | £ 179,630             | £ 36.12                     |

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/48c4ff08-2a9d-4d3c-9718-eee6f10e87a1" /> **Conclusions:**  Insurance covers approximately 66% of all bills, while patients pay around 34% out of pocket. Room charges are low (5% of the total) but relevant for hospitalized cases (1,232 visits).  

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/55601706-b5a9-4da3-9c7a-8926a6ee60b2" /> **Trend:** An increase in billing in 2025 driven by a higher number of visits in Q1.

* ### Department Distribution

| Department       | Billing Amount  | Share  |
|-----------------|---------------------|-----------|
| Cardiology       | £ 846,925             | 25.2 %     |
| Orthopedics      | £ 813,253             | 24.2 %     |
| General Surgery  | £ 783,247             | 23.3 %     |
| Neurology        | £ 478,200             | 14.2 %      |
| Pediatrics       | £ 434,450             | 12.9 %      |

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/48c4ff08-2a9d-4d3c-9718-eee6f10e87a1" /> **Conclusions:** Cardiology and Orthopedics generate approximately 50% of revenue, likely due to expensive procedures (e.g., MRI/CT). Pediatrics contributes the least but remains stable.

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/f35489d1-c8a5-4471-9b95-d5fb263625ac" /> **Recommendation:** Invest in Neurology for growth, as its share is low.

* ### Procedure Distribution

| Procedure    | Billing Amount |
|-------------|---------------------|
| X-Ray       | £ 1,053,529           |
| CT Scan     | £ 805,508             |
| MRI Scan    | £ 600,739             |
| Ultrasound  | £ 481,347             |
| Blood Test  | £ 414,952             |

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/48c4ff08-2a9d-4d3c-9718-eee6f10e87a1" /> **Conclusions:** X-Ray is the leader (31% of total) due to its frequency in emergency cases. MRI and CT are expensive but less common.

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/f35489d1-c8a5-4471-9b95-d5fb263625ac" /> **Recommendation:** Optimize X-Ray procurement to reduce costs.

* ###  Distribution by Diagnoses and Service Types

| Diagnosis      | Emergency  | Inpatient  | Outpatient  | Total  |
|---------------|----------------|----------------|-----------------|-------------|
| Hypertension  | £ 295,617        | £ 316,481        | £ 716,115         | £ 1,328,213   |
| Appendicitis  | £ 143,289        | £ 146,923        | £ 371,306         | £ 661,518     |
| Asthma        | £ 187,044        | £ 186,479        | £ 255,982         | £ 629,505     |
| Migraine      | £ 89,536         | £ 88,402         | £ 147,481         | £ 325,419     |
| Fracture      | £ 121,867        | £ 117,424        | £ 172,129         | £ 411,420     |

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/48c4ff08-2a9d-4d3c-9718-eee6f10e87a1" /> **Conclusions:** Hypertension is the top diagnosis (40% of revenue), mainly outpatient. Emergency visits are higher for Asthma and Fractures.

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/f35489d1-c8a5-4471-9b95-d5fb263625ac" /> **Recommendation:** Focus on chronic disease prevention (Hypertension) to reduce outpatient load.

* ###  Regional Distribution

Top cities: Edinburgh (£ 1,021,264), Birmingham (£ 821,900).

| State/Country       | Billing Amount | Visits |
|--------------------|--------------------|--------|
| Wales              | £ 1,302,079          | 1,899  |
| Northern Ireland   | £ 1,050,377          | 1,548  |
| England            | £ 580,205            | 916    |
| Scotland           | £ 423,414            | 637    |

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/48c4ff08-2a9d-4d3c-9718-eee6f10e87a1" /> **Conclusions:** Wales is the leader (39% of revenue), likely due to a higher number of visits. England shows lower efficiency (fewer visits but higher bills).

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/f35489d1-c8a5-4471-9b95-d5fb263625ac" /> **Recommendation:** Expand services in Scotland for better balance.

* ### Visits and Hospitalizations
**General visits:** 5,000 (61% non-emergency, 39% emergency). **Hospitalized:** 1,232 (25% of visits). **Outpatient:** 2,520.

Length of stay (LOS):
| Days | Number of Patients |
|-----------|-----------------|
| 1         | 146             |
| 2-4       | 430             |
| 5-7       | 409             |
| 8+        | 247             |


**Visits by month:** Peak in January 2025 (1235), lowest in October 2024 (45). **Hospitalizations by month:** Peak in January 2025 (445).

**Visits by departments and types:**

| Department       | Non-Emergency | Emergency | Total |
|------------------|---------------|-----------|-------|
| Cardiology       | 823           | 458       | 1,281 |
| General Surgery  | 751           | 434       | 1,185 |
| Orthopedics      | 670           | 509       | 1,179 |
| Neurology        | 419           | 278       | 697   |
| Pediatrics       | 408           | 250       | 658   |

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/48c4ff08-2a9d-4d3c-9718-eee6f10e87a1" /> **Conclusions:** Cardiology has the highest number of visits (25.6% of the total), mostly non-emergency (64% within the department). Orthopedics has the highest percentage of emergency visits (43% within the department), likely due to trauma. Non-emergency visits dominate across all departments (an average of 61%), but Orthopedics shows a more balanced ratio (57% non-emergency vs. 43% emergency). Pediatrics has the lowest share of emergency visits (38%), which is expected given the prevalence of scheduled appointments.

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/fe11a30a-381e-4294-bd6e-1bff1546c3a1" /> **Trend:** Increasing visits in 2025, but hospitalizations decline after January. 

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/f35489d1-c8a5-4471-9b95-d5fb263625ac" /> **Recommendation:** Prepare resources for the winter peak.

* ### Provider Ratings

| Provider          | Average Rating |
|------------------|----------------|
| Dr. Olu Abisola   | 5.45           |
| Dr. Johnson Grek  | 5.05           |
| Dr. Emma Jones    | 4.85           |
| Dr. Ravi Patel    | 3.36           |
| Dr. Sade Kikiola  | 2.35           |

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/48c4ff08-2a9d-4d3c-9718-eee6f10e87a1" /> **Conclusions:** Top ratings are observed among African and European specialists, while lower ratings are seen among specialists from India and Nigeria.


<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/f35489d1-c8a5-4471-9b95-d5fb263625ac" /> **Recommendation:** Training for low-rated specialists to improve the quality of medical care (overall average ~4.2).



### Thank you for your interest in this project 🏆
