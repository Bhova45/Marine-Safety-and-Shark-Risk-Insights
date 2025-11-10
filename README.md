# 🦈 Marine Safety and Shark Risk Insights Overview

This project provides actionable insights into global shark attack data to inform targeted safety and prevention strategies. By analyzing **geographic**, **activity-related**, and **demographic** risk factors, this analysis aims to enhance marine safety awareness and reduce the incidence and fatality of shark encounters worldwide.

---

## 📊 Key Findings & Insights

### 🌍 Geographic Risk & Attack Frequency

The majority of documented shark attacks occur in three primary global hotspots:
* **USA**
* **Australia**
* **South Africa**

### 🏄 Activities at Highest Risk

The most common activities associated with shark attacks are:
* **Surfing**
* **Swimming**
* **Fishing**
* **Spearfishing**

**Crucially, fatality rates are significantly higher for swimmers compared to surfers.**

### 🧑‍🤝‍ Demographics

Shark attacks disproportionately affect younger individuals:
* **Nearly 80%** of all victims are **under 30 years old**.

### 💀 Fatality Distribution

Fatal attacks are most frequent in the same high-incidence countries:
* **USA**
* **Australia**
* **South Africa**

---

## ✅ Hypothesis Testing Validation

The analysis statistically validated the following core hypotheses:

1.  **Attack Location:** Confirmed high risk in the USA and Australia.
2.  **Activity Fatality:** Confirmed that fatality rates are higher for swimmers than for surfers.
3.  **Victim Age:** Confirmed the majority of victims are under 30 years old.

---

## 🛠️ Data Preparation & Methodology

Robust data cleaning and statistical methods were employed to ensure data integrity and reliable insights:

* **Normalization:** Applied to key columns including `Country`, `Activity`, `Species`, `Age`, `Year`, and `Fatal Y/N`.
* **Missing Values:** Imputed using statistical methods (e.g., median for numerical data).
* **Standardization:** Regular expressions were used to extract and standardize categorical and numerical values (especially age and location details).

---

## 📋 Recommendations for Marine Safety

Based on the findings, the following targeted recommendations are proposed:

1.  **Targeted Youth Prevention:** Focus prevention efforts and safety education on **youth** engaging in high-risk activities (surfing, swimming) in major hotspot countries (USA, Australia, South Africa).
2.  **Swimmer Awareness:** **Encourage protective practices** and increase awareness among swimmers, given their statistically higher fatality rate.
3.  **Beach Safety:** Improve and increase safety measures and awareness programs at beaches in the USA, Australia, and South Africa.
4.  **Temporal Analysis:** Further exploration of seasonal trends is necessary for more refined, time-specific safety recommendations.

---

## ⏭️ Next Steps

To build upon this analysis and provide ongoing value, the next steps include:

* **Temporal Analysis:** Incorporate granular temporal analysis (e.g., by month/season) to pinpoint high-risk periods.
* **Visual Dashboards:** Develop interactive visual dashboards for ongoing monitoring and easy communication of trends.
* **Dataset Expansion:** Continue expanding and updating the dataset to maintain high accuracy and statistical power.
