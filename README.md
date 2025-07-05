# Healthcare-Access-In-Africa
# INTRODUCTION
This analysis aims to explore the healthcare facility data, identify disparities in access to healthcare accessibility between rural and urban regions. The objective is to propose data-driven recommendations that governments and stakeholders can implement to enhance healthcare service delivery across Africa.

Interact with the Power BI dashboard ####

# PROBLEM STATEMENT 💡
Access to quality healthcare remains a significant challenge in Africa, with stark disparities between rural and urban regions. These inequities highlight inefficiencies in healthcare funding and resource allocation, preserving a cycle of unequal access.  This case study seeks to uncover the root causes of these disparities, evaluate the effectiveness of current healthcare funding models, and propose actionable solutions to ensure equitable healthcare access for all Africans, regardless of their location.

# OBJECTIVES 🎯
1. Identify Disparities: Analyze the distribution of healthcare facilities, workforce availability, and patient accessibility to highlight key differences between rural and urban regions.  
2. Evaluate Funding Efficiency: Assess how healthcare funding is allocated and its impact on service delivery, particularly in underserved areas.  
3. Improve Service Delivery: Provide data-driven insights to enhance emergency response times, patient satisfaction, and overall healthcare outcomes.  
4. Propose Policy Recommendations: Develop actionable strategies for governments and stakeholders to bridge the gap between rural and urban healthcare services.  
5. Optimize Resource Allocation: Suggest ways to maximize the impact of healthcare funding in underserved regions to ensure equitable access for all.

# METHODOLOGY ✈
POWER BI: Used to create visualizations, such as bar charts, pie charts, line charts, scatter plots, and tree maps, to represent the data visually and make it easier to understand and interpret.
•	Load in our data
•	Transform data (Create a new column for demography)
•	Close and apply
•	Create visuals to know our findings.
DATA TRANSFORMATION
To prepare the Healthcare accessibility in Africa dataset for analysis by performing data cleaning and transformation tasks using Power BI. The process includes handling duplicates, missing values, and ensuring data consistency across various columns.
Extract, Load and Transform (ELT)
Data Import and Table Creation
Importing Data: The dataset was loaded into Power BI from the provided CSV file containing 2,000 records and 15 columns.
Data Structure: The dataset includes information on healthcare facilities, including location, facility type, and number of medical staff, patient visits, response times, funding, infrastructure availability, and patient satisfaction rates.

# Transform:  
1. Identifying and Handling Duplicates
Checking for Duplicates: The dataset did not contain duplicates in any column.
2. Handling Missing Values	
Identifying Missing Values:
The dataset did not contain missing values in any column.
Further checks were done to ensure completeness
3. Standardizing Data
Standardizing Categorical Values:
The Facility Type column was reviewed to ensure uniform naming conventions (e.g., “Clinic,” “Hospital,” “Health Center”).
Date Formatting: Although no date columns exist in the dataset, numerical and categorical data were formatted properly already.
4. Creating New Columns
•	The creation of the “urban_Rural Areas” Column was created. The classification into Urban or Rural was based on the following existing columns: population density, Electricity availability and Internet availability. Where population >=5000 (which represents an estimated value of the average population) “Urban”, else “Rural”. For electricity and internet availability, where “yes” = “Urban”, else “Rural”.
•	The Efficiency measure was created to evaluate how effectively healthcare facilities use their allocated funding. It is calculated by dividing the funding received by the annual patient visits.
# Load
Final Process and Data Validation
•	The cleaned and transformed data was reviewed for accuracy and completeness.
•	Power BI was used to create visualizations that depict insights from the cleaned dataset, ensuring the data was ready for analysis.

# KPI OVERVIEW 💼
To measure progress and evaluate the effectiveness of healthcare accessibility initiatives, the following Key Performance Indicators (KPIs) will be tracked:
*	Total Number of Doctors
*	Total funding received by all health facilities
*	Population recorded
*	Annual patient visits
These KPIs will provide a comprehensive framework to monitor progress, identify gaps, and ensure that interventions are effectively improving healthcare accessibility and quality across Africa.

# Key Business Questions ❓
1. How does the distribution of healthcare facilities compare between rural and urban regions?

