# E-Commerce Sales Data Analysis Using Association Rule Mining (ARM)

An end-to-end data-mining project that discovers purchasing patterns in
3,000+ e-commerce transactions using **7 ARM algorithms**, and predicts
product returns using **classification models**.

## 📊 Highlights

| Metric | Value |
|---|---|
| Transactions analyzed | 3,000+ |
| ARM algorithms implemented | Apriori, FP-Growth, DIC, FP-Trace, Partitioned Apriori, MAFIA, CHARM |
| Top rules | Lift up to 5.20 |
| Best classifier | Decision Tree (AUC 0.84, F1 0.52) |
| Fastest miner | FP-Growth (5× faster than Apriori) |

## 📁 Files

- `ecommerce_arm_pipeline.py` — Full pipeline: EDA → ARM (7 algorithms) → Classification
- `Team26_ARM_Report.pdf` — Detailed project report

## 🎯 Key Business Insights

- **Corporate + Online** customers dominate Office Supplies & Technology.
- **UPI payment** correlates strongly with Home & Kitchen Appliances.
- **Shipping > 5 days + Discount > 20% + Satisfaction < 3** → 78% probability of return.

## 🚀 How to Run

```bash
pip install pandas numpy matplotlib seaborn mlxtend scikit-learn
python ecommerce_arm_pipeline.py