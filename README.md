# **Weekday vs Weekend Walking Distance Analysis**

## **Description**

Sabancı University **DSA210 - Introduction to Data Science** Course, Fall **2024-2025** Term Project by **Ege Taş (Student ID: 32378)**.  
This project analyzes my walking distance data, obtained from the Apple Health app, to understand the differences in physical activity levels between weekdays and weekends.

The hypothesis tested in this project is:  
*"My walking distance is higher on weekdays because I spend more time at school and attending classes, whereas on weekends, I typically drive, which reduces my physical activity levels."*

---

## **Table of Contents**
- [Motivation](#motivation)  
- [Data Source](#data-source)  
- [Plan](#plan)  
- [Findings (Preliminary)](#findings-preliminary)  
- [Limitations](#limitations)

---

## **Motivation**

Physical activity plays a vital role in maintaining a healthy lifestyle. Tracking walking distance provides valuable insights into daily routines and their impact on overall activity levels. This project originates from my curiosity about how my weekday and weekend routines influence my walking habits. 

By analyzing this data, I aim to:
1. Understand the effect of structured school schedules on physical activity.
2. Explore how driving impacts walking distance, especially during weekends.  
3. Gain personal insights to adjust my habits for a healthier lifestyle.

---

## **Data Source**

The walking distance data was collected from the Apple Health app, covering a period of several weeks. The dataset includes:
- **Date:** To distinguish between weekdays and weekends.
- **Walking Distance (km):** The total walking distance logged each day.
- **Manual Driving Tags:** Days identified as driving-intensive based on personal observations.

The dataset was anonymized to protect sensitive information, focusing solely on the walking distance metric.

---

## **Plan**

### **November 20-30, 2024**
- Finalize the **README.md** file for the GitHub repository, including:
  - Detailed project description.
  - Dataset overview and sources.
  - Hypothesis and objectives.
  - Analysis methods planned.

- Submit the public GitHub repository URL to SuCourse for the project proposal.  
  - Ensure the repository includes preliminary EDA scripts, visualizations, and any supporting materials.

### **December 5-15, 2024**
- Perform detailed exploratory data analysis (EDA):
  - Visualize walking distances for weekdays and weekends.
  - Identify outliers and trends.
  - Calculate statistical summaries (mean, median, etc.).

- Begin working on comparisons between driving and non-driving weekends:
  - Use visualizations such as boxplots and bar charts.

### **December 20-30, 2024**
- Conduct hypothesis testing to analyze differences in walking distances:
  - Weekdays vs weekends.
  - Driving weekends vs non-driving weekends.

- Refine analysis scripts and document the process in the repository:
  - Include updated visualizations.
  - Add explanations for analysis choices.

### **January 2-10, 2025**
- Finalize all findings and write the project report:
  - Summarize key insights and interpretations.
  - Highlight limitations and challenges faced during the analysis.

- Prepare for the final submission:
  - Review all scripts and ensure reproducibility.
  - Organize the repository with clear folder structures for scripts, data, and visualizations.

### **January 10, 2025**
- Submit the finalized project material, including the project report, analysis scripts, and visualizations, to SuCourse.

---

## **Findings (Preliminary)**

### **Overall Weekly Trends**
- **Weekdays:** Higher walking distances, likely due to movement between classes and activities on campus.  
- **Weekends:** Greater variability in walking distances, with a lower median, reflecting reduced physical activity.  

### **Impact of Driving on Activity**
1. **Driving Weekends:** Significantly lower walking distances compared to non-driving weekends.  
2. **Non-Driving Weekends:** Higher walking distances than driving weekends but still lower than weekdays.

---

## **Limitations**

1. **Data Scope:** Focused only on walking distances; other physical activities like gym workouts are excluded.  
2. **Manual Labeling:** Driving days were labeled manually, which may introduce bias.  
3. **Sample Size:** The dataset is limited to my personal activity, making generalization difficult.  
