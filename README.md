# 📊 Churn Analysis Dashboard

### Overview

This project presents an **interactive Power BI dashboard** designed to analyze customer churn patterns and key business drivers.
 I developed this dashboard to provide a **data-driven, visual understanding of churn trends**, enabling business stakeholders to identify risk factors and take proactive measures.

---

## 🔑 Key Metrics

The dashboard highlights the following top-level indicators:

| Metric              | Value      | Insight                               |
| ------------------- | ---------- | ------------------------------------- |
| **Total Customers** | **6,418**  | Total active customers in the dataset |
| **New Joiners**     | **411**    | New customers added during the period |
| **Total Churn**     | **1,732**  | Customers who left the service        |
| **Churn Rate**      | **26.99%** | Overall proportion of customers lost  |

These KPIs form the foundation for deeper exploration across demographics, geography, services, and contract details.

---

## 📈 Major Insights & Trends

### 1️⃣ Demographic Analysis

* **Gender:**

  * Male customers account for a slightly higher churn share (**~64%**) compared to females.
  * Indicates potential dissatisfaction or engagement gaps among male users.

* **Age Group:**

  * Churn is lowest in the `<20` group and peaks in the **35–50** and **>50** age brackets (~30% churn).
  * Older customers exhibit a stronger tendency to leave, possibly due to pricing sensitivity or service preferences.

---

### 2️⃣ Geographic Patterns

* **Top 5 States by Churn Rate:**

  * **Jammu (57.19%)** stands out as the highest churn region, followed by Assam (38.13%) and Jharkhand (34.51%).
  * Indicates a need for location-specific retention strategies such as targeted promotions or improved infrastructure.

---

### 3️⃣ Service Usage & Offerings

* **Internet Type:**

  * **Fiber Optic customers** churn the most (**41.10%**), whereas DSL and customers without internet show lower rates.
  * Suggests issues with service quality or pricing for Fiber Optic plans.

* **Add-On Services:**

  * Lack of **Device Protection Plan** and **Online Backup** correlates strongly with churn (71% and 72% of churned users, respectively, did **not** have these services).
  * Offering bundled value-added services could improve retention.

---

### 4️⃣ Account Information

* **Payment Method:**

  * **Mailed checks** have the highest churn (37.82%), hinting that digital payment adoption may align with more stable customer relationships.

* **Contract Type:**

  * **Month-to-month contracts** experience the highest churn (**46.53%**).
  * Customers on longer-term contracts (One or Two Year) churn significantly less, demonstrating the stabilizing effect of longer commitments.

* **Tenure:**

  * Customers with **6–12 months of tenure** show high churn counts, indicating risk during the early engagement phase.

---

### 5️⃣ Churn Distribution by Reason

* **Competitor Influence:**

  * **Competition (761 customers)** is the leading cause of churn, followed by attitude-related reasons (301) and dissatisfaction (300).
  * Competitive pricing and customer service enhancements are key countermeasures.

---

## 💡 Data Science Perspective

From a data science standpoint, these insights highlight:

* **Predictive Features:** Contract type, payment method, service add-ons, and geographic location emerge as strong predictors of churn.
* **Retention Opportunities:** Encouraging long-term contracts, promoting service bundles, and targeting high-churn regions can directly reduce churn rates.

This analysis sets the stage for **predictive modeling** (e.g., Logistic Regression, Random Forest) to identify at-risk customers before they churn.

---

## 🛠️ Tech Stack

* **Power BI** – Data cleaning, transformation, and dashboard visualization
* **Excel/CSV** – Source data preparation
* (Optional) **Python/R** – For future machine learning model development


