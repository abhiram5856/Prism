# Prism

Got it — you want to formally begin from **STEP-0**.
Good move — Step-0 sets up **project intent, outcomes, scope, dataset plan, and environment** before touching any data.

Let’s do it.

---

# 🏁 **STEP-0 — PROJECT FOUNDATION (PRISM)**

---

# 🎯 **0.1 — Project Intent**

**Project Name:** `PRISM`

**Goal:**
Build a **Customer 360° Behavioral Intelligence Platform** using hybrid (real+synthetic) e-commerce data.

**Why:**
Companies like Amazon, Flipkart, Swiggy, Nykaa hire people who can:

* understand customers deeply
* extract behavioral insights
* build lifecycle + cohort models
* compute pricing & profitability economics
* prepare data for ML (churn/CLV) later

PRISM Phase-1 gives you that skillset **without ML yet**.

---

# 🧱 **0.2 — Phase-1 Scope (Analytics Only)**

In **Phase-1**, we will complete:

1. **Data Integration**
2. **Cleaning & Standardization**
3. **Feature Engineering**

   * behavioral features
   * lifecycle features
   * economic features
4. **Pricing & Discount Intelligence**
5. **Return Behavior & Profitability**
6. **Cohort & Retention Analysis**
7. **Survival Analysis (Churn Signals)**
8. **Visual EDA & Insights**
9. **GitHub Project Packaging**

**No ML in Phase-1**.

---

# 🧩 **0.3 — Phase-2 Preview (Future)**

(Not doing now, just planning)

Phase-2 adds ML models:

* Churn classification
* CLV regression
* Segmentation (KMeans)
* Recommendation system
* Deployment/Dashboard

This is why Phase-1 is designed to produce **ML-ready features**.

---

# 📦 **0.4 — Dataset Strategy**

We selected **Hybrid (Option A)**:

✔ Base = **Brazilian E-Commerce Public Dataset** (Real)
✔ Augment with **Indian market synthetic signals**

Breakdown:

| Layer             | Source    |
| ----------------- | --------- |
| Core Transactions | Real      |
| Customer Profiles | Real      |
| Payments          | Real      |
| Deliveries        | Real      |
| Reviews           | Real      |
| Discount Patterns | Synthetic |
| Session Behavior  | Synthetic |
| Returns/Reasons   | Synthetic |
| Demographics      | Synthetic |
| Profit Economics  | Synthetic |

Best of both worlds.

---

# 🇮🇳 **0.5 — Indian Context Augmentation Plan**

We will transform into Indian marketplace context:

✔ Map to Indian States/Cities
✔ Convert prices to **INR**
✔ Add **UPI / COD / Wallet** payments
✔ Add Festive seasons (Diwali, Big Billion Day)
✔ Add Demographics (age, gender, income)
✔ Add Sessions (page views, add to cart, search)
✔ Add Discount Behavior
✔ Add Return Reasons
✔ Add Logistics Costs
✔ Add Churn Signals (recency, dormancy)

Result dataset feels like “Flipkart/Amazon India”.

---

# 🏗️ **0.6 — Knowledge Outcomes You Gain**

By the end of Phase-1 you will know:

### **Technical**

✔ Pandas EDA
✔ Groupby aggregations
✔ Multi-table joins
✔ Cohort analysis
✔ Survival analysis
✔ Price elasticity
✔ Profitability modeling
✔ Feature engineering

### **Business**

✔ Customer lifecycle
✔ Purchase psychology
✔ Discount sensitivity
✔ Return behavior
✔ Profitability vs revenue
✔ Acquisition channels
✔ Retention metrics
✔ Customer segmentation logic

### **Portfolio**

✔ Enterprise folder structure
✔ Good README
✔ GitHub hygiene
✔ Charts & insights
✔ Reproducible notebooks

All **interview-friendly**.

---

# 🧰 **0.7 — Tooling & Environment**

### **Required Tools**

* Python 3.x
* Jupyter Notebook
* VS Code (later for Phase-2)

### **Required Libraries**

```
pandas
numpy
matplotlib
seaborn
plotly
lifelines
faker
tqdm
```

### **Data Source**

Dataset URL:
[https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

# 📂 **0.8 — Project Folder Structure**

Create:

```
prism/
├── data/
│   ├── raw/
│   ├── augmented/
│   ├── processed/
├── notebooks/
│   ├── 01_ingestion.ipynb
│   ├── 02_cleaning.ipynb
│   ├── 03_feature_engineering.ipynb
│   ├── 04_behavioral_analysis.ipynb
│   ├── 05_lifecycle_analysis.ipynb
│   ├── 06_economic_analysis.ipynb
│   ├── 07_pricing_discount.ipynb
├── outputs/
│   ├── charts/
│   ├── reports/
├── src/
│   ├── utils.py
├── requirements.txt
└── README.md
```

This structure is **professional + ML-ready**.

---

# 🧾 **0.9 — Deliverables After Phase-1**

You will have:

✔ Complete hybrid dataset
✔ Clean integrated master table
✔ Behavioral feature table
✔ Cohort retention heatmap
✔ Survival curve (Kaplan-Meier)
✔ Price elasticity plots
✔ Discount sensitivity curve
✔ Profitability metrics
✔ Lifecycle segmentation logic
✔ GitHub-ready notebooks
✔ Insights summary
✔ Indian context interpretation

This is enough to **get shortlisted for Analytics roles** and prepare for ML in Phase-2.

---

# 🚀 **0.10 — Checkpoint Before Moving On**

Now confirm:

1. **Dataset Plan:** Hybrid (✔)
2. **Environment:** Python + Jupyter (✔)
3. **Hardware:** 14th gen + 4060 GPU (✔)
4. **Goal:** Phase-1 only for now (✔)
5. **Role Path:** Analytics → ML (✔)

Now we ask **only one final question** before ingestion:

### **Q0 — Do you want me to generate a full PDF Project Charter for Prism (Phase-1)?**

It includes:
✔ project summary
✔ scope
✔ dataset strategy
✔ timeline
✔ deliverables
✔ future ML plan

Reply with:

> **Yes** (generate PDF)
> or
> **No** (skip to Step-1 ingestion)

Your move.
