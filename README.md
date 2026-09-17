# 🎮 Gaming Platform Player & Transaction Analytics Dashboard

An executive-level interactive Excel analytics dashboard built to analyze player engagement, monetization patterns, and detect suspicious (bot/fraud) session activity across gaming platforms.

---

## 📸 Dashboard Preview

![Dashboard Preview](/dashboard_preview.png)

---

## 📊 Business Problem & Objectives

Gaming platforms continuously handle high volumes of player sessions, microtransactions, and automated bot activity. The objective of this dashboard is to provide platform managers and corporate stakeholders with a unified visual report to track:
1. **Monetization & Revenue Performance**: Monitoring conversion rates between paid and non-paid sessions.
2. **Player Engagement Dynamics**: Analyzing session frequency across High, Medium, and Low engagement tiers.
3. **Fraud & Risk Mitigation**: Tracking bot activity spikes and suspicious session distribution across player tiers.

---

## 📁 Dataset & Architecture

The raw dataset (`Gaming_Case_Study_Excel_Dataset.xlsx - Sheet1.csv`) consists of platform session logs containing the following key fields:
* **Session_ID**: Unique identifier for each player session.
* **Player_ID**: Unique player identifier.
* **Platform**: Device platform used (`Console`, `Mobile`, `PC`).
* **Engagement_Level**: Categorized player engagement (`High`, `Medium`, `Low`).
* **Made_Purchase**: Binary indicator (`Yes`, `No`) for microtransactions.
* **Suspicious_Flag**: Risk metric flag (`1` for suspicious/bot activity, `0` for normal).
* **Revenue**: Transaction amount per session.

---

## 🛠️ Key Data & Analytics Features

* **Data Preprocessing & Cleaning**: Cleaned raw session logs, normalized platform metrics, and engineered calculated fields (`Engagement Level`, `Made Purchase`, `Suspicious Flag`).
* **KPI Metrics Block**: Top-level executive cards tracking Total Revenue ($2,631.27), Total Players (500), Active Sessions (499), and Suspicious Activity Rate (20.60%).
* **Interactive Dynamic Slicers**: Seamlessly cross-filter all 6 dashboard visuals simultaneously by `Year-Month`, `Made Purchase`, `Suspicious Flag`, `Engagement Level`, and `Platform`.
* **Corporate Palette & Visual Hierarchy**: Custom Navy/Slate/Coral 2D flat visual architecture engineered for executive clarity.

---

## 🚀 How to View & Use

1. Clone or download the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/gaming-platform-analytics-dashboard.git](https://github.com/YOUR_USERNAME/gaming-platform-analytics-dashboard.git)
