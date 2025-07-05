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
1.	How does the distribution of healthcare facilities compare between rural and urban regions?

![first](https://github.com/user-attachments/assets/319b21db-d6c6-486e-8d7c-f9a599299f41)

	Urban Areas: There are significantly more healthcare facilities here:
•	Clinics: 472
•	Health Centers: 431
•	Hospitals: 393
	Rural Areas: There are fewer facilities compared to urban regions:
•	Clinics: 224
•	Health Centers: 248
•	Hospitals: 232
Key Insight: Urban areas have considerably more healthcare facilities than rural areas, which highlights a disparity in healthcare access. This difference might mean that rural communities have limited access to healthcare services. It emphasizes the need to invest more in rural healthcare infrastructure to bridge this gap.

2.	Are urban healthcare facilities receiving more funding than rural ones?

![image](https://github.com/user-attachments/assets/d7836c19-0357-4972-aed9-632898523014)



Urban facilities receive higher funding across all types:
•	Clinics: $52 million
•	Health Centers: $46 million
•	Hospitals: $40 million
Rural facilities receive considerably less funding:
•	Clinics: $24 million
•	Health Centers: $27 million
•	Hospitals: $25 million
Key Insight: Urban areas get much more funding for healthcare facilities compared to rural areas, regardless of the type of facility. This indicates an unequal distribution of resources, potentially leading to better healthcare services in urban areas while rural areas struggle with limited support.




