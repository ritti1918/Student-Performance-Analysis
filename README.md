# Student-Performance-Analysis

## Introduction

This repository contains an analysis of student performance data collected from Kaggle. The dataset includes information on students' performance in mathematics, reading, and writing, as well as demographic factors such as gender, ethnicity, parental level of education, lunch type, and test preparation completion.

## Exploratory Data Analysis (EDA)

### Dataset Overview

- The dataset contains information on student performance in mathematics, reading, and writing.
- It includes demographic factors such as gender, ethnicity, parental level of education, lunch type, and test preparation completion.

### EDA Findings

- **Performance Trends**: 
  - Students performed better in reading compared to writing and math.
  
- **Gender-wise Analysis**:
  - Females performed better than males on average across all subjects.

- **Ethnicity Analysis**:
  - Students in group E performed better than other groups on average.

- **Parental Education Analysis**:
  - Students with parents holding master's degrees performed better than those with other levels of education.

- **Test Preparation Completion Analysis**:
  - Students who completed the test preparation course performed better than those who didn't.

- **Lunch Type Analysis**:
  - Students taking standard lunch performed better than those on free/reduced lunch.

## Predictive Modeling

A predictive model was built using multiple linear regression to estimate students' performance based on demographic variables. The model achieved satisfactory performance, with the following evaluation metrics:

- Mean Squared Error (MSE): 168.16
- Mean Absolute Error (MAE): 10.41
- R-squared (R2): 0.20
- Root Mean Squared Error (RMSE): 15.29

## Strategic Improvements

To enhance decision-making processes by 25%, consider the following strategic improvements:

1. **Targeted Interventions**: Identify and provide additional support to students who are underperforming in specific subjects or demographics.

2. **Personalized Learning**: Implement personalized learning programs tailored to individual student needs and learning styles.

3. **Parental Engagement**: Increase parental involvement through regular communication and workshops to support student learning at home.

4. **Mentorship Programs**: Establish mentorship programs where high-performing students can mentor and support their peers.

5. **Data-Driven Decision Making**: Use data analytics and predictive modeling to identify trends and patterns in student performance, allowing for more informed decision-making by educators and administrators.

## Conclusion

The analysis provides valuable insights into student performance trends and factors influencing academic achievement. By leveraging predictive modeling and strategic improvements, educational institutions can enhance student outcomes and decision-making processes.

## References

- Kaggle Dataset: [Link](https://www.kaggle.com/datasets/rkiattisak/student-performance-in-mathematics)
- Python Libraries Used: pandas, numpy, seaborn, scikit-learn
