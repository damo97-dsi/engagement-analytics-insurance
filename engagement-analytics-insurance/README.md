# Engagement Analytics in Health Insurance  
### A Retention Decision System for Predicting Disengagement and Targeting Cost-Effective Interventions  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Damodar%20Naraparaju-blue?logo=linkedin)](https://www.linkedin.com/in/damo-madhukar)  
[![GitHub](https://img.shields.io/badge/GitHub-Project%20Repo-black?logo=github)](https://github.com/damo97-dsi/engagement-analytics-insurance)

---

## 🚀 Executive Snapshot

- 🎯 Identifies high-risk disengaged customers for targeted retention  
- 📊 ~87% model accuracy with risk-based prioritization  
- 💰 Estimated 15% churn reduction (~$1.2M impact)  
- 🧠 Behavioral segmentation into 3 actionable personas  
- ⚡ Highlights effectiveness of low-cost, non-monetary incentives  

---

## 📊 Sample Output

![Cluster Segmentation](visuals/cluster_segmentation.png)  
![Feature Importance](visuals/feature_importance_rf.png)

---

## Overview

This project builds a decision-driven analytics system to identify disengaged health insurance customers, segment them by behavioral risk, and guide targeted retention actions.

Rather than stopping at churn prediction, the system translates model outputs into intervention tiers, helping prioritize which customers to target, what type of incentive to use, and where retention efforts are likely to generate the highest value.

---

## Business Problem

Health insurers often lose customers due to declining engagement in wellness and loyalty programs.

When disengagement is detected too late:
- retention costs increase  
- intervention effectiveness drops  
- customer lifetime value declines  

This project addresses:

- Which customers are at risk of disengaging?  
- What behavioral segments exist?  
- Which intervention strategies improve retention efficiently?  

---

## Objective

Design a retention decision system that:

- predicts disengagement risk  
- identifies actionable customer segments  
- supports targeted intervention planning  

---

## Decision Framework

Customers are grouped into action tiers:

- **High Risk** → Immediate intervention  
- **Medium Risk** → Behavioral nudges  
- **Low Risk** → Passive monitoring  

This shifts retention from broad outreach to focused prioritization.

---

## Dataset

Simulated dataset reflecting real-world engagement signals:

- inactivity streaks  
- reward usage  
- wellness participation  
- digital interactions  
- demographics  

---

## Methodology

### 1. Data Preparation
- cleaned and validated data  
- engineered behavioral features  

### 2. Predictive Modeling
- Logistic Regression  
- Random Forest  

Used to prioritize high-risk customers.

### 3. Behavioral Segmentation
Clustered customers into actionable personas.

### 4. Retention Strategy Design
Mapped model outputs to intervention tiers aligned with business actions.

---

## Key Results

- **~87% accuracy in disengagement prediction**  
- **High-risk segments concentrated majority of churn exposure**  
- **Estimated 15% churn reduction (~$1.2M impact)**  
- **3 actionable customer personas identified**  
- **Younger cohorts responded better to non-monetary incentives**  

---

## Business Insights

- disengagement driven by inactivity + reward fatigue  
- targeted strategies outperform broad outreach  
- non-monetary incentives reduce cost without losing impact  
- segmentation improves prioritization  

---

## Tools & Technologies

Python · pandas · scikit-learn · matplotlib · Power BI · Jupyter Notebook  

---

## Project Structure
