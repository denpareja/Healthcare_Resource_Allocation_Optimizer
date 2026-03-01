# Healthcare Resource Allocation Optimizer
Data-driven framework that identifies high-priority counties for healthcare resource allocation by analyzing preventable hospitalization risk and physician supply gaps.

---

## 1. Executive Summary
This project develops a data-driven prioritization framework to identify geographic regions that require urgent healthcare resource allocation. By integrating hospitalization risk indicators with physician supply metrics, the model highlights counties where high clinical burden coincides with limited provider availability. The final output is a prioritization score that supports strategic healthcare planning and policy decision-making.

---

## 2. Business Problem
Healthcare systems frequently struggle to allocate resources efficiently due to fragmented data across clinical outcomes and workforce capacity. Decision-makers need a structured, objective method to identify where physician shortages intersect with high patient risk.

Key question:
**Which counties should be prioritized for healthcare resource investment?**

---

## 3. Dataset Overview
Two public healthcare datasets were integrated:

**Dataset 1 — Preventable Hospitalizations**
- County
- Year
- Risk-adjusted hospitalization rate
- Population counts
- Clinical condition indicators (PQIs)

**Dataset 2 — Physician Supply Metrics**
- County
- Physician supply rates
- Length of stay indicators
- Comparative benchmarks

The datasets were merged by county to build a unified analytical dataset combining outcome burden and workforce capacity.

---

## 4. Analytical Approach
The project follows a structured analytics pipeline:

**Data Preparation**
- Standardized column names
- Handled missing values
- Filtered relevant metrics
- Validated join consistency

**Feature Engineering**
- Aggregated risk metrics by county
- Created standardized z-scores
- Built composite priority score:

Priority Score = Risk Level − Physician Supply Level

**Model Logic**
Counties rank higher when:
- hospitalization risk is high
- physician supply is low

**Visualization Layer**
- Scatter analysis
- Log-scale distribution plots
- Priority ranking charts
- Quadrant classification analysis

---

## 5. Key Insights
- Counties with the highest hospitalization risk are not always those with the lowest physician supply.
- A subset of counties shows **critical imbalance**: high risk + low provider availability.
- Resource gaps are clustered rather than randomly distributed.
- Physician supply varies widely across counties, suggesting structural inequities in healthcare access.

---

## 6. Strategic Recommendations
Healthcare leaders could use this framework to:

- Prioritize funding allocation to underserved counties
- Deploy mobile clinics or telehealth services strategically
- Incentivize physician placement programs
- Plan workforce distribution based on risk burden

---

## 7. Business Impact
If implemented operationally, this model enables organizations to:

- Reduce preventable hospitalizations
- Improve population health outcomes
- Optimize provider distribution
- Increase ROI of healthcare investments

Instead of reactive resource allocation, organizations can shift toward **predictive planning**.

---

## 8. Tools Used
- Python
- pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Statistical standardization methods
- Feature engineering techniques

---

## 9. Executive Takeaway
This project demonstrates how integrated healthcare analytics can transform raw public data into strategic decision intelligence. By combining risk metrics with workforce supply indicators, organizations gain a clear, quantitative roadmap for targeted intervention.

---

## 10. Consulting Relevance
This project reflects real-world consulting work typically performed in:

- healthcare strategy firms
- public health agencies
- policy analytics teams
- health system operations consulting

It demonstrates the ability to:

✔ translate business problems into analytical frameworks  
✔ build decision-ready metrics  
✔ integrate multiple data sources  
✔ communicate findings at executive level  

---

## Author:  
# Denisse Pareja  
Healthcare Analytics Consultant | Data Scientist

Specialized in building decision-driven analytics systems that translate data into strategic insight for healthcare and operational organizations.

LinkedIn: https://linkedin.com/in/TUURL
GitHub: https://github.com/denpareja

---

## Portfolio Note
This project is part of a professional analytics portfolio focused on developing decision-intelligence frameworks that help organizations move from descriptive reporting to predictive and strategic analytics.