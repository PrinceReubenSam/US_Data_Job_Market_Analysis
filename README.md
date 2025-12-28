# Data Analyst Job Market Insights  
##  Overview  
This project was created to **showcase my proficiency in Python** while analyzing the **data job market**, with a strong focus on **data analyst roles**.  
The motivation behind this analysis is to gain clarity on which skills matter most for landing optimal opportunities, both in terms of **demand** and **salary potential**.  

##### Using job data sourced by  **Luke Barousse**, I examine job titles, salaries, locations, and required skills.  
##### Through Python-based analysis, I aim to answer key questions about the evolving data job landscape.  
---

##  Key Questions  
This project investigates the following:  

1. Which skills are most in demand for the **top three data roles**?  
2. What are the trending/in-demand Skills for Data Analysts?  
---

## 🛠 Tools & Technologies  

- **Python** – Core programming language for analysis  
- **Pandas** – Data manipulation and analysis  
- **Matplotlib** – Data visualization  
- **Seaborn** – Advanced and styled data visualizations  
- **Jupyter Notebooks** – Interactive analysis and documentation  
- **Visual Studio Code** – Script execution and code development  
- **Git & GitHub** – Version control and project sharing
- **ChatGPT** - For further assistance

---
## Data Preparation and Cleanup
This section outlines the steps taken to prepare the data for analysis, ensuring accuracy and usability.

### Import & Clean Up Data
I start by importing necessary libraries and loading the dataset, followed by initial data cleaning tasks to ensure data quality, to focus my analysis on the U.S. job market, I apply filters to the dataset, narrowing down to roles based in the United States.
<img width="1756" height="748" alt="code1" src="https://github.com/user-attachments/assets/1cea52b9-6abe-4299-a11c-698fbeb6c590" />

# The Analysis  

## 1. Most Demanded Skills for Top 3 Roles  
I identified the three most common job titles, then extracted the top five skills for each.  
This shows which skills are most valuable depending on the role.  

Detailed steps: [2_Skill_Demand.ipynb](Project/2_Skills_Count_Analysis.ipynb)
### Data visualization codes
<img width="1988" height="938" alt="code2" src="https://github.com/user-attachments/assets/31e72d7f-9813-4940-805f-170d9009a199" />

### Result

<img width="620" height="472" alt="image" src="https://github.com/user-attachments/assets/7fde191f-4154-47b0-9a2f-cd953a6d69eb" />

###  Insights  

- **SQL** is the top skill for Data Analysts and Data Scientists, appearing in over half of job postings.  
- **Python** dominates for Data Engineers (68%) and is also highly valued for Data Scientists (72%) and Data Engineers (65%).  
- Data Engineers often need specialized tools (**AWS, Azure, Spark**), while Analysts and Scientists rely more on general tools like **Excel** and **Tableau**.
    
## 2. Trending Skills for Data Analysts  

To track 2023 trends, I filtered **Data Analyst** roles and grouped skills by posting month.  
This revealed the **top five skills per month**, showing how their demand shifted over the year.  

 Detailed steps: [3_Skills_Trend.ipynb](Project/3_Skills_Trend_Analysis.ipynb)  

### Data visualization codes  

<img width="1696" height="862" alt="code3" src="https://github.com/user-attachments/assets/aa9f5800-8f6c-47c6-b826-d13bbda4e46e" />

### Result

<img width="1696" height="862" alt="image" src="https://github.com/user-attachments/assets/531bce03-7049-484e-9cb1-fd5e0ac651fd" />

### insights

- SQL remains the top skill but declines about 10 percentage points (≈64% → ≈54%).
- Excel falls mid-year then rebounds, peaking ≈45% in Jul/Aug and finishing near ≈40%.
- Python and Tableau are stable around 30–35%, with Tableau rising late to ≈33%.
- Power BI is lowest (≈18–23%) but shows a small year-end uptick.

### Takeaway 
**Data analysts should focus on mastering SQL and Python, supplemented with Excel; add Tableau for visualization and can treat Power BI as optional.**

## Final Insights
- **Shifting market:** Skill demand changes over time — staying current is essential for career growth.  
- **Prioritization:** Learn skills that are both in high demand and well-compensated to maximize economic return.

