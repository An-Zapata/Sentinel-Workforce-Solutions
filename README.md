### Project Overview
This project analyzes environmental health and safety (EHS) incident data from Sentinel Workplace Solutions, with the goal of identifying key trends, risk factors, and compliance gaps that contribute to workplace incidents. By leveraging data visualization and statistical insights, this analysis provides actionable recommendations to help Sentinel reduce incident frequency, improve safety training effectiveness, and foster a proactive workplace safety culture. A centralized dashboard was developed to showcase critical metrics, including incident trends over time, industry and location-based risk assessments, employee compliance behavior, and near-miss reporting patterns. This report synthesizes the insights gained from the data and outlines high-impact, data-driven strategies for mitigating workplace risks and improving EHS compliance across Sentinel’s nationwide job sites.

### Objectives

1. **Incident Dimension Exploration**: To analyze workplace incidents across *time, location, and severity* to identify trends, high-risk seasonality, and geographic hotspots for targeted safety interventions.
2. **Employee Compliance Behavior**: To assess the impact of training completion and near-miss flagging on incident frequency and severity, providing insights into workplace safety compliance.
3. **Risk Analysis**: To detect patterns in incident severity and compliance gaps, enabling resource allocation to high-risk areas and industries for proactive risk management.

### Data Description
This dataset represents workplace incident reports from Sentinel Workplace Solutions, covering a nationwide network of job sites across multiple industries from **2022 to 2024**. Each entry corresponds to a **reported workplace incident**, capturing key details such as incident type, location, severity, compliance factors, and employee training status. The data is structured to support a **comprehensive safety analysis**, enabling an exploration of **incident trends, employee compliance behavior, and risk patterns**. It includes metrics related to incident severity (levles of severity and days lost), near-miss flagging, and training completion, allowing us to assess how compliance measures influence safety outcomes.

