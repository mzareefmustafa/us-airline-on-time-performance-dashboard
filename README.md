# U.S. Airline On-Time Performance Dashboard (Tableau)

An interactive Tableau dashboard analyzing **U.S. airline on-time performance and delays** using Bureau of Transportation Statistics (BTS) data from **2019–2024**.  

The project examines airline reliability, delay drivers, and operational disruption before and after the COVID-19 shock.

Live dashboard:  
https://public.tableau.com/app/profile/mohammed.zareef.mustafa/viz/U_S_AirlineOn-TimePerformance20192024/Dashboard

## Purpose

This project was built to:
- Evaluate airline reliability using clearly defined performance KPIs
- Understand how delay patterns changed after 2020
- Identify the primary operational drivers of delays
- Translate complex operational data into executive-level insights

## Key Questions Answered

- How reliable are U.S. airlines overall?
- How did on-time performance change post-2020?
- Which delay causes contribute most to total delay time?
- Are delays driven more by airline operations or external factors?
- Which airlines consistently perform best on on-time rate?

## Dashboard Highlights

- KPI summary: on-time rate, delay rate, average delay minutes, cancellation rate
- Time-series trends for reliability and flight volume (2019–2024)
- Delay breakdown by cause (carrier, late aircraft, weather, NAS, security)
- Top-performing airlines by on-time rate
- Interactive filters for year range and airline selection

## Key Insights

- Overall on-time performance averages **~82–86%**, with strong seasonality.
- Flight volume dropped sharply in 2020 and recovered steadily, but reliability did not fully stabilize.
- **Carrier-related and late aircraft delays** account for the majority of delay minutes.
- Weather contributes meaningfully but is not the primary long-term driver of delays.
- Security-related delays are negligible relative to other causes.
- Top-performing airlines maintain higher reliability even during periods of volatility.

## Tools & Skills Used

- Tableau Desktop
- KPI design and validation
- Time-series analysis
- Aggregations and ratios
- Dashboard layout and visual hierarchy
- Interactive filtering
- Top-N ranking logic
- Data storytelling

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

## Data Source

- [Airline On-Time Statistics and Delay Causes (BTS)](https://www.kaggle.com/datasets/daryaheyko/airline-on-time-statistics-and-delay-causes-bts?select=Airline_Delay_Cause.csv)

## Author

**Mohammed Zareef-Mustafa**

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE.txt) file for details.
