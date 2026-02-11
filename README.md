# E-Commerce OTIF & Perfect Order Analytics

📌 **Project Overview**

This project provides a multi-layered analytics suite designed to solve critical fulfillment challenges for a South African e-commerce company. The primary focus is measuring On-Time In-Full (OTIF) performance and quantifying the revenue leakage caused by operational failures.

---

## 🚨 The Business Problem

The organization was facing significant revenue loss due to incomplete deliveries and a lack of visibility into which warehouses, carriers, or products were driving these failures. Management required data-driven insights to answer:

- **Are we delivering orders On-Time and In-Full?**
- **Where are the regional and operational bottlenecks?**
- **How much revenue is being lost to damages and returns?**

---

## 📊 Dashboard Architecture

The solution is divided into four strategic views to serve different levels of the organization:

### 1. Executive OTIF Overview
Provides a high-level summary of supply chain reliability and the "Perfect Order" rate.

- **Key Metric:** 61.3% OTIF Rate
- **Insight:** Identifies a significant "In-Full" bottleneck at 72.3%

![Executive OTIF Overview](Dashboard_Images/executive_otif_overview.png)

---

### 2. Product & SKU Performance Explorer
Drills down into specific inventory items driving fulfillment gaps.

- **Key Metric:** Electronics category drives the highest lost revenue at **R805,647**
- **Top Offender:** SKU-060 (**R29,513** in losses)

![Product & SKU Performance](Dashboards%20Images/product_sku_performance.png)

---

### 3. Root Cause Explorer
Identifies inefficiencies in specific warehouse-carrier shipping lanes.

- **Key Metric:** WH-CPT leads in lost revenue at **R793,539**
- **Worst Lane:** WH-JHB to KZN via FastTrack (49.4% OTIF)

![Root Cause Explorer](Dashboards%20Images/root_cause_explorer.png)

---

### 4. Daily Operation View
A tactical "heartbeat" view for real-time monitoring of daily volumes and failure types.

- **Key Metric:** Daily Delivered Revenue averages between **R200k - R300k**
- **Failure Analysis:** Short shipments and returns average **~50 units daily**

![Daily Operation View](Dashboards%20Images/daily_operation_view.png)

---

## 🛠️ Project Structure
├── Dashboards Images/ # High-resolution exports of the Tableau views
├── Dataset/ # Line-level fulfillment data used for analysis
├── Documentation/ # Comprehensive project report and KPI definitions
├── Google Collab Files/ # Python/SQL scripts for data cleaning and prep
├── Icons and stickers/ # Visual assets used in dashboard design
└── Tableau/ # Packaged Tableau Workbook (.twbx)

---

## 🚀 Key Strategic Recommendations

| Timeframe | Recommendation |
|-----------|----------------|
| **Short-Term** | Immediate audit of the top 10 SKUs (starting with SKU-060) and the WH-CPT facility to plug revenue leaks |
| **Medium-Term** | Renegotiate carrier contracts, specifically addressing EconoMove's low successful unit counts |
| **Long-Term** | Implement automated exception monitoring and predictive OTIF models |

---

## 🔗 How to Access

- **Interactive Dashboard:** [View Live on Tableau Public](https://public.tableau.com/views/E-CommerceOTIFPerfectOrderAnalytics/DailyOperationsView?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- **Full Documentation:** Refer to the [`Documentation/`](Documentation/) folder for the detailed business analysis

---

## 📫 Contact & Feedback

For questions or collaboration opportunities, please reach out or open an issue in this repository.

**#SupplyChainAnalytics #OTIF #PerfectOrder #Tableau #EcommerceAnalytics #DataVisualization**