## what I learned
- **advanced python:** stronger skills with pandas, numpy, matplotlib, and seaborn for cleaning and visuals.  
- **data prep matters:** accurate cleaning and formatting are essential for reliable results.  
- **storytelling with notebooks:** clear narrative + visuals improves reproducibility and reviewer understanding.  
- **version control:** using git/GitHub for tracking changes and sharing work.  
- **market fit:** how to match learning priorities to demand and salary potential.








Data Analyst Job Market Insights
Overview

This project analyzes the U.S. data job market with a strong focus on Data Analyst roles, using Python to identify which skills are most valuable for securing competitive opportunities based on market demand and salary potential.

Using job posting data sourced from Luke Barousse (2023), the analysis examines job titles, salaries, locations, and required skills to better understand trends shaping the data analytics job landscape.

Key Questions

This project answers the following questions:

Which skills are most in demand across the top data roles?

Which skills are trending for Data Analysts over time?

Tools & Technologies

Python – Core programming language for analysis

Pandas – Data cleaning, manipulation, and analysis

NumPy – Data optimization and numerical operations

Matplotlib – Data visualization

Seaborn – Advanced and styled visualizations

Jupyter Notebooks – Interactive analysis and documentation

Visual Studio Code – Script execution and development

Git & GitHub – Version control and project sharing

ChatGPT – Research and debugging assistance

Data Preparation and Cleanup

The dataset was prepared entirely in Python to ensure accuracy and analytical reliability. This included importing required libraries, handling missing values, standardizing formats, and filtering postings to focus exclusively on U.S.-based data roles.
<img width="1756" height="748" alt="code1" src="https://github.com/user-attachments/assets/1cea52b9-6abe-4299-a11c-698fbeb6c590" />

Analysis
1. Most Demanded Skills for Top Data Roles
<img width="1988" height="938" alt="code2" src="https://github.com/user-attachments/assets/31e72d7f-9813-4940-805f-170d9009a199" />


The three most common data job titles were identified, after which the top skills associated with each role were extracted and analyzed to determine role-specific demand.

Insights

SQL is the most in-demand skill for Data Analysts and Data Scientists, appearing in over half of job postings.

Python is highly valued for Data Scientists (~72%) and Data Engineers (~65%).

Data Engineers more frequently require specialized tools such as AWS, Azure, and Spark, while Data Analysts and Data Scientists rely more on Excel and Tableau.

2. Trending Skills for Data Analysts (2023)

To understand skill trends over time, Data Analyst postings were grouped by month and analyzed to track shifts in demand throughout 2023.
<img width="1696" height="862" alt="code3" src="https://github.com/user-attachments/assets/aa9f5800-8f6c-47c6-b826-d13bbda4e46e" />

<img width="1696" height="862" alt="image" src="https://github.com/user-attachments/assets/531bce03-7049-484e-9cb1-fd5e0ac651fd" />


Insights

SQL remains the top skill but declined by ~10 percentage points (≈64% → ≈54%).

Excel declined mid-year, rebounded to ~45% in July/August, and closed near ~40%.

Python and Tableau remained relatively stable at ~30–35%, with Tableau increasing toward year-end.

Power BI showed the lowest demand (~18–23%) but experienced a modest upward trend.

Key Takeaways

Data Analysts should prioritize SQL and Python as core technical skills.

Strong Excel proficiency remains essential.

Tableau adds value for visualization-heavy roles, while Power BI is useful but less dominant.

Skill demand evolves continuously, making ongoing upskilling critical.

What I Learned

Strengthened advanced Python skills using Pandas, NumPy, Matplotlib, and Seaborn.

Reinforced the importance of proper data cleaning and preparation for reliable analysis.

Improved data storytelling through clear narratives and visualizations in notebooks.

Gained hands-on experience with Git/GitHub for version control and collaboration.

Learned how to align skill development with market demand and salary potential.

Conclusion

This project provided valuable insights into the Data Analyst job market and clarified which skills offer the highest return for career growth. The challenges encountered during data cleaning and analysis strengthened my problem-solving and visualization skills and reinforced the importance of staying adaptable in a rapidly evolving field.

## Conclusion  
Working on this project taught me a lot about the data analyst job market and the skills that matter most.  
I faced challenges with cleaning and organizing data, but they helped me get better at problem-solving and visualization.  
The insights I gained give me clearer direction for growing in data analytics and staying adaptable as the field changes.  
