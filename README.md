# Ulcer-Health-Risk-Analysis-Report
Excel-Power BI Project | Ulcer Patients Data |From Raw Healthcare Data to Ulcer Risk Intelligence

### Table of Contents
* [Project Overview](#project-overview)
* [Tools & Technology](#tools--technology)
* [Dataset Overview](#dataset-overview)
* [Data Cleaning & Transformation](#data-cleaning--transformation)
* [Exploratory Data Analysis](#exploratory-data-analysis)
* [Power BI Dashboard](#power-bi-dashboard)
* [Key Metrics](#key-metrics)
* [Findings](#findings)
* [Recommendations](#recommendations)
* [Future Work](#future-work)

### Project Overview
This project focuses on the development of an Ulcer Health Risk Analysis Dashboard designed to analyze, visualize, and interpret patient data related to ulcer conditions. 
The objective of the project is to provide a clear and data driven understanding of ulcer risk factors, patient demographics, clinical indicators, and treatment patterns. 
By transforming raw healthcare data into meaningful insights, the dashboard supports informed decision making and highlights areas for early intervention 
and improved patient outcomes.
This project also represents a significant milestone in my data analytics journey, combining healthcare knowledge with analytical thinking and dashboard design.

### Tools & Technology
The following tools and technologies were used in the execution of this project:
- Power BI: for data modeling, visualization, and dashboard development
- Microsoft Excel: for initial data inspection and preprocessing
- DAX (Data Analysis Expressions): for calculated measures and key metrics
- Data Visualization Principles: to ensure clarity, consistency, and usability

### Dataset Overview
The dataset used in this project consists of patient level ulcer related data, including:
- Patient demographics (age groups)
- Clinical indicators such as BMI and hemoglobin levels
- Ulcer characteristics (depth, history, and severity)
- Pain patterns (postprandial, fasting, nocturnal, mixed)
- Medication usage (NSAIDs, aspirin, none)
The dataset provides a holistic view of ulcer risk and progression across different patient categories.

Sample Preview
| Patient ID | Age | Sex | BMI | h_pylori_status | ulcer_history | med_type | med_duration(Monthly) | smoking_status | alcohol_intake_level | pain_severity | 
|------------|-----|-----|-----|-----------------|---------------|----------|-----------------------|----------------|----------------------|---------------|
| P0001 | 26 | M | 23.4 | positive | previous | none | 0 | former | none | 2 |
| P0002 | 49 | F | 27.8 | negative | none | NSAIDs | 6 | never | moderate | 5 |
| P0002 | 63 | M | 30.2 | positive | recurrent | aspirin | 8 | current | heavy | 7 |

### Data Cleaning & Transformation
Before analysis, the dataset underwent several cleaning and transformation steps to ensure accuracy and reliability:
- Removal of duplicates and handling of missing values
- Standardization of categorical fields (e.g., ulcer depth and pain patterns)
- Creation of calculated columns and measures for averages and comparisons
- Grouping of patient ages into meaningful age ranges
These steps ensured the data was well structured and suitable for analysis in Power BI.

### Exploratory Data Analysis 
Exploratory Data Analysis (EDA) was conducted to identify patterns, trends, and anomalies within the dataset. Key observations included:
- Variations in ulcer depth across different patient stages
- Relationships between medication use and ulcer severity
- Distribution of pain patterns among patients
- Differences in ulcer history (previous, recurrent, none)
EDA played a crucial role in shaping the final dashboard design and key metrics.

### Power BI Dashboard
The Ulcer Health Risk Analysis Dashboard presents insights through an interactive and visually intuitive layout. The dashboard includes:
- Summary cards for total patients, average BMI, and average hemoglobin levels
- Charts showing ulcer depth prevalence and pain pattern distribution
- Patient distribution across medications
- Age group distribution and ulcer history analysis
- The dashboard allows users to quickly assess ulcer risk levels and understand contributing factors such as H. pylori infection, frequent NSAID use,
  and lifestyle related risks.

<img width="1194" height="666" alt="Screenshot 2026-02-10 161552" src="https://github.com/user-attachments/assets/390d53c6-e14b-4cf9-9944-f6a840f74be6" />
<img width="1182" height="667" alt="Screenshot 2026-02-10 161613" src="https://github.com/user-attachments/assets/23f2a7f6-838a-492b-9014-ae0548304f44" />
<img width="1190" height="664" alt="Screenshot 2026-02-10 161636" src="https://github.com/user-attachments/assets/2bed9918-477b-47ef-abb4-74128aaa7b53" />
<img width="1192" height="665" alt="Screenshot 2026-02-10 161702" src="https://github.com/user-attachments/assets/8f1d5874-f4bf-445d-afc5-351d4f769ea8" />

### Key Metrics
Key metrics tracked in the dashboard include:
- Total number of patients
- Average Body Mass Index (BMI)
- Average hemoglobin level
- Ulcer depth prevalence (superficial, deep, very deep)
- Pain severity and patterns
- Medication usage distribution
These metrics provide a concise snapshot of patient health status and ulcer risk.

### Findings
From the analysis, the following insights were observed:
- A significant proportion of patients present with superficial to deep ulcers
- NSAID usage is common among patients with higher ulcer severity
- Postprandial pain is the most frequently reported pain pattern
- Certain age groups show higher ulcer prevalence
- Recurrent ulcer cases indicate the need for improved preventive care

### Recommendations
Based on the findings, the following recommendations are proposed:
- Encourage early screening for high-risk patients
- Reduce unnecessary NSAID usage and promote safer alternatives
- Improve patient education on ulcer risk factors and lifestyle changes
- Use data driven dashboards to support continuous monitoring and decision-making

### Future Work
Future improvements to this project may include:
- Integration of real time or larger clinical datasets
- Inclusion of additional clinical variables such as diet and smoking history
- Predictive modeling to estimate ulcer risk levels
- Enhanced interactivity and drill through analysis within the dashboard
