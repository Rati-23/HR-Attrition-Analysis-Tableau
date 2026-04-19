# HR Attrition Analysis using Tableau

## Overview

This project presents a quantitative analysis of employee attrition using a dataset of 1,470 employees. The objective is to move beyond surface-level reporting and understand attrition as a **multi-variable system** driven by the interaction of workload, compensation, tenure, and job role.

An interactive Tableau dashboard is developed to identify high-risk employee segments and uncover the structural patterns behind workforce turnover.

---

## Key Metrics

* **Total Employees:** 1470
* **Total Attrition:** 237
* **Attrition Rate:** ~16.1%

This indicates that approximately **1 in 6 employees leaves the organization**, signaling systemic inefficiencies rather than random exits.

---

## Problem Statement

Traditional HR analysis treats attrition as isolated factors and relies on aggregated metrics, which fail to capture interactions between variables.

This project addresses that gap by:

* Identifying key drivers of attrition
* Analyzing how multiple variables interact
* Detecting high-risk employee segments
* Enabling data-driven decision-making

---

## Methodology

The analysis is performed using Tableau through a structured pipeline:

* Data classification into categorical and numerical variables
* Creation of calculated fields (Attrition Rate, Risk Segmentation)
* Binning of continuous variables (e.g., tenure groups)
* Comparative analysis (department, job role)
* Distribution analysis (income, tenure)
* Integration into an interactive dashboard with filters

---

## Key Insights

Attrition is not random—it is **concentrated and predictable**.

* **Overtime is the strongest driver**
  Employees working overtime show ~30.5% attrition compared to ~10.4% without overtime (≈3× increase)

* **Early tenure is highly unstable**
  Employees with 0–5 years experience show ~18% attrition, significantly above average

* **Income strongly influences retention**
  Attrition is concentrated in the ₹3K–₹4K range, while retained employees cluster around ₹5K–₹6K

* **Role and department matter**

  * Sales: ~20.6% attrition
  * Laboratory Technician: ~23.9% attrition (highest)
  * Managerial roles: <10% attrition

* **Work-life balance shows non-linear impact**
  “Average” work-life balance (~31.4%) leads to higher attrition than even “Poor” conditions

---

## Risk Segmentation Model

Employees are classified into risk categories based on combined exposure to key drivers:

* **Low Risk:** ~58% (~850 employees)
* **Medium Risk:** ~33% (~480 employees)
* **High Risk:** ~9% (~130–140 employees)

The high-risk group, although small, contributes disproportionately to total attrition.

---

## System-Level Insight

Attrition emerges when multiple conditions overlap:

> **Early tenure + Overtime + Low income + High-pressure role**

This cluster represents the most unstable segment of the workforce and drives the majority of exits.

---

## Impact

Targeted interventions can significantly reduce attrition:

* Reducing overtime exposure can lower attrition from ~16% to ~12–13%
* Improving compensation and work conditions can reduce attrition by 10–15% within high-risk groups

---

## Tools & Technologies

* **Tableau** – Data visualization and dashboard development
* **Microsoft Excel** – Data preprocessing

---

## Project Files

* `HR_Dashboard.twbx` – Interactive Tableau dashboard
* `HR_Dataset.xlsx` – Source dataset
* `Report.pdf` – Detailed analysis
* `Presentation.pptx` – Project summary
* `Tutorial.mp4` – Dashboard walkthrough

---

## How to Use

Download the `.twbx` file and open it in Tableau Desktop to interact with the dashboard.
Use filters to explore attrition across departments, roles, and demographic segments.

---

## Conclusion

This project demonstrates that employee attrition is not random behavior but a **structured and measurable system**. By analyzing interactions between variables rather than isolated metrics, attrition can be predicted and significantly reduced through targeted, data-driven strategies.

---

## Author

**Rati Srivastava**
Aerospace Engineering Student | Data Science Student

---
