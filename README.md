<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,20&height=200&section=header&text=📊%20Data%20Science%20Journey&fontSize=45&fontColor=fff&animation=twinkling&fontAlignY=36&desc=Learning%20Day%20by%20Day%20%7C%20Notebook%20by%20Notebook&descAlignY=57&descSize=17" width="100%"/>

</div>

<div align="center">

[![Author](https://img.shields.io/badge/Author-Birendra%20Chaudhary-informational?style=for-the-badge&logo=github&logoColor=white)](https://github.com/birendrachy7)
[![Language](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Notebooks](https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Status](https://img.shields.io/badge/Status-🔥%20Actively%20Updating-success?style=for-the-badge)](https://github.com/birendrachy7/Data_Science)

</div>

---

## 🌟 What Is This Repository?

This is my **personal Data Science learning journal** — a daily-updated collection of Jupyter Notebooks where I document everything I learn, one topic at a time.

Every day I study a new concept, practice it with real code, and push a new notebook. Think of it as a **live textbook** that grows alongside my learning — beginner-friendly, hands-on, and always up to date.

> 💡 **Tip for learners:** Follow this repo and come back daily — new notebooks are added as I progress through the full Data Science stack!

---
<!--
## 📅 Daily Log — Notebooks Completed

| Day | Notebook | Topics Covered | Status |
|-----|----------|---------------|--------|
| Day 1 | [`Day1_DS_numpy.ipynb`](./Day1_DS_numpy.ipynb) | NumPy — Arrays, Operations, Indexing, Math, Random | ✅ Done |
| Day 2 | `Day2_DS_pandas.ipynb` | Pandas — Series & DataFrames | 🔜 Coming |
| Day 3 | `Day3_DS_pandas_adv.ipynb` | Data Cleaning, Missing Values, Groupby | 🔜 Coming |
| Day 4 | `Day4_DS_matplotlib.ipynb` | Matplotlib — Charts & Plots | 🔜 Coming |
| Day 5 | `Day5_DS_seaborn.ipynb` | Seaborn — Statistical Visualizations | 🔜 Coming |
| Day 6 | `Day6_DS_eda.ipynb` | Exploratory Data Analysis (EDA) | 🔜 Coming |
| Day 7 | `Day7_DS_ml_intro.ipynb` | Intro to Machine Learning Concepts | 🔜 Coming |
| Day 8 | `Day8_DS_sklearn.ipynb` | scikit-learn — Regression & Classification | 🔜 Coming |
| Day 9 | `Day9_DS_eval.ipynb` | Model Evaluation, Accuracy, Confusion Matrix | 🔜 Coming |
| Day 10+ | `Day10_DS_project.ipynb` | Real-world Mini Project — End to End | 🔜 Coming |

> ✅ Done &nbsp;|&nbsp; 🔄 In Progress &nbsp;|&nbsp; 🔜 Coming Soon

---

## ✅ Day 1 — NumPy Deep Dive

> **File:** [`Day1_DS_numpy.ipynb`](./Day1_DS_numpy.ipynb) &nbsp;·&nbsp; 901 lines &nbsp;·&nbsp; 24 KB

NumPy is the foundation of all Data Science in Python — almost every library (Pandas, Matplotlib, scikit-learn) is built on top of it. Day 1 explores it thoroughly.

**What's inside:**

```
📓 Day1_DS_numpy.ipynb
│
├── 🔢 What is NumPy & Why It Matters
├── 📦 Creating Arrays
│   ├── np.array(), np.zeros(), np.ones()
│   ├── np.arange(), np.linspace(), np.eye()
│   └── np.random.rand(), np.random.randint()
│
├── 📐 Array Properties
│   ├── .shape, .ndim, .size, .dtype
│   └── .reshape(), .flatten(), .ravel()
│
├── ✂️ Indexing & Slicing
│   ├── 1D, 2D, 3D array access
│   ├── Boolean indexing
│   └── Fancy indexing
│
├── ➕ Array Operations
│   ├── Arithmetic: +, -, *, /
│   ├── Broadcasting rules
│   └── Universal functions (ufuncs)
│
├── 📊 Statistical Functions
│   ├── np.mean(), np.median(), np.std()
│   ├── np.min(), np.max(), np.sum()
│   └── np.percentile(), np.corrcoef()
│
├── 🔗 Array Manipulation
│   ├── np.concatenate(), np.stack()
│   ├── np.vstack(), np.hstack()
│   └── np.split(), np.sort()
│
└── 🧮 Linear Algebra Basics
    ├── np.dot(), np.matmul()
    └── np.linalg — determinant, inverse, eigenvalues
```

**Quick example from the notebook:**

```python
import numpy as np

# Create a 2D array
arr = np.array([[1, 2, 3],
                [4, 5, 6],
                [7, 8, 9]])

print(arr.shape)        # (3, 3)
print(arr.mean())       # 5.0
print(arr[1, :])        # [4 5 6]  — row slicing
print(arr[:, 2])        # [3 6 9]  — column slicing
print(arr * 2)          # element-wise multiplication
print(np.sqrt(arr))     # ufunc — square root of every element
```

---

## 🗺️ The Full Learning Roadmap

```
┌─────────────────────────────────────────────────────────────────┐
│                   DATA SCIENCE ROADMAP                          │
├─────────────────┬───────────────────────────────────────────────┤
│  📦 FOUNDATION  │  NumPy → Pandas                               │
│   (Days 1–3)    │  Arrays, DataFrames, Data Wrangling           │
├─────────────────┼───────────────────────────────────────────────┤
│  📊 VISUALIZE   │  Matplotlib → Seaborn                         │
│   (Days 4–5)    │  Plots, Charts, Statistical Graphs            │
├─────────────────┼───────────────────────────────────────────────┤
│  🔍 EXPLORE     │  Exploratory Data Analysis                    │
│   (Day 6)       │  Patterns, Correlations, Real Datasets        │
├─────────────────┼───────────────────────────────────────────────┤
│  🤖 MODEL       │  scikit-learn                                 │
│   (Days 7–9)    │  ML Algorithms, Training, Evaluation          │
├─────────────────┼───────────────────────────────────────────────┤
│  🚀 BUILD       │  End-to-End Project                           │
│   (Day 10+)     │  Data → Clean → Analyze → Model → Predict     │
└─────────────────┴───────────────────────────────────────────────┘
```

---
-->
## 🚀 How to Use This Repo

### Option 1 — Run in Google Colab (No Setup Needed ☁️)

Click the badge below to open Day 1 directly in your browser:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/birendrachy7/Data_Science/blob/main/Day1_DS_numpy.ipynb)

### Option 2 — Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/birendrachy7/Data_Science.git
cd Data_Science

# 2. Launch Jupyter
jupyter notebook

# 3. Open any .ipynb file and start learning!
```

---

## 🛠️ Libraries Used in This Journey Till NowDays

<div align="center">

| Library | Purpose |
|---------|---------|
| ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) | Numerical computing, arrays |
| ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) | Data manipulation, DataFrames |
| ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) | Interactive notebooks |

<!--| ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white) | Plotting & visualization | Day 4 |
| ![Seaborn](https://img.shields.io/badge/Seaborn-3A7EBF?style=flat-square&logo=python&logoColor=white) | Statistical visualization | Day 5 |
| ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) | Machine learning models | Day 7 |
-->
</div>

---

## 📚 Useful Resources for Learners

| Resource | What You'll Learn |
|----------|------------------|
| 📘 [NumPy Official Docs](https://numpy.org/doc/) | Complete NumPy reference |
| 🐼 [Pandas Docs](https://pandas.pydata.org/docs/) | DataFrames & data wrangling |
| ☁️ [Google Colab](https://colab.research.google.com/) | Free Jupyter in the cloud |
| 📓 [Jupyter Notebook](https://jupyter.org/) | Open-source interactive notebook environment |
<!--| 📈 [Matplotlib Gallery](https://matplotlib.org/stable/gallery/) | Chart examples with code |
| 🎨 [Seaborn Gallery](https://seaborn.pydata.org/examples/) | Statistical plot examples |
| 🤖 [scikit-learn Docs](https://scikit-learn.org/stable/) | ML algorithms & API |
| 🎓 [Kaggle Learn](https://www.kaggle.com/learn) | Free hands-on DS micro-courses |-->


---


## 👤 Author

**Birendra Chaudhary** — Computer Engineering Student & Aspiring Data Scientist

[![GitHub](https://img.shields.io/badge/GitHub-birendrachy7-181717?style=flat-square&logo=github)](https://github.com/birendrachy7)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-birendra.chy.7-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/birendra.chy.7)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-FF5722?style=flat-square&logo=google-chrome)](http://birendrachaudhary08.com.np)
[![Email](https://img.shields.io/badge/Email-info.birendra008@gmail.com-D14836?style=flat-square&logo=gmail)](mailto:info.birendra008@gmail.com)

---

## ⭐ Support This Journey

If these notebooks help you learn, please **star ⭐ the repo** — it's the best way to keep me motivated to keep pushing daily notebooks!

> 📌 **Watch this repo** to get notified every time a new notebook is added.

---

<div align="center">

*"Data is the new oil. Python is the drill."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,20&height=100&section=footer" width="100%"/>

</div>
