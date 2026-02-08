# 🏥 Hospital Readmissions & Utilization Analytics

## 📌 Project Overview
Healthcare providers often need a structured view of hospital utilization and patient readmissions to improve operational efficiency and patient outcomes.  
In a simulated LeonDab Hospital scenario, leadership sought insight into 30-day readmission patterns, patient flow, and length-of-stay variations across demographics and clinical pathways.

This project delivers an end-to-end SQL–Power BI analytics solution that transforms hospital encounter data into an interactive dashboard supporting data-driven clinical and operational decisions.

---

## 🎯 Business Objectives
- Monitor 30-day hospital readmission performance  
- Understand patient utilization and length-of-stay patterns  
- Identify demographic segments with elevated readmission risk  
- Examine clinical and discharge-related drivers of repeat visits  
- Provide executive-level monitoring of hospital performance trends  

---

## ❓ Business Questions
- What is the overall 30-day readmission rate?  
- Which demographic groups show higher readmission risk?  
- How does length of stay vary across diagnoses and discharge types?  
- Which clinical pathways influence readmission outcomes?  
- Are there utilization patterns indicating operational inefficiencies?  

---

## 🗂 Dataset Overview
- **Type:** Simulated Hospital Readmissions Dataset  
- **Structure:** Patient-level encounter data  
- **Row Count:** *1500*  
- **Time Coverage:** *Feb 2026*  

### Key Fields
- patient_id  
- age  
- sex  
- insurance  
- diagnosis  
- visit_date  
- length_of_stay  
- discharge_type  
- readmitted_within_30d  
- readmission_date  
- comorbidity_score  

> Note: Dataset is synthetic and used strictly for analytics demonstration.

---

## ⚙️ Data Preparation & Modeling
- SQL used to create analytical base views  
- MySQL database connected to Power BI via ODBC  
- Star-schema data modeling approach  
- Custom Date Table created for time intelligence  
- Dedicated DAX Measures Table for KPI management  
- Data validation performed on readmission and LOS fields  

---

## 📊 Key Metrics
- Total Patients
- 30-Day Readmission Rate
- Median Length of Stay
- Average Length of Stay (LOS)      
- Long-Stay Patients  

---

## 📈 Dashboard Structure

### 🟦 Page 1 — Executive Overview
Purpose: Provide a high-level snapshop of readmission patterns, patient flow, and lenght-of-stay trends.

Key Visuals:
- KPI Cards: Total patients, Readmission rate, Median LOS, Avg LOS, Long-stay patients
- Readmission rate by gender
- Long-stay patients by insurance type
- Monthly Trend Analysis (with long-stay trend as secondary axis) 
- Patient distribution by length of stay

Insights Supported
- Overall readmission burden
- Temporal patient trends
- LOS distribution pattens
- High-level risk segmentation

---

### 🟩 Page 2 — Patient Demographics and Clinical Profile
Purpose: Explore how demographic and clinical characteristics relate to LOS and readmissions.

Key Visuals:
- Length of stay by Age group
- Readmission rate by Age group
- Diagnosis distribution by Gender
- Average comorbidity score by LOS category
- Patient distribution by Age group and Gender

Insights Supported
- Age-related hospitalization patterns
- Clinical complexity vs LOS
- Demographic disparities in diagnosis and care outcomes

---

### 🟥 Page 3 — Clinical Drivers & Operational Factors
Purpose: Identify operational and clinical factors associated with readmissions.

Key Visuals:
- Diagnosis vs Readmission within 30 days
- Discharge Type Analysis  
- Comorbidity Influence  
- Insurance & Gender Risk Patterns  

Insights Supported
- Impact of discharge planning on readmissions
- Insurance-linked operational risks
- Diagnosis-specific readmission drivers
- Clinical pathways optimazation opportunities

---

## 💡 Analytical Value
- Identification of patient segments with higher readmission risk  
- Visibility into operational utilization patterns  
- Insights into discharge and diagnosis-related outcomes  
- Executive-level monitoring of hospital performance  

---

## 🛠 Tools & Technologies
- MySQL (SQL Data Preparation)  
- Power BI (Data Modeling & Visualization)  
- DAX (Measures & Calculations)  
- Healthcare Analytics Framework  

---

## ⚠️ Limitations
- Synthetic dataset (not real patient data)  
- Simplified clinical definitions  
- No predictive modeling included  
- Financial cost analysis not implemented  

---

## 🚀 Future Improvements
- Predictive readmission risk modeling  
- Cost and financial impact analytics  
- Integration with real-world EHR datasets  
- Survival and cohort analysis  
- Advanced clinical outcome modeling  

---

## 📷 Dashboard Preview
![Overview Dashboard](images/overview.png)

---

## 👤 Author
Pantaleon Akujobi  
Healthcare & Data Analytics Projects

