# Bank-Marketing-Analysis
Bank-Marketing-Analysis
# Bank Marketing Campaign Analysis

An exploratory data analysis (EDA) of a bank's telemarketing campaign data to uncover patterns that could improve future campaign effectiveness.

---

## Overview

This project analyzes customer data from a bank's direct marketing campaign, where clients were contacted by phone and offered a term deposit subscription. The goal was to identify which customer segments, time periods, and contact strategies lead to the highest conversion rates.

**Overall conversion rate: 11.27%**

---

## Key Findings

### 1. Prior Campaign Outcome is the Strongest Predictor
Clients who had previously subscribed converted at **65%** when re-contacted, compared to just **9%** for new contacts — a 7x difference. Re-engaging existing customers should be the top priority for any future campaign.

### 2. Timing Matters — A Lot
Conversion rates vary dramatically by month. **March, December, September, and October** all achieved 44–51% conversion rates, while summer months like **May and August** sit around 7–11%. Concentrating campaign activity in Q4 and early spring could significantly improve ROI.

### 3. Students and Retirees Convert at Disproportionately High Rates
Despite being underrepresented in the dataset, **students (31%)** and **retired clients (25%)** convert at nearly 4x the rate of blue-collar workers (7%). These are high-value segments worth targeting more aggressively.

### 4. Contact Method Makes a Difference
Clients contacted via **cellular phone** were more than twice as likely to convert compared to those contacted via landline.

### 5. Education Has a Weak but Present Effect
**University degree holders** showed the highest conversion rate (13.7%) among groups with sufficient sample size, while clients with only basic education converted at lower rates.

---

## Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Google Colab
- Dataset: [ADD DATASET SOURCE HERE]

---

## Project Structure

```
├── README.md
└── bank_marketing_analysis.ipynb
```

---

## How to Run

1. Open the notebook in Google Colab or Jupyter
2. Upload the dataset CSV file when prompted
3. Run all cells in order

---

## Business Recommendations

Based on the analysis, a more effective campaign strategy would:
- **Prioritize re-contacting** previously converted clients
- **Focus calling windows** on March, September, October, and December
- **Target students and retirees** more deliberately despite their smaller numbers
- **Use cellular contact** over landlines wherever possible
