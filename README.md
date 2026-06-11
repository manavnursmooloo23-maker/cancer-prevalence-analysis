# 📈 Cancer Prevalence Dashboard (Victorian Cancer Registry)

## 🔍 Overview

This project involved designing and developing the **Cancer Prevalence tab** for the Cancer Council Victoria Data Explorer using real-world data from the Victorian Cancer Registry (VCR).

The dashboard provides a **public-facing, interactive tool** that enables clinicians, researchers, policymakers, and the general public to explore cancer prevalence trends in a clear and accessible way.

---

## 📊 Data Description

The dashboard is built using cancer prevalence data from the Victorian Cancer Registry (VCR), structured across multiple datasets to capture demographic, clinical, and geographic dimensions.

The data includes:

* **Timepoints** – Year-based snapshots representing prevalence at a specific point in time
* **Prevalence window (LastXYears)** – Defines the time horizon, representing people diagnosed within that period who are still alive
* **Sex** – Male, Female, and Persons
* **Age groups** – (e.g. 0–24, 25–49, 50–69, 70–79, 80+)
* **Cancer types** – Grouped into main, sub, and detailed tumour classifications
* **Geographical and socio-economic groupings** – Including remoteness, SEIFA, and Integrated Cancer Services (ICS) regions

---

## 📊 Key Dataset Labels

### 🟨 Core Time Variables

* **TimePoints** – Year of data snapshot
* **LastXYears** – Prevalence window (e.g. 1, 5, 10, 20 years)

### 🟩 Demographic Variables

* **Sex** – Male, Female, Persons
* **timepoint_ageg** – Age group classification

### 🟦 Cancer Classification

* **TUMOUR_GROUP_ID** – Unique cancer identifier
* **tumourgroup_main** – Main category (e.g. breast, lung)
* **tumourgroup_sub** – Sub-category
* **tumourgroup_detail** – Detailed classification

### 🟪 Prevalence Measures

* **Total_Prevalence** – Number of people living with cancer
* **Perc_of_Vic_pop_within_age_group** – Percentage within age group

### 🟫 Disparity Variables

* **SEIFA** – Socio-economic grouping
* **Remoteness / Region** – Geographic classification
* **Integrated Cancer Services (ICS)** – Health service regions

---

1. What We Are Looking At




The dashboard presents a high-level view of cancer prevalence in Victoria. In this view, we are analysing the number of people living with cancer (prevalence) for:

All malignant tumours (default selection)
Both males and females
People diagnosed within the past 5 years (5-year prevalence)

This provides an immediate understanding of the scale of cancer prevalence in the population.


---

## 💡 Business Value

* Supports data-driven healthcare planning and resource allocation
* Identifies high-risk demographic and geographic groups
* Highlights inequalities in healthcare access and outcomes
* Improves accessibility of complex public health data for non-technical users

---

## ⚙️ Technical Approach

* **Tool:** Microsoft Power BI
* **Data Processing:** R and Excel
* **Data Modelling:** Measures, relationships, and calculated fields
* **Design:** Interactive visuals, slicers, and custom tooltips
* **Governance:** Small-cell suppression and rounding for privacy compliance

---

## 🚀 Conclusion

This project demonstrates the ability to transform complex healthcare data into a **clear, interactive, and insight-driven dashboard**, supporting real-world decision-making in public health.

---

## 🔗 Links

👉 [View Portfolio Case Study](https://github.com/manavnursmooloo23-maker/portfolio-proj)
