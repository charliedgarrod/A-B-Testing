# 🧪 Homepage A/B Testing — Bike Shop Loyalty Program

This project evaluates the impact of a homepage design change on user engagement with the loyalty program of an online bicycle store. Using a full A/B testing workflow—from power analysis to statistical inference—the notebook assesses whether the new interface boosts click-through rates (CTR) to the loyalty sign-up page.

---

## 🎯 Objective

The store aimed to increase CTR from 50% to at least 55% by redesigning its homepage. This test investigates whether the change produced a statistically significant improvement in user engagement.

---

## 🛠️ Methodology

- **Power Analysis**  
  Determined the required sample size to detect a 5% uplift in CTR with sufficient statistical power.

- **Data Cleaning & Preparation**  
  Removed duplicates, normalized column names, and ensured input consistency.

- **Group Assignment**  
  Randomized users into control and treatment groups using server IDs for unbiased comparison.

- **Sampling & Balance Checks**  
  Drew equal-sized samples and validated group similarity.

- **Statistical Testing**  
  Performed a two-proportion z-test to compare CTRs and assess significance.

---

## 📈 Results

- The new homepage led to a *slight decrease* in click-throughs to the loyalty page.
- The difference was statistically significant (*p < 0.05*), resulting in rejection of the null hypothesis.
- The redesign negatively impacted user engagement, providing valuable feedback for future UX decisions.

---

## 🔍 Insights

- Even small UI changes can have measurable effects on user behavior.
- Rigorous experimentation is essential for evaluating product improvements.
- The project serves as a reusable blueprint for running A/B tests—from planning to interpretation.

---

## 🧬 Tools Used

- **Python**: Pandas, NumPy, SciPy  
- **Statistical Techniques**: Power analysis, random sampling, hypothesis testing
