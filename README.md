Capstone Project | Masters in Informatics and Analytics
Author: Ndubuisi Nezianya

This project explores the impact of study abroad participation on students’ academic performance (GPA), credit hours earned, and demographic and financial attributes at UNCG. The analysis uses anonymized institutional data and statistical techniques to evaluate measurable educational outcomes.

Table of Contents

About the Project

Dataset Description

Data Governance & Security

Data Cleaning & Preprocessing

Key Insights

Statistical Testing

Limitations

Next Steps


 About the Project
This project analyzes the academic and demographic data of students who participated in UNCG’s Study Abroad program to:

Measure changes in GPA before and after participation

Compare credit hours earned

Understand participation trends by ethnicity, college, and gender

Evaluate the statistical significance of observed changes

 Dataset Description
Total Records: 2,869

Institution: University of North Carolina at Greensboro (UNCG)

Collected By: International Programs Center (IPC)

Key Features:

UNCG Student ID (pseudonymized)

Academic Year

GPA Before / GPA at Graduation

Program Type, College, Major

Pell Grant Eligibility, Ethnic Origin

Hours Attempted vs. Earned

 Data Governance & Security
To ensure ethical handling of student data and comply with academic research standards, the following data governance and security measures were implemented:

 Data Protection Measures
Pseudonymization: All student IDs were anonymized; no names or personally identifiable information (PII) were used.

Restricted Access: Dataset access was limited to authorized individuals involved in the project, stored securely on institutional systems.

No Third-party Sharing: The dataset was not shared with any third-party service, API, or cloud platform without institutional approval.

Data Minimization: Only features relevant to the research question were retained. Sensitive financial and contact details were excluded.

Local Processing: All analysis was conducted in a secure local environment, with no upload to public cloud servers.

 Compliance
FERPA Awareness: The dataset was handled in alignment with the Family Educational Rights and Privacy Act (FERPA) guidelines.

Institutional Oversight: The project followed UNCG’s internal data usage protocols and was supervised as part of an academic capstone requirement.


 Data Cleaning & Preprocessing
Removed null values in numeric columns

Filtered out inconsistent or irrelevant entries

Created derived metrics: GPA Change, %GPA Growth

Grouped and aggregated data by college, major, year

Descriptive statistics and visual exploration


 Key Insights
 GPA Impact: Slight but statistically significant GPA improvement post-study abroad (Δ = +0.01)

 Credit Hours: Study abroad students earned 6–7 more hours on average than non-participants


👩‍🎓 Demographics:

36% of participants were from minority groups

Female students had higher graduation GPA (+0.15) than males

35% were Pell eligible

 Program Type by College:

Arts & Science → Host Enrollments

Business & Econ → Faculty-led


 Statistical Testing
Test Used: Paired Sample t-Test

Hypothesis:

H₀: GPA After = GPA Before

H₁: GPA After ≠ GPA Before

Results:

t(2015) = 3.43

p = 0.001 → Statistically significant

Null hypothesis rejected



Limitations
Missing financial data limited full economic analysis

No control group comparison included yet

Observational dataset—not a randomized experiment



Next Steps
Implement a matched control group for deeper causal inference

Include loan data and post-graduation employment

Collect qualitative feedback from participants to complement quantitative metrics

