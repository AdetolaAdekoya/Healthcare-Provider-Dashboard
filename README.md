# Healthcare-Provider-Dashboard


# Project Overview 
This project presents a Power BI dashboard designed to analyse hospital billing data across differetn segments like: diagnoses, departments, and medical procedures. The dashboard helps healthcare stakeholders understand cost distribution, patient utilization patterns, and areas driving the most revenue or expenditure.

# Objective
•	To monitor and analyse hospital billing performance across different dimensions.

•	To identify diagnoses, departments, and procedures contributing most to billing.

•	To support data-driven decision-making for cost optimization and efficiency improvements.


# Dataset
The dataset used in this dashboard contains informations like:

•	Billing information: total billing amount, medication cost, treatment cost, insurance coverage, room charges, and out-of-pocket amounts.

•	Patient details: demographics and location.

•	Clinical data: diagnoses, service types (inpatient, outpatient, emergency), departments, and procedures.


# Tools Used

•	Power BI was used for interactive dashboard creation.

•	Power Query for cleaning, transforming, and preparing the dataset.

•	DAX (Data Analysis Expressions) for calculating measures such as average costs, departmental contributions, and procedure-level billing totals.


<img width="1058" height="562" alt="dashboard org" src="https://github.com/user-attachments/assets/79b7634f-2dca-4ff0-80e3-58409bf65509" />



# Analysis Approach 

1.	Data Cleaning & Transformation – We used Power Query to remove inconsistencies, handle blanks, and structure the dataset for reporting.
   
2.	Data Modelling – We established relationships across patient, billing, department, and procedure tables.
   
3.	Calculation Layer – We built DAX measures for KPIs such as total billing, average medication cost, insurance coverage, and department/procedure contributions.
   
4.	Dashboard Development – We created interactive visuals with filters (e.g., by city or patient location).

# Visualization
The dashboard features several key visuals such as:

1.	Total Billing Amount by Diagnosis and Service Type
   
*	Shows how billing varies by diagnosis (e.g., hypertension, asthma, appendicitis).

*	Breaks down cost distribution by service type (inpatient, outpatient, emergency).

*	Example: Fracture cases are largely billed as inpatient (32.69%), while asthma and migraine shows significant emergency and outpatient costs.


<img width="327" height="181" alt="amount by diagnosis" src="https://github.com/user-attachments/assets/35eb311f-b0a1-43e2-bd43-b87397b91394" />



3.	Total Billing Amount by Department
   
*	Displays departmental contributions to billing (e.g., cardiology, neurology, pediatrics).

*	Cardiology (26.7%) is the highest contributor at £348,212.00 followed by Orthopaedics with (24.3%) at £316,667.00.

*	A blank measure is used here as a placeholder in Power BI to improve formatting and layout.
*	


<img width="310" height="177" alt="amount by dept" src="https://github.com/user-attachments/assets/0c4b8f24-df4e-4e1e-90c7-a74c3c309546" />


4.	Total Billing Amount by Procedure
   
*	Breaks down billing by medical procedures.

*	CT Scans (£9,687, 31%) drive the highest billing, followed by Ultrasound (£6,761, 22%) and MRI (£5,642, 18%).

*	This helps identify high-revenue or cost-intensive procedures.
*	

<img width="608" height="217" alt="amount by procedure" src="https://github.com/user-attachments/assets/8d6220c1-075c-40ac-bcf1-2a13f9020c33" />



## Key Insights and Findings

Strong Billing Performance: Total hospital billing reached **£1M** across \~2,000 patients, with average out-of-pocket expenses at just **£204.7** per patient despite substantial insurance coverage.
* **Cost Drivers:** **Treatment (£1M)** and **medication (£22K)** dominate overall costs, while **room charges (£29K)** remain minimal.
* **Diagnosis & Service Mix:** Hypertension and Appendicitis are heavily **outpatient-driven (>50%)**, while Asthma shows a balanced spread across emergency, inpatient, and outpatient care.
* **Departmental Impact:** **Cardiology (£348K, 26.7%)**, **Orthopedics (£317K, 24.3%)**, and **General Surgery (£292K, 22.4%)** together account for over **70% of total billing**.
* **Procedural Insights:** Imaging dominates costs—**X-Rays (£418K, 32%)** and **CT Scans (£319K, 24%)** lead the way—making diagnostic services the primary billing contributor.
