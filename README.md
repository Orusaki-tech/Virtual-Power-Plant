Markdown
# Virtual Power Plant (VPP) Analytics Pipeline ⚡

An end-to-end data pipeline and analytics project built to analyze grid loads, solar generation, and spot pricing anomalies across **Great Britain (GB)** and **Ireland (IE)** using Python, dbt (data build tool), and Jupyter Notebooks.

---

## 📊 Executive Analytical Summary

* **Great Britain (GB) Summer Solar Surge:** Winter baseline loads peaked at **57,678 MW** in January with negligible solar penetration (0.33% / 155 MW). By June, summer solar generation peaked at **1,758 MW**, driving solar penetration up to **4.73%** while overall grid demand dipped to **34,160 MW**.
* **Ireland (IE) Winter Price Volatility:** Ireland's market experienced extreme seasonal financial pressure. While summer grid loads stabilized with costs dropping to **€133.8k** in August and peak spot prices capped at **€102.70/MWh** in June, winter brought extreme pricing pressure—hitting a max spot price of **€920.77/MWh** in February and driving average monthly grid costs up to **€199.8k**.

---

## 🛠️ Project Structure

```text
Virtual-Power-Plant/
│
├── vpp_analytics/                # dbt project directory
│   ├── models/                   # SQL data models (staging & marts)
│   │   ├── staging/              # Raw data cleaning and normalization
│   │   └── marts/                # Aggregated analytical summaries
│   ├── seeds/                    # Source CSV data files
│   └── dbt_project.yml           # dbt configuration
│
└── Virtual_Power_Plant.ipynb     # End-to-end execution & reporting notebook
🚀 Getting Started
Prerequisites
Python 3.x

dbt-core / dbt adapter

Jupyter Notebook

Running the Pipeline
Clone the repository:

Bash
git clone [https://github.com/Orusaki-tech/Virtual-Power-Plant.git](https://github.com/Orusaki-tech/Virtual-Power-Plant.git)
Navigate into the dbt project folder and run your models:

Bash
cd vpp_analytics
dbt run
Open the Jupyter Notebook Virtual_Power_Plant.ipynb to review the full analytical workflow and data visualizations.
