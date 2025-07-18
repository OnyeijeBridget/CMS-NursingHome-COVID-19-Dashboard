# CMS-NursingHome-COVID-19-Dashboard

This project presents a comprehensive analysis of the CMS Nursing Home COVID-19 dataset, leveraging Excel as a full-stack analytics tool to assess facility-level data integrity, vaccination performance, and public health outcomes across U.S. states. The dataset—known for its complexity and reporting inconsistencies—was subjected to rigorous cleaning and quality assurance filtering, reducing 14,791 raw records to a trusted analytical base of 62% high-quality entries.

Using Power Query, I implemented rule-based data exclusion to remove nulls, invalid provider IDs, and non-submitted reports, preserving only QA-compliant facilities. 
Key metrics, such as up-to-date staff and resident vaccination rates, confirmed weekly COVID-19 cases, and QA pass distributions, were engineered using robust DAX measures and dynamically linked PivotTables.

The resulting multi-page dashboard visualizes the top 20 states by COVID-19 burden and vaccination rates, uncovers potential reporting bias due to data retention thresholds, and provides actionable insights for data quality improvement. Special attention was given to filtering logic, denominator integrity in percentage calculations, and the risk of overestimating performance post-cleaning.

This project reflects a strong grasp of healthcare data analysis, Excel modeling, and the importance of data quality in operational reporting. It exemplifies stakeholder-driven analytics—translating messy public health data into credible, insight-ready visuals for performance monitoring, benchmarking, and strategic planning.



**Portfolio Analysis Questions**

 1. Which states or facilities reported the highest number of confirmed COVID-19 cases and deaths
 during the reporting week?

 2. What percentage of residents and staff are up to date with their COVID-19 vaccinations across
 facilities and states?

 3. Which facilities or states had the highest case fatality rates (deaths ÷ confirmed cases), and what
 might explain those differences?
 
 4. Are there any data quality or reporting gaps that could affect the accuracy of this week's
 numbers?
