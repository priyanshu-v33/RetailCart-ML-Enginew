## 📌 Executive Summary
**RetailCart ML Engine** is an end-to-end Machine Learning and Customer Analytics platform designed for e-commerce platforms to transition from generic, "one-size-fits-all" marketing to highly targeted, persona-driven retention strategies. 

By applying **unsupervised clustering algorithms** and **dimensionality reduction (PCA)** on multi-dimensional transactional and demographic data, RetailCart ML Engine automatically partitions customers into distinct behavioral segments, identifies churn risks, and flags high-value VIP shoppers.

---

## 🚨 The Problem Statement
Modern e-commerce platforms handle thousands of active customer profiles across multiple regions. Operating with blanket marketing strategies leads to critical business bottlenecks:

1. **Capital Inefficiency:** High marketing spend wasted on low-converting audiences.
2. **Revenue Leakage:** Inability to proactively identify, engage, and retain high-value VIP buyers.
3. **Customer Churn:** Delayed detection of disengaged or churn-prone shoppers before they drop off completely.

---

## 🎯 Project Objectives & Aim
* **Data Processing & Feature Engineering:** Transform 22 raw attributes (demographics, purchase history, web activity, campaign response) into high-signal metrics (e.g., Total Spend, Tenure, Household Dynamics).
* **Dimensionality Reduction:** Utilize Principal Component Analysis (PCA) to overcome multicollinearity and compress high-dimensional feature space while retaining maximum variance.
* **Intelligent Clustering:** Benchmark **K-Means**, **Agglomerative Hierarchical Clustering**, and **DBSCAN** to determine optimal mathematical user clusters.
* **Business Personas & Strategy:** Translate raw cluster outputs into actionable customer personas (*Champions*, *Budget Shoppers*, *At-Risk / Churn-Prone*, *Promotional Responders*) with specific marketing workflows.
* **Interactive Dashboard:** Deploy a Streamlit web application enabling real-time segment inspection, scenario filtering, and exportable customer lists.

---

## 🗺️ System Architecture & Workflow
