# ✈️ Flight Bag Rescue — Early Warning System

> Predictive analytics system to identify high-risk luggage delays at congested transit hubs.

---

## 📖 Overview

Flight baggage delays are a major operational issue in air travel, especially at high-traffic hubs with tight transfer windows.

This project builds a **risk-scoring model** to predict whether a bag is likely to be delayed, enabling early intervention and improved logistics.

---

## 🚀 Key Results

- Processed **7,000+ tracking records**
- Integrated **3+ operational datasets** (logs, schedules, performance metrics)
- Engineered **5+ predictive features**
- Built a **logistic regression model** for delay prediction

---

## 🧠 Methodology

### 1. Data Integration
Combined multiple data sources:
- baggage tracking logs  
- flight schedules  
- operational performance metrics  

### 2. Feature Engineering
Designed predictive variables including:
- hub congestion indicators  
- transfer window duration  
- connection complexity  
- timing-related features  

### 3. Modeling
- Logistic Regression (binary classification)
- Output: **probability of delay (risk score)**

---

## 📊 Example Output

| Bag ID | Risk Score | Prediction |
|--------|-----------|-----------|
| 10234  | 0.82      | High Risk |
| 20451  | 0.27      | Low Risk  |

---

## ⚙️ Tech Stack

- Python  
- Scikit-learn  
- Pandas  

---

## 📂 Project Structure

```bash
.
├── notebooks/
│   ├── preprocessing.ipynb      # Data cleaning & merging
│   ├── feature_engineering.ipynb
│   ├── modeling.ipynb           # Logistic regression training
│   ├── evaluation.ipynb         # Metrics & validation
│
├── data/
│   ├── raw_data.csv
│   ├── processed_data.csv
│
├── README.md
