# 📦 E-Commerce OTIF & Perfect Order Analytics
> **Transforming Supply Chain Inefficiency into Revenue Growth**

This repository contains a multi-layered analytics suite designed to solve critical fulfillment challenges for a South African e-commerce leader. By measuring **On-Time In-Full (OTIF)** performance, this project identifies operational bottlenecks and quantifies revenue leakage.

[**🚀 View Interactive Tableau Dashboard**](https://public.tableau.com/views/E-CommerceOTIFPerfectOrderAnalytics/DailyOperationsView?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 🚨 The Business Problem
The organization faced significant revenue loss due to incomplete deliveries and a lack of visibility across warehouses and carriers.

**Management required data-driven answers to:**
* **Reliability:** Are we delivering orders On-Time and In-Full?
* **Bottlenecks:** Which regions or warehouses are underperforming?
* **Financial Impact:** How much revenue is lost to damages and returns?

---

## 🛠️ Technical Stack
* **Visualization:** Tableau (Multi-page Interactive Dashboards)
* **Data Processing:** Python (Pandas/NumPy), SQL
* **Environment:** Google Colab
* **Metrics:** OTIF Rate, Perfect Order Rate, Revenue Leakage Analysis

---

## 📊 Dashboard Architecture
The solution is divided into four strategic views, tailored for different organizational stakeholders:

### 1. Executive OTIF Overview
*High-level summary of supply chain health.*
* **Key Metric:** 61.3% OTIF Rate.
* **Critical Insight:** Identifies a significant "In-Full" bottleneck at 72.3%.
![Executive OTIF Overview](Dashboards_Images/Executive_OTIF_Dashboard.png)

### 2. Product & SKU Performance Explorer
*Drill-down into specific inventory items driving gaps.*
* **Key Metric:** Electronics category drives the highest lost revenue at **R805,647**.
* **Top Offender:** SKU-060 (**R29,513** in losses).
![Product & SKU Performance](Dashboards_Images/Product_&_SKU_Performance_Explorer_Dashboard.png)

### 3. Root Cause Explorer
*Operational mapping of warehouse-carrier shipping lanes.*
* **Key Metric:** **WH-CPT** leads in lost revenue at **R793,539**.
* **Worst Lane:** WH-JHB to KZN via FastTrack (49.4% OTIF).
![Root Cause Explorer](Dashboards_Images/Root_Cause_Explorer_Dashboard.png)

### 4. Daily Operation View
*Tactical "heartbeat" for real-time monitoring.*
* **Volume:** Daily Delivered Revenue averages **R200k - R300k**.
* **Failure Analysis:** Short shipments and returns average **~50 units daily**.
![Daily Operation View](Dashboards_Images/Daily_Operation_Views_Dashboard.png)

---

## 🚀 Strategic Roadmap

| Horizon | Recommendation |
| :--- | :--- |
| **Short-Term** | Immediate audit of **SKU-060** and the **WH-CPT** facility to plug revenue leaks. |
| **Medium-Term** | Renegotiate carrier contracts, specifically addressing **EconoMove's** low success rate. |
| **Long-Term** | Implement automated exception monitoring and predictive OTIF modeling. |

---

## 📂 Project Structure
```text
├── Dashboards Images/   # High-resolution dashboard exports
├── Dataset/             # Line-level fulfillment data
├── Documentation/       # KPI definitions and business analysis
├── Google Collab Files/ # Python/SQL scripts for ETL
├── Icons and stickers/  # UI/UX visual assets
├── Tableau/             # Packaged Workbook (.twbx)
├── README
└── LICENCE

```
## 📫 Contact & Feedback
Project Author: Bheki Mogola

Website: [**Bheki Mogola**](https://bhekimogola.netlify.app/)
