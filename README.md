# Strategic Supplier Segmentation for Resilient Supply Chains 🌍⚙️

> **Objective:** To segment a network of 200 suppliers using K-Means clustering across Operational KPIs and ESG (Environmental, Social, and Governance) metrics, transforming raw procurement data into a strategic framework for resilient, sustainable supply chain management.

---

## 📑 Table of Contents
1. [Business Problem](#-business-problem)
2. [Dataset Overview](#-dataset-overview)
3. [Tools and Technologies](#%EF%B8%8F-tools-and-technologies)
4. [Methodology](#-methodology)
5. [Optimized Results: The 4 Clusters](#-optimized-results-the-4-clusters)
6. [Strategic Recommendations](#-strategic-recommendations)
7. [How to Run This Project](#-how-to-run-this-project)
8. [Author & Contact](#-author--contact)

---

## 💼 Business Problem
Modern supply chains face a dual mandate: maintain aggressive operational efficiency (speed, cost, accuracy) while simultaneously meeting strict global sustainability and ESG compliance standards. Traditional procurement models fail to balance these competing priorities.

**Goal:** Utilize unsupervised machine learning to uncover hidden supplier performance patterns, allowing the business to identify risk, target capability-building investments, and align procurement strategies with corporate sustainability goals.

---

## 📂 Dataset Overview
The project integrates operational and environmental data for 200 active suppliers.
* **Data Sources:** `Supplier_KPI.csv` and `Supplier_ESG.csv`
* **Operational Metrics:** On-Time Delivery Rate, Lead Time Days, Defect Rate, Cost Competitiveness, Order Accuracy.
* **ESG Metrics:** Carbon Emissions, Energy Efficiency, Waste Management, Labor Practices, Governance Transparency.

---

## 🛠️ Tools and Technologies
* **Language:** Python
* **Data Integration & Scaling:** Pandas, NumPy, Scikit-Learn (`StandardScaler`)
* **Machine Learning:** Scikit-Learn (K-Means Clustering)
* **Data Visualization:** Matplotlib, Seaborn

---

## ⚙️ Methodology
1. **Data Integration:** Merged operational KPI and ESG datasets on `Supplier_ID` to create a unified performance view.
2. **Preprocessing:** Handled data scaling and normalization to ensure high-variance metrics (e.g., carbon emissions) did not disproportionately skew the clustering algorithm.
3. **Modeling Strategy:** Applied K-Means clustering, utilizing the Elbow Method to determine the optimal number of distinct, actionable supplier segments (k=4).
4. **Analysis:** Visualized the clusters to identify critical trade-offs, such as delivery speed versus carbon footprint.

---

## 📈 Optimized Results: The 4 Clusters
The K-Means model successfully categorized the supplier base into four distinct strategic tiers:

1. 🟢 **High-Impact Performers:** Elite suppliers excelling in both operational efficiency and ESG compliance. The backbone of the supply chain.
2. 🟡 **Balanced Tier-1:** Reliable partners with steady operational metrics but average sustainability scores.
3. 🟠 **Sustainable Niche:** Suppliers with exceptional environmental practices but slower operational speeds or higher costs.
4. 🔴 **Agile but Underdeveloped:** Highly flexible and fast suppliers that carry significant ESG risks or lack mature governance structures.

---

## 🚀 Strategic Recommendations
By applying this segmentation model, procurement teams can shift from a "one-size-fits-all" approach to a targeted strategy:
* **Tiered Partnerships:** Prioritize the *Balanced Tier-1* cluster for core, high-volume operations, while utilizing the *Sustainable Niche* cluster to fulfill specific green-procurement mandates.
* **Targeted Investments:** Deploy capability-building resources specifically to the *Agile but Underdeveloped* cluster to mitigate long-term compliance risks without losing their operational speed.
* **ESG-Aligned Procurement:** Ensure future supplier onboarding actively screens for the traits identified in the *High-Impact* cluster.

---

## 💻 How to Run This Project
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/CollinAslinDsouza/strategic-supplier-segmentation.git](https://github.com/CollinAslinDsouza/strategic-supplier-segmentation.git)
