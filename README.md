# 🕵️‍♂️ Castle Doctrine & Homicide Analysis

**Exploring the Real Impact of Self-Defense Laws on Violent Crime**

This project investigates whether the **Castle Doctrine**—a self-defense law adopted by some U.S. states—has a measurable effect on homicide rates. Instead of simple correlations, we use **causal inference techniques** to provide a nuanced, reliable estimate of the law’s impact.

---

## 📊 Project Overview

When states adopt laws at different times, naive comparisons can be misleading due to **nationwide crime trends** and **state-specific economic differences**. This project uses **Difference-in-Differences (DiD) estimation** to isolate the causal effect of the Castle Doctrine while controlling for confounding variables such as **poverty** and **unemployment**.

**Key Question:**  
> Does the Castle Doctrine actually change homicide rates, or do apparent spikes just reflect broader trends?

**Main Finding:**  
After controlling for bias, the estimated effect is approximately **+1.41 homicides per 100,000 population** in treated states—showing the importance of rigorous causal analysis.

---

## 🧰 Methodology

- **Data Collection & Cleaning:** Compiled homicide, economic, and political data across U.S. states.  
- **Feature Engineering:** Identified confounders like unemployment, poverty, and prior crime trends.  
- **Difference-in-Differences Analysis:** Compared treated vs. control states to estimate the causal effect.  
- **Visualization & Diagnostics:** Checked assumptions (e.g., parallel trends) and visualized treatment effects over time.  

---

## 💻 Tools & Libraries

- **Python** – Main programming environment  
- **Pandas & NumPy** – Data cleaning, transformation, and aggregation  
- **Matplotlib & Seaborn** – Trend visualization and assumption checks  
- **Scikit-learn (Linear Regression)** – Engine for DiD estimation  

---
**Install required libraries:**
pip install -r requirements.txt
Run the Jupyter notebooks or Python scripts to reproduce the analysis.

🤝 **Connect**
Have questions or suggestions? Feel free to open an issue or reach out!

## 🚀 How to Use

**Clone the repository:**  
```bash
git clone https://github.com/Amnafiaz200/castle-doctrine-analysis.git
cd castle-doctrine-analysis```
