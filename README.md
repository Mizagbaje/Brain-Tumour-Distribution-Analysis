# Brain-Tumour-Distribution-Analysis
Brain Tumour Distribution Analysis using Power BI, SQL, and Excel — analyzing tumour patterns, grades, and patient demographics to support healthcare insights.


## Table of Contents

- [Project Overview](#project-overview)
- [Tools & Technologies](#tools--technologies)
- [Dataset Overview](#dataset-overview)
- [Data Preparation](#data-preparation)
- [Power BI Dashboard](#power-bi-dashboard)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)


### Project Overview
A Power BI healthcare analytics dashboard that visualizes brain tumour patient data, revealing trends in demographics, tumour types, brain regions, and diagnosis patterns over time.

### Tools & Technologies
* Excel
* Power BI


### Dataset Overview
Columns:
Patient ID,	Age,	Gender,	Tumor Type,	Tumor Grade,	Affected Brain Region,	Tumor Size (cm),	Symptoms,	Laterality,	Histology Confirmation,	Treatment Type,	Date of Diagnosis

📄 Sample Dataset Preview

| Patient ID | Age | Gender | Tumor Type       | Tumor Grade | Affected Brain Region | Tumor Size (cm) | Symptoms                                      | Laterality | Histology Confirmation | Treatment Type | Date of Diagnosis |
|------------|-----|--------|------------------|-------------|------------------------|------------------|-----------------------------------------------|------------|-------------------------|----------------|-------------------|
| P00001     | 41  | Male   | Glioma           | Grade 1     | Frontal                | 2.9              | Weakness                                      | Left       | Confirmed              | Observation    | 2022-03-04        |
| P00002     | 11  | Male   | Ependymoma       | Grade 3     | Cerebellum             | 6.8              | Balance issues, Dizziness, Coordination problems | Right      | Confirmed              | Radiation      | 2016-04-01        |
| P00003     | 23  | Male   | Pituitary Tumor  | Grade 1     | Pituitary              | 1.6              | Headache, Vision problems                     | Left       | Confirmed              | Observation    | 2015-04-13        |


### Data Preparation

Before visualization in Power BI, the dataset was:

* Cleaned to handle missing or inconsistent values

* Standardized for age groups and tumour categories

* Transformed to create calculated fields for analysis (e.g., age group ranges, yearly diagnosis counts)


### Power BI Dashboard
The Power BI dashboard includes the following key visuals and report elements:

🔢 KPI Cards (Top Summary Metrics)

These provide a quick snapshot of overall statistics:

* Total Patients – Total number of recorded brain tumour cases

* Average Age – Mean age of diagnosed patients

* Average Tumour Size – Average tumour size across cases

* Most Affected Age Group – Age range with the highest number of cases

* MADR (Most Affected Diagnosis Region) – Brain region with the highest tumour occurrence

🧬 Tumour Analysis Visuals

Donut Chart – Tumour Type Distribution
Shows the percentage breakdown of tumour types such as:

* Glioma

* Meningioma

* Pituitary Tumours

Bar Chart – Top Affected Brain Regions
Compares the number of tumour cases across brain regions:

* Pituitary

* Frontal

* Temporal
  
* Occipital

* Parietal

* Multiple regions

📈 Trend Analysis

Line Chart – Annual Patients Diagnosed
Displays year-wise trends in brain tumour diagnoses, helping identify increases or declines over time.

👥 Demographic Analysis

Column Chart – Top Affected Age Groups
Shows distribution of cases across age ranges:

* 11–20

* 21–30

* 31–40

* 41–50

* 51–60

* 60+

🎛 Filters & Interactive Controls

Case Status Toggle (Confirmed / Unconfirmed)
Allows users to filter the dashboard based on diagnosis confirmation status.

Tumour Grade Selector (Grade 1–4)
Enables filtering by tumour severity grade for focused analysis.

<img width="1347" height="752" alt="Brain Analysis" src="https://github.com/user-attachments/assets/35745109-2fd7-4aac-876b-f7da98875233" />



### Key Insights

Based on the analysis presented in the dashboard, several important patterns emerge in brain tumour distribution and patient demographics:

🧠 1. Middle-Aged Adults Are Most Affected

The **41–50 age group** shows the highest number of diagnosed cases, making it the most vulnerable demographic. This suggests that brain tumour detection and screening efforts may be especially important for middle-aged adults.

---

🧬 2. Glioma Is the Most Common Tumour Type

Among all tumour categories, **Glioma accounts for the majority of cases (≈69%)**, significantly higher than Meningioma and Pituitary tumours. This highlights Glioma as the most prevalent brain tumour type in the dataset.

---

📍 3. Pituitary Region Shows the Highest Tumour Occurrence

The **Pituitary gland** appears as the most frequently affected brain region, followed by the frontal and temporal lobes. This may indicate a higher detection rate or prevalence of tumours in hormonally significant brain areas.

---

📈 4. Diagnosis Trends Fluctuate Over Time

Annual diagnosis data shows **noticeable variation across years**, with a clear peak around the early 2020s. This could reflect improved diagnostic technology, increased reporting, or changes in environmental and health factors.

---

👥 5. Cases Concentrate in Working-Age Population

A large proportion of cases fall between **31 and 60 years**, meaning brain tumours significantly impact individuals in their prime working and family-support years, increasing the social and economic burden of the disease.

---

📏 6. Tumour Size Remains Relatively Consistent

The **average tumour size (~2.0 units)** remains fairly stable across the dataset, suggesting that tumours are often detected within a similar size range, possibly due to standardized diagnostic thresholds.

---

⚖️ 7. Distribution Across Brain Regions Is Widespread

Although the pituitary region leads, tumours are recorded across **multiple brain regions**, indicating that brain tumours are not localized to a single area and require broad diagnostic imaging approaches.



### Recommendations

Based on the patterns observed in the dashboard, the following recommendations can be considered for healthcare analysis and research planning:

🧠 1. Focus Screening on Middle-Aged Adults

Since the **41–50 age group** shows the highest number of cases, healthcare awareness programs and early screening initiatives could be more strongly targeted toward middle-aged populations to support earlier detection.

---

🧬 2. Increase Research on Glioma

With **Glioma being the most prevalent tumour type**, further research into its causes, risk factors, and treatment outcomes could have the greatest impact on improving patient care and survival rates.

---

📍 3. Prioritize Monitoring of High-Risk Brain Regions

The **pituitary, frontal, and temporal regions** appear most frequently affected. Improved imaging protocols and focused neurological evaluations in these regions may help with earlier and more accurate diagnosis.

---

📈 4. Investigate Causes Behind Diagnosis Trends

Fluctuations and peaks in yearly diagnoses suggest the need to explore:

* Changes in diagnostic technology
* Environmental or lifestyle risk factors
* Improvements in reporting and data collection

Understanding these trends can help healthcare systems prepare for future case volumes.

---

👥 5. Provide Support for Working-Age Patients

Since many cases fall within the **31–60 age range**, policies and support systems should consider:

* Workplace medical support
* Financial and insurance assistance
* Rehabilitation and long-term care planning

This helps reduce the broader social and economic impact.

---

📊 6. Enhance Data Collection and Standardization

Consistent tumour size averages suggest standardized detection stages, but more detailed data (tumour stage, treatment type, survival rate) would allow for deeper clinical insights and predictive modeling in the future.

---

🤝 7. Use BI Tools for Ongoing Healthcare Monitoring

This project demonstrates how **Power BI and data visualization tools** can help hospitals and research institutions continuously monitor disease trends, improving data-driven decision-making in healthcare.



### Dataset Source
[Download Here](https://drive.google.com/drive/folders/1NQigapYQNUd_chmjHYQVrATUoNvkGpWN)




