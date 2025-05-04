# 🧪 A/B Testing Experiment Analysis

This project simulates and analyzes an A/B test using Python. It demonstrates the full lifecycle of a typical experiment — from data generation and exploration to statistical testing and insights.

---

## 📌 Overview

A/B testing (split testing) is a method used to compare two variants of a product, webpage, or feature to determine which one performs better. In this simulated experiment, we test two groups (A = control, B = variant) and analyze their conversion rates.

---

## 🔧 Tools & Techniques Used

- Python (pandas, numpy, scipy, matplotlib)
- Statistical analysis (z-test for proportions)
- Data simulation
- Group-wise comparisons
- Experiment design logic

---

## 📊 Key Steps

1. **Data Simulation**  
   - 1,000 users randomly assigned to Group A or B  
   - Group A has 12% conversion; Group B has 15%

2. **Data Exploration**  
   - Preview dataset  
   - Calculate conversion rates by group

3. **Visualization**  
   - Plot conversion differences using bar charts

4. **Hypothesis Testing**  
   - Run a z-test to determine if the observed difference is statistically significant

---

## 📈 Result

> The project evaluates whether the variant (Group B) leads to a statistically significant lift in conversions compared to the control (Group A).

---

## 🧠 Skills Demonstrated

- Experimental design
- Binary outcome analysis
- Hypothesis formulation & testing
- Communication of statistical results
- Data storytelling for business stakeholders

---

## 🚀 Next Steps

- Expand to include confidence intervals
- Simulate more metrics (e.g., revenue per user)
- Package into reusable function for repeated tests



