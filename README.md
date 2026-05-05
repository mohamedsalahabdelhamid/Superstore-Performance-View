# 🛒 Superstore Executive Analytics Dashboard

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:36D1DC,50:5B86E5,100:232526&height=220&section=header&text=Superstore%20Retail%20BI&fontSize=45&fontColor=ffffff&animation=fadeIn" alt="Header"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Excel"/>
  <img src="https://img.shields.io/badge/Power%20Pivot-0078D4?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Power Pivot"/>
  <img src="https://img.shields.io/badge/DAX-F2C811?style=for-the-badge&logo=analytics&logoColor=black" alt="DAX"/>
  <img src="https://img.shields.io/badge/Star%20Schema-003B57?style=for-the-badge&logo=postgresql&logoColor=white" alt="Modeling"/>
</p>

---

## 🖼️ Dashboard Showcase
<p align="center">
  <img src="https://raw.githubusercontent.com/mohamedsalahabdelhamid/Superstore-Performance-View/main/Screenshot%202026-02-27%20171925.png" width="900" alt="Superstore Dashboard Screenshot"/>
</p>

---

## 📌 Project Architecture
This project demonstrates a complete end-to-end data analytics workflow using **Microsoft Excel** as a powerful Business Intelligence tool, applying concepts typically used in enterprise BI solutions like Power BI.

```mermaid
graph LR
    A[Raw Sales Data] --> B[Power Query ETL]
    B --> C[Star Schema Modeling]
    C --> D[DAX Metric Development]
    D --> E[Dynamic UI/UX Design]
```

---

## 🛠️ The Technical Stack

<details>
<summary><b>🔹 1. Data Engineering (Power Query)</b></summary>
<br>
<ul>
  <li>Standardized transactional datasets with millions of records.</li>
  <li>Built robust ETL pipelines to handle geographic normalization.</li>
  <li>Automated data refreshing via structured table connections.</li>
</ul>
</details>

<details>
<summary><b>🔹 2. Star Schema Design (Power Pivot)</b></summary>
<br>
<ul>
  <li>Developed a high-performance relational model.</li>
  <li>Separated <b>Fact Sales</b> from <b>Dimension Tables</b> (Products, Customers, Geography, Calendar).</li>
  <li>Ensured lightning-fast filtering across multi-year data.</li>
</ul>
</details>

<details>
<summary><b>🔹 3. Analytical Intelligence (DAX)</b></summary>
<br>
Developed custom measures for executive KPIs:
<ul>
  <li><b>Dynamic Ranking:</b> Top 10 products/customers by profit.</li>
  <li><b>Shipping Status:</b> Tracking efficiency vs. segment performance.</li>
  <li><b>Category Contribution:</b> Percentage-based revenue mix.</li>
</ul>
</details>

---

## 📊 Business Insights
*   **💻 Tech Dominance:** The Technology category accounts for the largest revenue share, but Office Supplies show higher stability in specific regions.
*   **📦 Logistics Impact:** Identified a direct correlation between shipping delays and lower performance in the "Corporate" segment.
*   **🌍 Regional Optimization:** Specific "Profit Deserts" were identified where sales are high but margins are negative due to logistics costs.

---

## 👤 Author
**Mohamed Salah Abdelhamid**
*   LinkedIn: [mohamedsalah-abdelhamid](https://www.linkedin.com/in/mohamedsalah-abdelhamid/)
*   GitHub: [@mohamedsalahabdelhamid](https://github.com/mohamedsalahabdelhamid)

---
<div align="center">
  <sub>Mastering Retail Analytics through Business Intelligence 🛒</sub>
</div>
