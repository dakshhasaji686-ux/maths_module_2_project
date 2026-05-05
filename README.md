# Student Performance Probability Analysis

## Overview
This project performs statistical and probability analysis on a dataset of 100 students. It studies how factors like study hours, attendance, and group discussion influence exam results.

---

## Dataset Description

The dataset contains the following columns:

- study_hours: Number of hours a student studies per week  
- attendance: Percentage attendance in lectures  
- group_discussion: Participation in group discussions (Yes/No)  
- previous_test_score: Marks obtained in previous test (out of 100)  
- final_exam_pass: Final exam result (Pass/Fail)  

Total Records: 100 students

---

## Tasks Performed

### 1. Basic Probability
- Defined probability and key concepts
- Calculated probabilities of:
  - Study hours > 10
  - Attendance > 80%
  - Passing the exam

---

### 2. Types of Probability
- Empirical Probability calculated using dataset
- Theoretical Probability explained using examples

---

### 3. Random Variable and Distribution
- Defined random variable: number of students passing out of 3
- Applied Binomial Distribution
- Calculated:
  - Probability distribution
  - Mean
  - Variance

---

### 4. Venn Diagram Analysis
Analyzed:
- Students studying more than 10 hours
- Students with attendance > 80%
- Students satisfying both conditions

---

### 5. Contingency Table and Probability
- Created contingency table for:
  group_discussion vs final_exam_pass

Calculated:
- Joint probability
- Marginal probability
- Conditional probability

---

### 6. Relationship Analysis
- Checked whether group discussion and passing are independent
- Result: Events are dependent

---

### 7. Bayes Theorem
- Calculated probability of passing given high attendance using Bayes theorem

---

## Tools Used
- Python
- Pandas
- NumPy

## Conclusion
- Higher study hours and attendance increase chances of passing
- Group discussion improves performance
- Probability helps in understanding and predicting outcomes
