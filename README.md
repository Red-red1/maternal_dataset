# 🩺 Maternal Health Risk Dataset

This dataset comprises detailed **clinical**, **physiological**, and **historical health** information collected from maternal patients to evaluate potential health risks during pregnancy.  

It serves as a valuable resource for developing **predictive models** aimed at identifying and managing **high-risk pregnancies**, providing insights into maternal health factors, and supporting **personalized patient care**.

---

## 📊 Dataset Overview

The dataset is well-suited for research in:
- **Obstetrics and Gynecology**
- **Predictive Health Modeling**
- **Maternal Healthcare Management**

---

## 🧩 Key Features

| Feature | Description |
|----------|-------------|
| **Age** | Age of the patient — a significant factor influencing pregnancy risk. |
| **Systolic BP** | Systolic blood pressure, representing arterial pressure when the heart beats. Elevated levels indicate **hypertension risk**. |
| **Diastolic BP** | Diastolic pressure measured between heartbeats; higher values may signal **gestational hypertension** or **preeclampsia**. |
| **BS (Blood Sugar)** | Patient’s blood sugar level — critical for monitoring **gestational diabetes** and fetal health. |
| **Body Temp** | Body temperature, useful in identifying **infection** or **inflammation**. |
| **BMI (Body Mass Index)** | Indicator of body fat based on height and weight; high BMI correlates with **gestational complications**. |
| **Previous Complications** | Binary indicator (0 or 1) representing a history of previous pregnancy complications. |
| **Preexisting Diabetes** | Indicates if the patient has a pre-pregnancy diabetes diagnosis. |
| **Gestational Diabetes** | Presence of diabetes **developed during pregnancy** — a major maternal and fetal risk factor. |
| **Mental Health** | Binary indicator for mental health conditions that may affect pregnancy outcomes. |
| **Heart Rate** | Patient’s heart rate — elevated levels may indicate **stress** or **cardiovascular strain**. |
| **Risk Level** | Categorical label (e.g., *High*, *Low*) representing the overall pregnancy risk assessment. |

---

## 🧠 Applications

This dataset can be applied in various domains of healthcare and data science:

### 🩸 Risk Stratification
Identify and classify patients at **higher risk** for maternal complications.

### 🤖 Predictive Modeling
Train **machine learning** and **statistical models** to forecast pregnancy-related health risks and guide preventive interventions.

### 🧬 Maternal Health Research
Support studies on how **clinical metrics** influence **pregnancy outcomes** and maternal well-being.

### 🏥 Healthcare Policy Development
Provide **data-driven evidence** to help formulate guidelines for maternal care, especially in **resource-limited settings**.

---

## ⚙️ Example Use Cases

- Predicting **high-risk pregnancies** using logistic regression or random forest models.  
- Analyzing the relationship between **BMI, BP, and gestational diabetes**.  
- Building a **dashboard** for monitoring maternal health indicators.  
- Supporting **AI-driven healthcare policy** recommendations.

---

## 📁 Dataset Summary

- **Format:** CSV  
- **Target Variable:** `Risk Level`  
- **Use Case:** Classification / Risk Prediction  
- **Domain:** Healthcare, Maternal Health, Predictive Analytics  

---

## ❤️ Acknowledgment

This dataset aims to promote **maternal health awareness**, support **public health research**, and enhance **AI-driven medical insights** to ensure better outcomes for mothers and infants worldwide.

---

## 🧮 Example: Loading the Dataset (Python)

```python
import pandas as pd

# Load the dataset
df = pd.read_csv("maternal_health_risk.csv")

# Display basic info
print(df.info())

# Show first few rows
df.head()
