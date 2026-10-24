# AI Usage and Impact Analysis on Students & Professionals

An Exploratory Data Analysis (EDA) project investigating how students and professionals leverage AI tools in their daily workflows, their productivity impacts, and their overall willingness to recommend AI technologies.

---

## Project Overview

Artificial Intelligence tools have rapidly transformed daily tasks, academic learning, and professional operations. This project analyzes survey data to uncover usage patterns, tool preferences, hours saved, and productivity gains across different user demographics.

---

## Key Questions Answered

1. **Which AI tools are most popular among users?**
2. **How do daily usage hours differ between Students and Professionals?**
3. **What is the relationship between daily AI usage hours and perceived Productivity Scores?**
4. **How does recommendation willingness (`Would_Recommend`) vary by user type?**

---

## Tech Stack & Tools

* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

---

## Data Cleaning & Preprocessing

1. **Handling Missing Values & Duplicates:**
   * Removed duplicated records.
   * Imputed missing numeric features using median imputation and categorical features using mode imputation.
2. **Feature Standardization & Text Extraction:**
   * Dropped non-informative identifier columns (`User_ID`).
   * Cleaned string-formatted numerical fields (e.g., extracting clean numeric hours from inputs like `'2 hrs'`).
   * Standardized text formats and casing across categorical features (`Gender`, `AI_Tool`).

---

## Key Findings & Insights

* **Tool Dominance:** `ChatGPT` emerged as the most widely used tool across both students and professionals.
* **Usage Patterns:** Professionals demonstrate higher daily usage hours on average compared to students, primarily driven by work automation.
* **Productivity Gains:** A positive correlation exists between daily usage hours and user-reported productivity scores.
* **User Acceptance:** A significant majority of both students and professionals express a strong willingness to recommend AI tools (`Would_Recommend = Yes`).

---

## Recommendations

1. **Tailored Training:** Educational institutions should provide targeted workshops to help students integrate AI tools effectively into study routines.
2. **Workflow Automation:** Organizations should invest in training employees on specialized AI platforms to maximize professional output.

---

## How to Run the Code

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/Ahmadali2005/ai-usage-impact-analysis.git]
   cd ai-usage-impact-analysis