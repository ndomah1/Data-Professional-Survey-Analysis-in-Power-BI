# Power BI Exploratory Analysis on Data Professionals Survey

![Data Professional Survey Breakdown.jpg](Data_Professional_Survey_Breakdown.jpg)

## Overview

This project analyzes survey responses from data professionals using Power BI. The dataset includes salary ranges, job titles, programming language preferences, work-life balance ratings, and demographics. The goal is to clean, transform, and visualize the data for meaningful insights.

## Goals and Key Questions

- What are the most common job titles among data professionals?
- How does salary vary by job title and region?
- What programming languages are most preferred?
- How satisfied are professionals with salary and work-life balance?
- How difficult is it to break into the data industry?

## Dataset

The dataset (https://www.kaggle.com/datasets/ahmedmohamedibrahim1/data-professional-survey-breakdown) consists of responses from **630 data professionals** collected via LinkedIn, Twitter, and other platforms. Key attributes include:

- **Job Title:** Data Analyst, Data Scientist, Engineer, etc.
- **Salary Range:** Reported salary, converted into an average numeric value.
- **Industry:** The sector where respondents work.
- **Programming Language Preference:** Respondents’ preferred programming language.
- **Satisfaction Ratings:** Work-life balance and salary satisfaction scores (0-10 scale).
- **Country and Demographics:** Location and age distribution.

## Data Cleaning and Transformation

- **Column Selection:** Removed unnecessary fields.
- **Standardization:** Unified job titles and programming language names.
- **Salary Conversion:** Transformed salary ranges into numerical averages.
- **Country Aggregation:** Standardized country names.
- **Work-Life Balance & Salary Satisfaction:** Converted responses into numeric scores.

## Key Insights

### 1. **Salary Trends by Job Title**

- **Data Scientists** have the highest average salary at **$94,000**.
- **Data Engineers and Architects** earn between **$60,000-$65,000**.
- **Data Analysts** have the lowest reported salaries, averaging **$55,000**.

### 2. **Programming Language Popularity**

- **Python** is the most widely used language among respondents.
- Other popular choices include **R, SQL, C++, JavaScript, and Java**.

### 3. **Work-Life Balance & Salary Satisfaction**

- The **average work-life balance satisfaction score** is **5.74/10**.
- **Salary satisfaction is lower**, averaging **4.27/10**.

### 4. **Geographic Breakdown of Respondents**

- **United States:** The largest group of respondents.
- **India, Canada, and the UK** also have significant representation.

### 5. **Difficulty Breaking Into Data Roles**

- **42.7%** of respondents found it **neutral or somewhat difficult**.
- **26.5%** rated it as **difficult or very difficult**.
- **30.8%** found it **relatively easy**.

## Power BI Dashboard

The interactive **Power BI dashboard** includes:

- **Average Salary by Job Title** (Bar Chart)
- **Programming Language Popularity** (Clustered Column Chart)
- **Satisfaction Ratings** (Gauge Visuals for Work-Life Balance & Salary Satisfaction)
- **Participant Nationalities** (Tree Map for country-wise analysis)
- **Difficulty of Breaking Into Data Roles** (Pie Chart for category breakdown)

![Data Professional Survey Breakdown.jpg](Data_Professional_Survey_Breakdown.jpg)

## Usage Instructions

1. Open the **Power BI Dashboard** (provide link if applicable).
2. Use **filters** to analyze trends by job title, location, and programming language.
3. Interact with the visualizations to explore salary, work-life balance, and career insights.

## Limitations

- **Self-Reported Data:** Responses may not fully reflect actual industry salaries.
- **Limited Data Cleaning:** Some categories, such as programming languages, were grouped for simplification.
- **Regional Salary Differences:** No adjustments for purchasing power parity (PPP).

## Future Recommendations

- **Advanced Data Cleaning:** Further standardization of job roles and language entries.
- **Trend Analysis:** Examining salary growth over time and career transitions.
- **Predictive Modeling:** Forecasting salaries based on industry, job title, and experience level.

This project demonstrates how **Power BI** can transform survey data into **meaningful business insights**, making it an excellent portfolio project for data professionals.