# Day 17 – Vehicle Cost Analysis Dashboard

## Overview

Day 17 focused on building a complete Vehicle Cost Analysis Dashboard using Claude and a provided CSV dataset. The objective was to generate an interactive HTML dashboard that compares fuel types, maintenance costs, running costs, environmental impact, and E85 fuel economics based on real vehicle data.

---

## Vehicle Configuration

| Parameter | Value |
|------------|---------|
| Vehicle | Swift Dzire |
| Fuel Type | Petrol (E20) |
| Vehicle Age | 12 Years |
| Monthly Distance | 1000 km/month |

---

## Task Completed

### 1. Dataset Analysis
- Downloaded and uploaded the provided CSV dataset.
- Processed fuel efficiency, maintenance, emissions, and fuel pricing data.

### 2. Dashboard Generation
Generated a complete HTML dashboard featuring:

- KPI Summary Cards
- Fuel Cost Comparison
- CO₂ Emission Analysis
- E85 Viability Analysis
- Cost vs Vehicle Age Analysis
- Maintenance Cost Comparison
- Fuel Recommendation Engine
- SVG Charts & Visualizations
- Environmental Impact Dashboard

### 3. Dashboard Execution
- Saved generated HTML file.
- Opened locally in browser.
- Verified responsiveness and chart rendering.

---

## Key Findings

### Cost per Kilometer

| Fuel Type | Cost/km |
|------------|---------|
| EV | ₹1.75 |
| CNG | ₹3.32 |
| Diesel | ₹4.67 |
| Petrol | ₹6.15 |
| E85 | ₹6.37 |

### CO₂ Emissions

| Fuel Type | CO₂/km |
|------------|---------|
| E85 | Lowest Liquid Fuel Emissions |
| EV | Near-Zero Tailpipe Emissions |
| CNG | Lower than Petrol |
| Diesel | High |
| Petrol | Highest among compared fuels |

### E85 Analysis

- Pump Price Advantage: **18% cheaper than Petrol**
- Running Cost Penalty: **+3.6%**
- Break-Even Price: **₹79.1/L**
- Current E85 Price: **₹82/L**
- Conclusion: E85 is environmentally beneficial but currently not economically superior for this vehicle.

---

## Dashboard Insights

### Advantages of Petrol (Current Fuel)

- Wide fuel availability
- Established service network
- Reliable for mixed driving conditions

### Advantages of E85

- Lower emissions
- Renewable fuel source
- Reduced fossil fuel dependency

### Limitations of E85

- Lower mileage
- Limited fuel station availability
- Higher effective running cost

---

## Skills Learned

- CSV Data Analysis
- Dashboard Design
- KPI Visualization
- Cost Modeling
- Environmental Impact Analysis
- HTML Dashboard Development
- SVG Chart Generation
- Vehicle Operating Cost Analytics

---

## Screenshots

### Dashboard Overview
![Dashboard Overview](screenshots/dashboard-overview.png)

### Fuel Cost & Emissions Analysis
![Fuel Cost Analysis](screenshots/fuel-cost-analysis.png)

### E85 Score & Vehicle Age Analysis
![E85 Analysis](screenshots/e85-analysis.png)

### Fuel Comparison & Recommendations
![Fuel Comparison](screenshots/fuel-comparison.png)

---

## Key Learnings

1. Lower fuel price does not always mean lower running cost.
2. Vehicle age significantly impacts operating expenses.
3. E85 offers environmental benefits but may not provide cost savings.
4. Data-driven dashboards help evaluate fuel choices objectively.
5. Visual analytics improve decision-making compared to raw datasets.

---

## Files Included

```
Day17/
│
├── README.md
├── e85_dashboard.html
│
└── screenshots/
    ├── dashboard-overview.png
    ├── fuel-cost-analysis.png
    ├── e85-analysis.png
    └── fuel-comparison.png
```

---

## Outcome

Successfully generated and deployed an interactive Vehicle Cost Analysis Dashboard using Claude. The dashboard provided comprehensive insights into fuel economics, environmental impact, maintenance costs, and E85 feasibility for a 12-year-old Swift Dzire, demonstrating practical applications of data analytics and visualization in real-world decision-making.
