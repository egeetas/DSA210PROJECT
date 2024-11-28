# DSA210PROJECT

# Weekday vs Weekend Walking Distance Analysis

#Description

Sabanci University DSA210 - Introduction to Data Science Course, Fall 2024-2025 Term Project by Ege Taş (Student ID: 32378).
This project aims to analyze the differences in my walking distance between weekdays and weekends, using data exported from the Apple Health app.

The hypothesis tested is:
"My walking distance is higher on weekdays because I spend more time at school and attending classes, whereas on weekends, I typically drive, which reduces my physical activity levels."

For the final report, see here.

#Table of Contents

Motivation

Data Collection and Processing

Findings

Overall Weekly Trends
Impact of Driving on Activity
Limitations

Future Work

Motivation

This project aims to explore how my daily routines affect my physical activity levels, particularly focusing on walking distance, a key metric tracked by the Apple Health app. Walking distance provides valuable insights into how I allocate my time and energy during school days and weekends.

The hypothesis tested in this project is that my walking distance is higher on weekdays due to increased activity during school hours, such as moving between classes and buildings on campus. In contrast, weekends are hypothesized to involve less walking due to frequent car usage and fewer structured activities.

Data Collection and Processing

Data Collection
I obtained the data from the Apple Health app by requesting an export file through the app's settings. This file was in XML format, containing detailed records of my daily physical activities, including Walking+Running Distance, along with timestamps and metadata.

Data Parsing and Analysis Plan
Parsing the Data: The XML data was parsed using Python to extract relevant records specifically for Walking+Running Distance. This included timestamps and daily totals for walking distances.
Categorization: Days were categorized as:
Weekdays (Monday-Friday) for school days.
Weekends (Saturday-Sunday), with some weekends labeled as driving days to reflect reduced physical activity.
Exploratory Data Analysis (EDA): Significant EDA techniques were applied in Python to:
Visualize distributions of walking distances for weekdays and weekends.
Compare walking distances on driving and non-driving weekends.
Highlight trends and patterns using boxplots, histograms, and summary statistics.
Findings

Overall Weekly Trends
Weekdays: Walking distance is consistently higher on weekdays, likely due to increased movement during school hours.
Weekends: Walking distances are lower and more variable, aligning with reduced activity levels when structured routines are absent.
Impact of Driving on Activity
Driving Weekends vs Non-Driving Weekends:
On weekends when I drove, walking distances were significantly lower compared to non-driving weekends.
This supports the hypothesis that driving negatively impacts physical activity levels.
Non-Driving Weekends:
These weekends show walking distances that, while lower than weekdays, are higher than driving weekends, reflecting leisure activities.
Limitations

Data-Specific Limitations
Limited Scope of Data: The analysis focuses only on walking distances and does not account for other physical activities (e.g., gym workouts or cycling).
Simulated Driving Data: Driving days were manually labeled based on personal routines, which may not fully reflect actual driving habits.
Personal Limitations
Privacy Concerns: Certain sensitive data, such as specific timestamps, were excluded to maintain privacy.
Knowledge and Resources: As a student, my knowledge and resources are limited, which might constrain the depth of the analysis.
Future Work

Hourly Trends: Extend the analysis to identify peak activity periods during weekdays and weekends.
Seasonal Analysis: Include walking distance data across seasons to observe variations in activity levels.
Integration of Additional Metrics: Incorporate calorie data, step counts, and heart rate measurements for a more comprehensive analysis.
Lifestyle Correlations: Explore correlations between walking distance and other metrics, such as sleep duration or screen time.
This project demonstrates how data science techniques can be applied to gain insights into personal routines and physical activity patterns. For further details, refer to the final report here.
