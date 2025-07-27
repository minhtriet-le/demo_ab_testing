# 📊 A/B Testing: Landing Page Performance Analysis

This project demonstrates how to conduct an A/B test using marketing metrics and statistical testing in Python.

---

## 📁 Contents

- `ab_test_analysis.ipynb`:  
  Jupyter notebook that performs exploratory data analysis and independent T-tests to compare two landing pages (Group A vs Group B).

- `ab_test_full_metrics.csv`:  
  Simulated dataset with 2,000 records (1,000 users for each group), including key marketing metrics:
  - Clicked (for CTR)
  - Converted (for CR)
  - Bounce
  - Time on Page
  - Revenue per Visitor (RPV)

---

## 🧪 A/B Test Description

We simulate a comparison between two landing pages:

- **Group A**: Baseline version
- **Group B**: Modified version (e.g., new design, new CTA)

### Metrics analyzed:

| Metric                   | Description                                  |
|--------------------------|----------------------------------------------|
| Conversion Rate (CR)     | % of users who completed the desired action  |
| Click-Through Rate (CTR) | % of users who clicked on a CTA              |
| Bounce Rate              | % of users who left after viewing one page   |
| Time on Page             | Average time spent on the page (in seconds)  |
| Revenue per Visitor (RPV)| Average revenue generated per user           |

---

## 📊 Statistical Testing

The notebook uses **independent T-tests** to compare metrics between the two groups.  
Null Hypothesis (H0): No significant difference between A and B.

We test at a 95% confidence level (α = 0.05).

---

## 🚀 How to Use

1. Open `ab_test_analysis.ipynb` in Jupyter Notebook or Google Colab.
2. Ensure `ab_test_full_metrics.csv` is in the same directory.
3. Run the notebook to:
   - View summary statistics
   - Perform hypothesis testing
   - Interpret statistical significance

---

## 📌 Note

This is a simulated dataset for educational purposes.  
In real-world A/B tests, sample size calculation, randomization, and experiment duration are crucial.

---

## 👨‍💻 Author

Created by: Minh Triet\
Contact: minhtrietle997@gmail.com
