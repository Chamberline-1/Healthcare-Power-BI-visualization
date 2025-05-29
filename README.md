# Healthcare-Power-BI-visualization

![](https://github.com/Chamberline-1/Healthcare-Power-BI-visualization/blob/main/power%20bi%20image.jpg)


# Introduction
The healthcare sector generates vast volumes of data daily, particularly in relation to patient admissions, treatment patterns, and resource allocation. One of the most valuable applications of this data is in understanding patient flow, specifically the distinction between inpatients and outpatients, to support operational efficiency, planning, and quality of care.

This project focuses on the development of a Power BI dashboard that visualizes and analyzes patient admission trends, using a dataset containing the following key variables:
- Archive Date: The time period reference for patient records
- Specialty Name & Specialty HIPE: Clinical areas and their corresponding HIPE (Hospital In-Patient Enquiry) classifications
- Case Type: Indicates whether a patient was an inpatient or outpatient
- Age Profile: Categorized patient age groups
- Time Band: A breakdown of admissions over parts of the day or specific time intervals
- Patient Category: Classification as either Adult or Child

The purpose of this project is to transform this raw dataset into a comprehensive, interactive dashboard in Power BI that delivers clear, actionable insights for hospital administrators, clinical planners, and decision-makers. The dashboard is designed to:
1. Monitor patient volume trends across time, case types, and specialties
2. Identify peak hours and critical demand periods through time band analysis
3. Segment data by age profile and patient category to support demographic-based planning
4. Highlight differences between inpatient and outpatient trends, helping optimize staffing, bed management, and scheduling

By bridging raw data with visual storytelling, this project empowers healthcare professionals with the insights needed to make data-informed decisions, improve patient care delivery, and streamline resource utilization.

# Key metrics
1. Patient Volume
2. Specialty insights
3. Demographics
4. Time band analysis
5. Case type distribution

# Skills applied
1. Data cleaning and transformation
2. Data modelling using DAX
3. Data analysis
4. Data visualization and dashboard design

![](https://github.com/Chamberline-1/Healthcare-Power-BI-visualization/blob/main/power%20healthcare%20dasboard.png)


# Analysis
1. Avg/Med wait list by case type
From the dashboard, it shows that outpatient cases dominates the wait list and inpatients and day cases have lower shares. This means that the outpatients faces more challenging scheduling pressures.

2. Avg/Med wait lsit by time band and age profile
The 18+ months wait time band has the highest volume, predominantly affecting the 0–15 and 16–64 age groups. Shorter wait times (0–3, 3–6 months) show a more balanced distribution across all age profiles. What this can implicate is that prolonged delays disproportionately affect children and working-age individuals, indicating a need to prioritize these age groups in backlog reduction efforts.

3. Specialty Breakdown
Ophthalmology, Paediatric Orthopaedic, and Paediatric Respiratory Medicine have notable average wait times of approximately 34–36 days. The blank category shows a significantly higher average wait time of 80.21 days, suggesting it may be an outlier or aggregated category. These specialties may be experiencing resource constraints or higher demand, and the blank category warrants further investigation for data accuracy or hidden backlog.

Outpatient and Day Case wait lists showed a steady increase from 2018 to 2021, with notable spikes during 2020–2021.
Inpatient wait lists remained relatively stable over the same period.
The COVID-19 pandemic likely contributed to rising delays in outpatient and day case services due to service disruptions and backlog accumulation.

# Conclusion
The analysis of the Healthcare Dashboard reveals a growing strain on healthcare services, particularly in outpatient and day case categories. The total wait list has increased from 640K to 709K year-over-year, indicating a significant rise in demand or backlog accumulation.
The longest delays (18+ months) are disproportionately affecting children (0–15) and working-age adults (16–64), which could have serious implications for both long-term health outcomes and societal productivity. In contrast, shorter wait times show a more even age distribution, suggesting that urgent or manageable cases are being addressed more consistently.

Among specialties, Ophthalmology, Paediatric Orthopaedics, and Paediatric Respiratory Medicine show consistently high average wait times (34–36 days), highlighting specific areas where service delivery may be under strain. Additionally, the presence of a "(Blank)" category with an unusually high average wait time (80.21 days) points to potential issues with data categorization or a concealed concentration of delayed cases that require immediate review.

Trend analysis from 2018 to 2021 shows outpatient and day case wait lists increasing steadily, with sharp rises during 2020–2021, likely due to the COVID-19 pandemic’s impact on routine services and elective procedures. Inpatient wait lists, however, remained stable, suggesting that urgent and critical care was prioritized during the pandemic period.

Overall, the dashboard highlights a critical need for targeted backlog reduction strategies, with an emphasis on:
1. Prioritizing long-wait patients, especially in younger age groups.
2. Improving throughput in high-delay specialties.
3. Ensuring data quality to prevent blind spots in planning and resource allocation.

Addressing these issues will be essential to restoring timely access to care and improving patient outcomes in the post-pandemic healthcare environment.