![image](https://github.com/user-attachments/assets/082591ad-3353-46a8-9178-eb163e9ead66)

Urban Areas: There are significantly more healthcare facilities here:

*	Clinics: 472
*	Health Centers: 431
*	Hospitals: 393

Rural Areas: There are fewer facilities compared to urban regions:

*	Clinics: 224
*	Health Centers: 248
*	Hospitals: 232

Key Insight: Urban areas have considerably more healthcare facilities than rural areas, which highlights a disparity in healthcare access. This difference might mean that rural communities have limited access to healthcare services. It emphasizes the need to invest more in rural healthcare infrastructure to bridge this gap.

2. Are urban healthcare facilities receiving more funding than rural ones?

![image](https://github.com/user-attachments/assets/43a97f35-f242-4785-ac2e-0c6c4d136151)

Urban facilities receive higher funding across all types:
*	Clinics: $52 million
*	Health Centers: $46 million
*	Hospitals: $40 million

Rural facilities receive considerably less funding:
*	Clinics: $24 million
*	Health Centers: $27 million
*	Hospitals: $25 million

Key Insight: Urban areas get much more funding for healthcare facilities compared to rural areas, regardless of the type of facility. This indicates an unequal distribution of resources, potentially leading to better healthcare services in urban areas while rural areas struggle with limited support.

3. Are healthcare facilities with higher funding more likely to have shorter emergency response times?

![image](https://github.com/user-attachments/assets/a64ca9f8-8fdc-4e45-b2e9-d9f9d01832aa)

>	Clinics:
*	Received the most funding: $75 million.
*	Have the quickest response time: 32 minutes.
>	Health Centers:
*	Received $70 million in funding.
*	Have the slowest response time: about 32.6 minutes.
>	Hospitals:
*	Received the least funding: $65 million.
*	Their response time is slightly faster than Health Centers: about 32.4 minutes.

Key Insight: Clinics stand out because they receive the highest funding and also have the fastest response times. Health Centers, despite receiving more funding than Hospitals, are the slowest in responding. This could mean that factors beyond funding, such as resource management or operational structure, might be affecting their response time.

4. Which facility types (hospitals, clinics, health centers) show the highest efficiency in terms of funding per patient visit?

![image](https://github.com/user-attachments/assets/aa37cda8-28d4-4307-b349-ad71fe2d2ff3)

Efficiency Scores:

*	Health Centers and Clinics: Both have the highest efficiency score of 10.1, making them equally efficient.
*	Hospitals: Have a slightly lower efficiency score of 10.0, but the difference is very minimal.

Key Insight: The scores indicate that all three types of facilities operate at very high efficiency levels. However, Health Centers and Clinics are marginally more efficient than Hospitals.

Critical factors preventing equal access to healthcare across different regions?

1.  Population: Urban areas, with approximately 9 million residents, enjoy better access to healthcare facilities compared to rural regions, where a population of 2 million is scattered across large areas. This disparity creates significant challenges in delivering quality healthcare services and results in unequal access.
2.  Funding: Urban healthcare facilities benefit from a substantially larger share of funding, receiving $138 million, while rural facilities, allocated only $75 million, struggle to provide adequate services. This imbalance severely impacts healthcare quality in rural areas.
3.  Internet and Electricity: Rural healthcare centers often face infrastructure challenges, with 982 facilities lacking a reliable electricity supply and 1,029 facilities suffering from unstable internet connectivity. These limitations hinder their ability to deliver consistent care and utilize modern digital health tools.
4. Doctors and Nurses: Urban facilities have a disproportionate concentration of medical professionals, recording over 13,000 doctors, whereas rural facilities have just over 7,000. This unequal distribution makes it difficult for rural areas to attract and retain skilled healthcare workers.

POLICY RECOMMENDATION TO BRIDGE THE GAP BETWEEN URBAN AND RURAL FACILITIES

I. Funding: Urban healthcare facilities benefit from significantly higher funding, but policies should aim to distribute resources more equitably. A needs-based funding approach, with additional support for rural facilities, can be achieved through targeted government grants or subsidies.

II. Electricity and Internet Access: Rural healthcare facilities often lack reliable electricity and internet services. Infrastructure improvement policies, such as expanding electrical grids to rural areas or subsidizing solar power solutions, can address these issues. Collaborations with telecom companies could ensure affordable internet access for telemedicine services.

III. Technological Advancements: Telemedicine offers a solution to bridge the gap between rural and urban healthcare access. Investments in telemedicine infrastructure, including equipment and staff training, are essential. Additionally, mobile health units could deliver temporary medical services to remote areas.

IV. Workforce Training and Retention: Attracting healthcare professionals to rural facilities requires incentives like loan forgiveness for medical graduates, competitive salaries, and housing benefits. Training programs focused on rural healthcare challenges can further strengthen retention efforts.

How can governments optimize healthcare funding allocation to maximize impact in underserved regions?

*	Data-Driven Decision Making: Use comprehensive data to identify underserved areas, predict outbreaks and prioritize funding based on health needs, disease burden and population demographics.
*	Monitor and Evaluate: Continuously assess the impact of funding allocations to ensure resources are being used effectively and adjust strategies as needed.
*	Strengthen Rural Health Workforce Financial Incentives: Offer scholarships, housing subsidies, or loan forgiveness for doctors/nurses working in underserved regions.

RECOMMENDATIONS

*	Urban areas have significantly more healthcare facilities compared to rural regions, where fewer clinics struggle to meet the needs of scattered populations. To close this gap, building mid-tier health centers in underserved rural areas should be prioritized, alongside the deployment of low-cost mobile clinics to reach remote communities.
*	Urban healthcare facilities receive 40-60% more funding than rural ones, leading to resource disparities. Governments should adopt a needs-based funding model, allocating at least 30% of health budgets to rural infrastructure, such as solar power and internet, to promote equitable healthcare access.
*	Enhancing emergency response times in rural areas can be achieved through the training of local first responders, improving transportation with ambulances and motorcycles, and utilizing GPS tracking to optimize emergency dispatch systems. These measures are cost-effective and lifesaving.
*	To improve healthcare efficiency, governments should focus on expanding primary care clinics that deliver high-volume, low-cost services in underserved areas. Structured referral systems should be implemented to reserve hospitals for complex cases, while performance-based funding can incentivize clinics to maintain quality care and cost-effectiveness.

CONCLUSION

Urban regions have better healthcare access due to more facilities, funding, and infrastructure, while rural areas face shortages in resources, staff, and basic utilities. Addressing this requires equitable funding, improved rural infrastructure, telemedicine initiatives, and workforce incentives to bridge the gap and ensure quality healthcare for all.




