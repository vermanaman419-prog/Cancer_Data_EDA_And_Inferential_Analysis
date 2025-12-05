# 📊 Cancer Data EDA & Inferential Analysis

A comprehensive exploratory and statistical analysis performed on a 50,000-record multi-country cancer patient dataset to uncover trends, disparities, and clinically meaningful insights.

# 📁 Project Overview

This project investigates global cancer patient data (2015–2024) to understand how demographics, lifestyle risks, genetics, environmental exposure, and healthcare systems influence cancer severity, treatment cost, and survival outcomes.

# The notebook includes:

- Extensive Exploratory Data Analysis 

- Statistical testing (Kruskal–Wallis, interaction regression)

- Feature importance insights

- Cross-country and demographic comparisons

## 1. Exploratory Data Analysis (EDA) 🔎
### 1.1 Key Trends & Hidden Patterns

- Smoking and genetic predisposition are the top drivers of cancer severity.

- Treatment cost is right-skewed → few patients incur extremely high expenses.

- Severity tends to cluster around moderate values with a small severe tail.

- Air pollution and alcohol use show moderate correlations with severity.

### 1.2 Disparities in Diagnosis, Lifestyle, Treatment & Outcomes

- Cancer type distribution varies widely (lung, breast, colorectal, etc.).

- Developed countries show significantly higher treatment costs.

- Lifestyle risk factors (smoking, alcohol, obesity) vary across populations.

- Survival years differ across individuals but show little variance across cancer stages.

### 1.3 Variations Across Countries, Age Groups & Cancer Stages

- USA, Australia, China → highest treatment burdens.

- India, Pakistan → lower average costs.

- Treatment cost increases sharply with age, especially 61+.

- Cancer stage shows little variation in treatment cost or survival years.

## 2. Inferential & Predictive Analytics
### 2.1 Proportion of Early-Stage Diagnoses by Cancer Type

- Some cancers (e.g., breast, colorectal) show higher early-stage detection.

- Lung cancer shows more mid-late stage detection.

### 2.2 Key Predictors of Severity & Survival Years

**Top predictors of severity:**

- Smoking

- Genetic Risk

- Treatment Cost

- Alcohol Use

- Air Pollution

- Variables with minimal effect: Gender, Obesity, Stage.

**Survival Years:**
No strong predictor identified — relationships were weak.

### 2.3 Economic Burden Across Demographics & Countries

- Developed countries bear higher treatment costs.

- Elderly patients have higher treatment expenses.

- High severity correlates with higher financial burden.

### 2.4 Is Higher Treatment Cost Linked to Longer Survival?

- No meaningful relationship found between treatment cost and survival years.

### 2.5 Do Higher Cancer Stages Increase Cost or Reduce Survival?

 **Kruskal-Wallis results:**

- Treatment Cost: p = 0.4254 → no significant difference

- Survival Years: p = 0.6033 → no significant difference

- Stage does not influence cost or survival statistically.

### 2.6 Does Genetic Risk Amplify Smoking Effects?

**Interaction regression:**

Interaction coefficient: –0.000228

p-value: 0.628

Result :  No interaction effect.
Smoking and genetic risk act independently in this dataset.

## Key Visualizations Included

- Age, gender, and country distributions

- Cancer type and stage distributions

- Smoking, alcohol, obesity, genetic risk visualizations

- Treatment cost & survival year histograms

- Country-wise and stage-wise comparisons

- Risk factor vs severity regression plots

- Correlation heatmap

- Kruskal–Wallis outputs

- Interaction regression summary



## Tech Stack

- Python

- Pandas, NumPy

- Matplotlib, Seaborn

- SciPy (Kruskal-Wallis tests)

- Scikit-learn (Feature importance)

## Key Findings (Summary)

- Smoking and genetic risk are the most influential factors for cancer severity.

- Treatment cost varies significantly between countries — highest in developed regions.

- Cancer stage has no significant impact on treatment cost or survival years.

- Treatment cost does not predict better survival outcomes.

- No interaction effect between smoking and genetic predisposition.

- Environmental exposure moderately increases severity.

- Demographic variables (gender, obesity) have minimal clinical impact.


## Author

Naman Verma
📧 vermanaman419@gmail.com

🌐 Linkedin: https://www.linkedin.com/in/naman419/
