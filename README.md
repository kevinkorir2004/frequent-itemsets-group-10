# 🛍️ Frequent Itemsets Analysis – Group 10

## 📚 Course
**Data Mining / Warehousing**

## 👥 Group Members & Roles

- Kevin Korir – Simulated data generation (Part 1)
- Margret – One-hot encoding (Part 2)
- Geoffrey – Frequent itemsets with Apriori
- Bricole & Alfred Gakinya – Closed & maximal frequent itemsets logic

---

## 📌 Project Summary

This project demonstrates frequent pattern mining on a simulated supermarket dataset. We focus on:

- ✅ Frequent Itemsets  
- ✅ Closed Frequent Itemsets  
- ✅ Maximal Frequent Itemsets

We use the **Apriori algorithm** from `mlxtend` with detailed inline comments for educational clarity.

---

## 📁 Files in This Repo

| File                          | Description                                 |
|-------------------------------|---------------------------------------------|
| `frequent_itemsets_analysis.ipynb` | Fully commented notebook |
| `supermarket_transactions.csv`     | Simulated transactions (3000 rows) |
| `frequent_itemsets.csv`            | Output from apriori |
| `closed_itemsets.csv`              | Filtered closed itemsets |
| `maximal_itemsets.csv`             | Filtered maximal itemsets |

---

## ⚙️ Requirements

```bash
pip install pandas mlxtend
