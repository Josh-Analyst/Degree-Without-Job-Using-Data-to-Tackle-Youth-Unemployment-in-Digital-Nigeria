# 🎓 Degree Without Job: Youth Unemployment in Digital Nigeria

This repository presents a data-driven analysis of youth unemployment in Nigeria, focusing on the gap between educational attainment and employment outcomes. The project was developed as part of a hackathon challenge and uses real and simulated datasets to uncover the structural causes of unemployment among graduates in a rapidly digitizing economy.

The goal is to empower policymakers, educators, and job seekers with insights that can influence curriculum reform, policy direction, and career decision-making. While no predictive models were built, the emphasis is on exploratory data analysis (EDA) and visual storytelling to surface key patterns and challenges across regions, demographics, and educational backgrounds.

---

## 🎯 Objective
Despite a rise in tertiary education enrollment across Nigeria, graduate unemployment remains high — driven by:

Mismatch between field of study and job market needs

Gender and regional disparities

Limited adoption of vocational and digital skills

Inefficient policy targeting

This project aims to unpack these factors using a combination of NBS datasets, simulated graduate data, and Power BI dashboards.

---

## Key Features
📍 Regional Analysis: Examine unemployment and underemployment across Nigeria’s six geopolitical zones

🎓 Degree vs. Job Relevance: Analyze which degree types and disciplines correlate with unemployment

🧪 Skills Insight: Identify the role of vocational, creative, and digital skills in boosting employability

👥 Demographic Lens: Gender- and age-based breakdown of employment status

📈 Interactive Power BI Dashboard: Visual summary of insights for policy and educational stakeholders

## 📊 Data Sources

| Source | Description |
|--------|-------------|
| [NBS Poverty Rate](https://www.nigerianstat.gov.ng/](https://intelpoint.co/blogs/nigerias-poverty-rate-trend-from1960-to-2024/)) | Official poverty rates per state/region |
| [Nigerian Tertiary Enrollment](https://www.nuc.edu.ng](https://data.worldbank.org/indicator/SE.TER.ENRR?locations=NG)) | Public data on graduate enrollment by state |
| Simulated Graduate Dataset | 1,539-row dataset with attributes like gender, field of study, digital/vocational skills, employment status |

---
##  Data Model & Sources
This project leverages a Star Schema structure in Power BI for analytical performance, built around simulated microdata and real state-level aggregates.

Table	Description
graduate_data	Simulated micro-level data (1,539 rows) covering gender, age, location, degree type, CGPA, employment status, skills
nbs_poverty	Official poverty data by state
tertiary_enrollment	Nigerian tertiary education enrollment data

## 🧪 Methodology

### Step-by-step process:

1. **Data Simulation** using `Faker` aligned with Nigerian context | Incorporated public data on poverty, tertiary enrollment, and employment
2. **Data Cleaning & Preprocessing** Standardized columns (e.g., employment status, degree type, region) | Created derived variables (e.g., well-paid vs. underpaid, job match vs. mismatch)
3. **Exploratory Analysis & Visualization** Used Power BI to surface patterns across demographics, degree types, and skills | Built KPI's,  bar charts, and trend lines
4. **Insight Synthesis** Summarized findings into key themes for policy, education, and individual decision
   
---

### Reports and Visuals
The dashboard is divided into several key pages, each focusing on a different aspect of supplier quality:

- **Overview**: Great for stakeholders to quickly grasp the current graduate employment situation and its linkage to regional development.
- **Unemployment**: Provides policymakers and researchers with micro-level indicators to investigate curriculum-employment mismatches and age/gender employment bias.
- **Skills**: Designed to guide youth, government, and educators on which skill areas to invest in for the future of work.

## 📈 Insights & Highlights

- **South East** has the highest unemployment rate among graduates  
- **NCE holders** are the most underpaid; **Master's holders** are better compensated  
- **Females** face higher unemployment and underpayment  
- **Computer Science** & **Biochemistry** graduates have better employment outcomes  
- Only **12%** of graduates work in their field of study  

---


## 🧠 Key Recommendations

| Stakeholder | Recommendation |
|-------------|----------------|
| **Government** | Fund vocational & digital training, target regional imbalances |
| **Educators** | Align curriculum with job market needs, teach practical skills |
| **Job Seekers** | Build tech/vocational skills, stay agile, and explore freelance/remote roles |

## Contributing
Contributions are welcome! If you have ideas for improving this dashboard or extending its functionality, feel free to open a pull request or submit an issue.


## Contact
For any questions or support, please contact:

- **Name**: Alani Joshua
- **Email**: alanijoshua500@gmail.com
