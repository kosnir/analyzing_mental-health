# Analyzing Mental Health Challenges Among International Students

## Objective
This project explores how studying abroad impacts the mental health of international students. Using data collected from a Japanese international university in 2018, the analysis investigates factors like acculturative stress, social connectedness, and their relationship to mental health outcomes such as depression.

The dataset and project were provided by **DataCamp** as part of an educational program.

## Dataset Overview
The dataset contains approximately 50 columns with information on demographics, stress levels, social belonging, and mental health indicators. It includes responses from international students surveyed at the university, providing insights into the challenges faced by this group.

## Dictionary of Variables
| Field Name      | Description                                      |
| --------------- | ------------------------------------------------ |
| `inter_dom`     | Student type (international or domestic)          |
| `japanese_cate` | Japanese language proficiency                     |
| `english_cate`  | English language proficiency                      |
| `academic`      | Academic level (undergraduate or graduate)        |
| `age`           | Student's age                                     |
| `stay`          | Length of stay in years                           |
| `todep`         | Depression score (PHQ-9 test)                     |
| `tosc`          | Social connectedness score (SCS test)             |
| `toas`          | Acculturative stress score (ASISS test)           |

## Research Questions
1. What is the prevalence of mental health issues among international students compared to general population norms?
2. How does acculturative stress correlate with depression levels?
3. Does a lack of social connectedness significantly increase the risk of mental health difficulties?
4. Are there regional or demographic differences in mental health outcomes among students?

## Methodology
The analysis uses both SQL and Python for data processing and visualization. Key steps include:

- **Data Cleaning**: Handling missing values and standardizing responses (e.g., removing rows with "NONE").
- **Exploratory Analysis**: Generating descriptive statistics and identifying trends in mental health indicators.
- **Visualization**: 
  - Using Python (Seaborn) to create plots and visualizations to explore relationships between variables.
  - Exporting summary tables to external tools for additional insights.

### Example SQL Tasks
- Identifying missing or inconsistent data.
- Aggregating data to study relationships between acculturative stress, social connectedness, and depression.
- Filtering and grouping data by demographic factors (e.g., age, region, or gender).

## Preliminary Findings
Initial results indicate that international students are at a higher risk for mental health challenges. Acculturative stress and social connectedness are significant predictors of depression. Students who report lower integration into the local culture or social isolation tend to show higher depression scores.

## Future Steps
1. Perform deeper correlation analysis to identify predictive factors.
2. Investigate interventions or support systems to mitigate stress and improve social connectedness.
3. Explore the impact of native language proficiency on the development of social connectedness.
4. Create interactive dashboards for stakeholders to explore key insights.

## Conclusion
This project underscores the importance of addressing the mental health needs of international students. By understanding the roles of acculturative stress and social belonging, universities can design targeted interventions to better support their diverse student populations.
