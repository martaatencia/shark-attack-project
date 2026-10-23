# 🦈 Shark Attacks - Data Wrangling & EDA Mini Project

*A comprehensive data cleaning and exploratory data analysis (EDA) project focused on transforming a messy shark attack dataset into actionable insights using Python and Pandas.*

---

## 🎯 Project Overview & Business Case

This project was built during a 4-day intensive data wrangling quest. Our mission was to take a raw, unformatted dataset of historical shark attacks, apply rigorous data cleaning workflows, and analyze the data to validate specific risk-related hypotheses.

### 💼 Our Business Case: Insurance Company Risk Assessment
As an **actuarial and risk assessment team for an insurance company**, our goal is to analyze historical shark attack data to accurately evaluate risk profiles, optimize insurance policy pricing (premiums) for high-risk water activities, and identify geographical hot zones where coverage terms might need adjustment.

### 📊 Core Hypotheses & Findings
To guide our data wrangling and exploratory data analysis, we formulated and tested three core hypotheses:

1. **`Hypothesis 1:` Shark attacks are more likely to happen to male individuals.**
   * 🛑 **Status:** **PROVEN**. The data clearly shows a significantly higher volume of total shark encounters involving male individuals.
   
2. **`Hypothesis 2:` Men are more likely to provoke shark attacks than women.**
   * 🛑 **Status:** **REFUTED**. Our analysis indicates that the proportion of provoked vs. unprovoked attacks is highly similar between men and women. Gender does not heavily influence the likelihood of provoking an attack.
   
3. **`Hypothesis 3:` Most shark attacks happen in the USA and Australia.**
   * 🛑 **Status:** **PROVEN**. These two countries represent the overwhelming majority of recorded historical shark incidents globally.

---

## 👥 Team Collaboration & Roadmap

Team members:
- **Marta ATENCIA**
- **Juan CONTRERAS**
- **Erzsebet FUZES**

Unlike rigid isolated roles, our team focused heavily on **collaborative development and alignment**, switching to a split-task strategy only when the foundation was solidly built.

* **Day 1: Full Team Alignment** 
  We worked entirely together to explore the dataset, define our business case (Insurance Risk Assessment), and outline the project roadmap.
* **Day 2: Shared Coding Foundation** 
  We kicked off the cleaning notebook together as a whole team. This ensured everyone was on the same page regarding coding standards, Git/Colab workflows, and the initial Regex logic.
* **Day 3: Divided & Conquered** 
  With a strong shared foundation, we split the tasks to maximize efficiency:
  * **2 Team Members:** Focused fully on deep data cleaning, formatting, and handling missing values.
  * **1 Team Member:** Focused strictly on data filtering, aggregation, and preparing data subsets for testing our hypotheses.
* **Day 4: Integration & Delivery** 
  The whole team reunited to lock down and review the code, finalize the data visualizations, validate our 3 core hypotheses, and build the client-facing presentation.


---

## 🛠️ Tech Stack & Best Practices

- **Language:** Python 3.13.16 (main, Oct  1 2026, 15:40:24) [GCC 13.3.0] 
- **Libraries:** Pandas, NumPy, Re (Regex)
- **Environment:** Google Colab (Collaborative Development)

---

## 📦 Data Cleaning Techniques Implemented

To transition the dataset from raw to analysis-ready, we applied ** the following distinct data cleaning techniques**:

1. **Handling Missing Values:** Dropped columns with critical low data density and imputed logical values for missing attributes.
2. **Duplicate Removal:** Identified and eliminated fully duplicated rows.
3. **String Manipulation (Regex):** Cleaned messy activity descriptions and location names into uniform categories.
4. **Data Type Formatting:** Standardized non-date columns, aligned text casing, and stripped white spaces.

---