This dataset was inspired by Public Health EHS and workplace incident datasets on [Kaggle](https://kaggle.com/datasets), but is ultimately an AI-generated dataset to create a focused analysis for this project.

![Image](https://github.com/user-attachments/assets/88824d8b-71e3-4e09-ac11-a29edff4ce67)

## Sentinel Workplace Solutions: Workplace Incident Analysis & Recommendations

### Executive Summary
This analysis uncovers key patterns in Sentinel Workplace Solutions workplace incident data across time, location, industry, and employee compliance factors, revealing seasonal spikes, industry-wide safety challenges, and training gaps that contribute to severe injuries.

- **Incident Frequency & Seasonal Risk Patterns:** Incidents show a seasonal spike in Q4, particularly in November and December, suggesting end-of-year operational stressors or environmental risks. Additionally, April, despite having lower incident counts, exhibits the highest severity in lost workdays per incident, indicating potential unaddressed workplace hazards.
- **Industry & Location-Based Risks:** Sentinel corporate offices and retail stores experience comparable incident severity levels to traditionally high-risk environments like warehouses and factories, highlighting the need for equal safety intervention efforts across all workplace settings. Additionally, San Jose records the highest average days lost per incident, while Dallas has the highest total incidents, emphasizing the need for location-specific safety strategies.
- **Training & Compliance Gaps:** 92% of severe incidents occurred among employees who had not completed safety training, reinforcing the critical role of compliance programs in preventing high-severity injuries. Additionally, near-miss flagging remains inconsistent, with incidents lacking a near-miss flag occurring more frequently, particularly in retail environments, where proactive risk identification is weaker.

### Key Insights
**Incidents Over Time**
- **2022:** Incident counts remained below the annual average of 419 incidents for most of the year, until a **sharp increase in Q4**, peaking in **November at 963 incidents**.
- **2023:** The year saw an **unexpected spike in February, with 715 incidents**, well above the 398-incident annual average. Q4 **continued** to reflect **seasonal volatility**, though with slightly lower peaks compared to 2022.
- **2024:** The year began with relatively stable incident rates, with monthly incidents remaining below the 432-incident average through June. However, Q4 again followed historical trends, with October experiencing a spike and December peaking at 828 incidents, reinforcing the recurring end-of-year risk period.

**Incidents by Other Dimensions**
- **By Industry:** Incident distribution across corporate offices, factories, retail stores, and warehouses suggests a consistent level of injury risk across all workplace environments. The range of total incidents across industries follows an expected distribution, where retail stores (2,268 injuries) and corporate offices (2,993 injuries) are lower, and warehouses (4,494 injuries) and factories (5,210 injuries) are on the higher end of the range.
- **By Severity:** Despite the expected **higher incident counts in factories and warehouses**, the severity distribution remains proportionally similar across industries, suggesting that all workplace environments—regardless of industry—pose comparable injury risks.
- **By City:** Analysis of incident distribution across cities highlights key locations with above- and below-average incident rates: **Dallas, San Jose, and New York** have **above-average incident counts** compared to the national dataset. **San Jose has the highest average days lost per incident**, suggesting **longer recovery times or more severe injuries** in this location. **Phoenix and Chicago** have **below-average total incidents**, however, Phoenix has one of the **highest variabilities in average days lost** across months, suggesting **sporadic but severe injuries** rather than frequent minor incidents. This pattern may indicate a **small number of high-severity incidents driving up the average** rather than consistent workplace risks

**Compliance Behavior**
- **Training Completion:** Training completion data reveals a contrasting pattern in its effectiveness at preventing injuries of different severities. **Minor and moderate incidents** were **more frequently reported** among employees who had **completed safety training** compared to those who had not. **Severe incidents**, however, show a **drastic shift—a significant 92%** of all severe incidents were **reported by employees who had not completed the required training**.
- **Near-Miss Flagging:** Near-miss flagging data suggests a correlation between unflagged incidents and higher incident frequency as incidents that did not have a near-miss flag attached occurred at a higher frequency than those that did. Additionally, Near-miss flagging consistency over time – No significant quarterly fluctuations in near-miss reporting patterns were observed.

**Risk Analysis**
- **Rising Incident Averages:** The **yearly average number of incidents has increased**, with 2024 recording the **highest annual average** over the three-year period. This indicates a **potential upward trend in workplace incidents**.
- **April as a Unique Risk Period:** While **April consistently records the low incident prevalence** (well **below the three-year average** of 1,248 incidents, with a mean of **615 incidents**), it exhibits a **disproportionately high number of lost workdays per incident**. This suggests that while **fewer incidents** occur in April, they tend to be **more severe**.
- **Near-Miss Underreporting:** Incidents that lacked a **near-miss flag were more frequent**, suggesting that **proactive risk identification** is **not consistently practiced** and needs to be effectively implemented in order to prvent future incidents.
- **High-Risk Cities:** **San Jose** has the **highest average days lost** per incident and **Dallas** has the **highest total incidents**, which may indicate **more severe injuries, slower return-to-work processes, or operational risks** that require further investigation.

- ![Image](https://github.com/user-attachments/assets/3ad419a4-23a9-4900-9ecf-1558ebc0ca66)

## Recommendations

1. ### Implement a Comprehensive Incident Reduction Program

Develop a multi-dimensional safety initiative that systematically addresses incident frequency across time, location, industry, and compliance gaps. This program should be data-driven and adaptive, targeting high-risk periods, industries, and reporting inconsistencies.

**Key Componets**
- **Seasonal Risk Mitigation:** Allocate additional safety monitoring and compliance enforcement during historically high-risk periods (Q4 spikes in November-December and April’s severity surge) to preemptively reduce incidents.
- **City-Specific Safety Interventions:** Deploy localized risk strategies for high-incident areas like San Jose and Dallas by utilizing best practices in lower-incident locations such as Phoenix to sustain improvements.
- **Industry-Specific Safety Enhancements:** Reevaluate safety measures and focus research in corporate offices and retail stores to evaluate the underlying causes of unusually high incident risk.
- **Standardize Injury Reporting:** Implement a comprehensive injury classification framework across all industries to eliminate reporting bias and inconsistencies.

2. ### Strengthen Training Compliance for High-Risk Incidents

- **Expand Targeted Training Programs:** Increase training participation and compliance enforcement for employees in chemical exposure, equipment-related, and ergonomic injury risk roles with the objective to prevent severe workplace injuries and reduce lost workdays.

- **Reinforce Safety Training for Incident Prevention:** Strengthen minor training engagement and accountability for all employees to minimize life-threatening incidents and long-term disability claims.

3. ### Embed Proactive Risk Identification in Safety Culture

- **Mandate Near-Miss Reporting for Improved Hazard Detection:** Enforce stricter near-miss reporting policies, particularly in retail environments, where flagging rates are lowest with the aim to ensure that near misses are captured will help preempt serious incidents before they escalate.

- **Optimize Safety Monitoring During High-Risk Periods:** Proactively identify and address critical risk periods, such as Q4 (November-December) and April, by allocating additional safety resources and strengthening compliance monitoring during these high-incident months. This targeted approach will mitigate preventable injuries, minimize operational disruptions, and enhance workplace safety during historically high-risk periods.

### Summary
By implementing these targeted, data-driven safety initiatives, Sentinel Workplace Solutions can improve injury classification accuracy, enhance training participation in high-risk categories, and embed proactive risk identification into workplace culture. These strategies will drive measurable reductions in workplace incidents, improve compliance, and optimize resource allocation for long-term safety and operational efficiency.

