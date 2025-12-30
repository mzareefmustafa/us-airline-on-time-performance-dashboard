# ✈️ U.S. Airline On-Time Performance Analysis (Tableau Dashboard Project)

An end-to-end exploratory and analytical dashboard project analyzing **U.S. airline on-time performance** using Bureau of Transportation Statistics (BTS) data from **2019–2024**.

This project focuses on understanding airline reliability, delay behavior, operational disruptions, and recovery patterns before and after the COVID-19 shock, using **interactive Tableau visualizations** and clearly defined performance KPIs.

All analysis and visualization were built in **Tableau Desktop**, with light data preparation performed directly on the raw dataset.

---

## 🔗 Live Dashboard

View the interactive Tableau dashboard here:  
👉 **[Tableau Public – U.S. Airline On-Time Performance (2019–2024)](https://public.tableau.com/app/profile/mohammed.zareef.mustafa/viz/U_S_AirlineOn-TimePerformance20192024/Dashboard)**

---

## 🚀 What This Project Shows

- Real-world airline operations analysis using public BTS data
- KPI design for performance and reliability metrics
- Time-series trend analysis (pre- and post-2020)
- Breakdown of delay causes and operational bottlenecks
- Comparative carrier-level performance analysis
- Dashboard storytelling with a **problem-focused layout**
- Interactive filtering for time range and airline selection
- Translating operational data into executive-level insights

This project emphasizes **analytical clarity, interpretability, and storytelling**.

---

## 📊 Analysis Highlights

This dashboard answers questions such as:

- How reliable are U.S. airlines overall?
- How did on-time performance change after 2020?
- Which delay causes contribute most to total delays?
- Are delays driven more by operations or external factors?
- How does flight volume relate to reliability?
- Which airlines consistently perform best on on-time rate?

Key analytical themes include:

- On-time vs delayed flight proportions
- Average delay duration trends
- COVID-era disruption and recovery
- Carrier-driven vs system-driven delays
- Relative insignificance of security-related delays

---

## 🛠 Tools & Skills Used

- Tableau Desktop
- KPI design and validation
- Time-series analysis
- Aggregations and ratios
- Dashboard layout and visual hierarchy
- Interactive filters (Year range, Carrier)
- Top-N ranking logic
- Categorical color encoding
- Data storytelling and insight annotation

---

## 📂 Project Structure

```text
flights_ontime_bts/
│
├── data/
│   └── airline_delay_cause_bts.csv       <-- raw BTS dataset
│
├── tableau/
│   └── flights_ontime_bts.twbx            <-- Tableau packaged workbook
│
├── exports/
│   └── dashboard_preview.png              <-- static dashboard preview
│
├── README.md                              <-- project overview
└── .gitignore
```

---

## 📈 Dashboard Contents

The dashboard includes the following components:

### KPI Summary

- On-Time Rate
- Delay Rate
- Average Delay Minutes
- Cancellation Rate

### Trend Analysis

- On-Time Performance Trend (2019–2024)
- Total Flights Over Time

### Breakdown & Comparison

- Delay Breakdown by Cause (stacked area)
- Top 5 Airlines by On-Time Rate

### Interactivity

- Global year range slider
- Global carrier name filter

---

## 🧠 Key Insights (Quick Summary)

- Overall on-time performance averages **~82–86%**, with clear seasonality.
- Flight volume dropped sharply in 2020 and recovered steadily, but reliability did **not fully stabilize**.
- **Carrier-related and late aircraft delays** dominate total delay minutes across all years.
- Weather contributes meaningfully but is not the primary long-term driver of delays.
- **Security-related delays are negligible** compared to other operational causes.
- Top-performing airlines consistently maintain higher on-time rates even during periods of volatility.

(Insights are summarized directly on the dashboard for quick interpretation.)

---

## 📦 Data Source

- [Airline On-Time Statistics and Delay Causes (BTS)](https://www.kaggle.com/datasets/daryaheyko/airline-on-time-statistics-and-delay-causes-bts?select=Airline_Delay_Cause.csv)

---

## 👤 Author

**Mohammed Zareef-Mustafa**

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE.txt) file for details.
