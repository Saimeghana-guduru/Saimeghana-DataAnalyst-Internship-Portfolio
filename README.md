# 🏨 Data-Driven Revenue Optimization & Attrition Mitigation
### **ApexPlanet Data Analytics Internship — Final Capstone Master Portfolio**

---

## 📈 Executive Portfolio Dashboard
This comprehensive capstone repository transitions a massive hospitality dataset from raw, unverified operational noise into a validated executive revenue preservation framework. By establishing an end-to-end data pipeline across **Python**, **SQL**, and **Power BI**, this project diagnoses, validates, and builds solutions around a multi-million dollar business challenge.

### 🎥 Project Walkthrough & Artifacts
* 🚀 **Interactive Executive Presentation:** [Download PowerPoint Deck (.pptx)](./Final_Presentation.pptx)
* 🎓 **Competency Summary:** [Review Key Learnings & Demonstrated Technical Skills](./LEARNINGS_AND_SKILLS.md)

---

## 📊 The Macro Business Problem (By The Numbers)
Initial analytical architecture exposed that while the property network operates on a healthy high-volume baseline, profitability is actively choked by extreme transactional volatility:

| Core Business Visual KPI | Validated Portfolio Metric | Strategic Context |
| :--- | :--- | :--- |
| **Cleaned Inventory Scale** | **87,377 Total Bookings** | Down-sampled from 119K raw rows for pure integrity |
| **Realized Net Revenue** | **$22.77 Million** | Total realized income across verified check-ins |
| **Average Daily Rate (ADR)** | **$105.00** | Standard billing metric across physical property assets |
| **Baseline Operational Attrition**| **27% Cancellation Rate** | **The Primary Profit Leak / Core Friction Vector** |

---

## 🛠️ The Tech Stack & Architecture

```text
 [Raw Data (~119K rows)] ──> [Python / Pandas Cleaning] ──> [Exploratory Data Analysis (EDA)]
                                                                        │
  [Power BI Dashboard] <─── [SQL Relational Database Views] <───────────┘
           │
           └───> [SciPy Statistical Proofs] ──> [Executive Business Strategy]
```

* **Data Cleansing & Diagnostics:** Python (Pandas, NumPy)
* **Relational Database Engineering:** MySQL Standard Queries
* **Business Intelligence Canvas:** Power BI Desktop 

---

## 🗺️ The Internship Milestone Journey

### 🪠 Phase 1: Data Rigor & Preprocessing (`Hotel_Bookings_Cleaning.ipynb`)
Eliminated structural noise from 119K initial records to construct a pristine analytical substrate of **87,377 rows**. 
* Systemically isolated and resolved missing parameters in major tracking codes (`agent` and `company` fields).
* Handled temporal variables to construct a normalized, dependable `arrival_date` pipeline.
* Stripped mathematical outliers from transaction boundaries (invalid zero or negative ADR inputs) to secure financial reporting integrity.

### 🔍 Phase 2: Exploratory Analysis & Reporting (`EDA(descriptive,univariate and multivariate analysis).ipynb`)
Executed deep multi-dimensional data profiling to surface performance markers.
* Identified major performance contrasts between high-volume **City Hotels** and seasonal **Resort Hotels**.
* Mapped critical market distribution channel footprints, revealing that indirect **TA/TO (Travel Agency/Tour Operator)** pipelines generate over 85% of traffic but concurrently introduce toxic operational volatility.

### 🗄️ Phase 3: Relational Engineering & Visual BI (`deep_dive_analysis.sql`)
Engineered database views to extract precise dimensions and feed the dashboard interface.
* Constructed optimized SQL grouping blocks tracking localized revenue peaks, exposing August as the high-stakes capacity bottleneck.
* Designed an executive, high-contrast **Power BI Dashboard** engineered with advanced interactive cross-filtering slicers, geographic travel tracking maps, and transparent area trend-charts for immediate executive choice-support.

### 🧪 Phase 4: Statistical Validation Engines (`Testing.ipynb`)
Moved from observation to scientific proof, applying Python scripting to execute diagnostic verification models:
1. **Two-Sample T-Test (Lead Time vs Attrition):** Mathematically proved that canceled reservations remain stagnant in the pipeline an average of **35 days longer** than confirmed check-ins ($105.7 \text{ days vs } 70.1 \text{ days}$; $p\text{-value} < 0.01$). Long booking horizons act as a direct cancellation catalyst.
2. **Chi-Square Test of Independence (Loyalty vs Attrition):** Confirmed that established returning guests maintain an exceptional **7.6% attrition rate** compared to **28.3%** for new acquisitions ($p\text{-value} \approx 0$). Brand loyalty acts as a statistical revenue shield.

---

## 💡 The Path Forward: Strategic Roadmap
Based on the validated insights generated across this portfolio, three structural implementations are proposed to plug the 27% revenue leak:

1. **Dynamic Deposit Barriers:** Mandate full non-refundable deposit terms on all reservations established with a lead-horizon greater than 60 days—focusing specifically on third-party TA/TO channels to neutralize empty inventory hold-times.
2. **Loyalty Inversion Allocation:** Reallocate 15% of heavy top-of-funnel customer acquisition capital directly into past-guest retention marketing. Promote direct-channel bookings to secure high-reliability arrivals while eliminating agent commissions.
3. **Calculated Capacity Overselling:** Intentionally overbook property capacity metrics by a calculated safety margin during peak seasonal months using our verified 27% baseline attrition threshold to ensure 100% true physical room utilization.

---

## 📂 Repository Directory Directory
```text
├── Task1_DataCleaning/
│   ├── hotel_bookings.csv
|   ├── data_dictionary.xlsx
|   ├── Hotel_Bookings_Cleaning.ipynb
│   └── cleaned_hotel_bookings.csv
├── Task2_EDA_BI/
│   ├── EDA(descriptive,univariate and multivariate analysis).ipynb
│   ├── sql_queries.sql
│   └── dashboard.xlsx
├── Task3_DeepDiveAnalysis/
│   ├── deep_dive_analysis.sql
│   └── dashboard.pbix
├── Task4_Storytelling_Validation/
│   ├── Testing.ipynb
│   └── Presentation.pptx
├── LEARNINGS_AND_SKILLS.md
├── Final_Presentation.pptx           
└── README.md                        
