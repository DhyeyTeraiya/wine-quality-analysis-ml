# 🍷 Wine Quality Analysis — Python Data Science Project

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/ML-Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Domain-Food%20&%20Beverage%20Analytics-red?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge"/>
</p>

---

## 📌 Project Overview

This project uses **Python and Machine Learning** to analyze and predict the quality of red wine based on its physicochemical properties. By exploring relationships between variables like acidity, pH, sulphates, and alcohol content, this project builds a predictive model that classifies wine quality — turning sensory evaluation into data-driven science.

> 🎯 **Goal**: Predict wine quality scores (0–10) using physicochemical test data, and identify which chemical properties most influence wine quality.

---

## 📁 Project Structure

```
wine-quality-analysis/
├── 🐍 vine projcet.py          # Main analysis and ML script
├── 📊 winequality-red.csv      # Red wine dataset (1,599 samples)
└── 📄 README.md                # Project documentation
```

---

## 📊 Dataset Information

| Feature | Description |
|---------|-------------|
| **fixed acidity** | Non-volatile acids (tartaric acid) |
| **volatile acidity** | Acetic acid — too much = vinegar taste |
| **citric acid** | Adds freshness and flavor |
| **residual sugar** | Sugar remaining after fermentation |
| **chlorides** | Salt content |
| **free sulfur dioxide** | Free SO₂ — prevents microbial growth |
| **total sulfur dioxide** | Bound + free SO₂ |
| **density** | Depends on alcohol/sugar content |
| **pH** | Acidity level (0=acidic, 14=basic) |
| **sulphates** | Antimicrobial additive |
| **alcohol** | % alcohol by volume |
| **quality** | 🎯 Target: Score from 0 to 10 |

- **Source**: [UCI Machine Learning Repository — Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality)
- **Records**: 1,599 red wine samples
- **Features**: 11 physicochemical properties + 1 quality score

---

## 🧪 Analysis Performed

### 1️⃣ Exploratory Data Analysis (EDA)
- Distribution plots for all features
- Correlation heatmap between variables
- Outlier detection and handling
- Quality score distribution analysis

### 2️⃣ Feature Engineering
- Quality binarization (Good: ≥7, Poor: <7)
- Feature importance ranking
- Correlation-based feature selection

### 3️⃣ Machine Learning Models
| Model | Accuracy |
|-------|----------|
| Logistic Regression | ~75% |
| Random Forest Classifier | ~87% |
| Decision Tree | ~79% |
| Support Vector Machine | ~77% |

### 4️⃣ Key Visualizations
- Correlation heatmap
- Feature importance bar chart
- Quality distribution histogram
- Confusion matrix
- ROC Curve

---

## 🔍 Key Findings

| Finding | Detail |
|---------|--------|
| 🍷 **Best Predictor** | Alcohol content has the highest correlation with quality |
| 📉 **Quality Driver** | High sulphates → Better quality wine |
| ⚗️ **Negative Indicator** | High volatile acidity consistently lowers quality scores |
| 📊 **Imbalanced Data** | Most wines score 5–6; very few score 3 or 9 |
| 🤖 **Best Model** | Random Forest outperforms all other algorithms |

---

## 🚀 How to Run

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run Analysis
```bash
python "vine projcet.py"
```

---

## 📦 Dependencies

```
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.0
seaborn>=0.11.0
scikit-learn>=0.24.0
```

---

## 💼 Applications

- 🍾 **Wine Production**: Quality control during manufacturing
- 🏷️ **Pricing Strategy**: Premium pricing based on quality prediction
- 🔬 **R&D**: Optimize chemical formulations for better quality
- 🤖 **Automation**: Replace manual tasting with data-driven scoring

---

## 👤 Author

**Dhyey Teraiya** — Batch 8, Data Analytics Student

- 🐙 GitHub: [@DhyeyTeraiya](https://github.com/DhyeyTeraiya)
- 💼 LinkedIn: [Dhyey Teraiya](https://linkedin.com/in/dhyey-teraiya)

---

## 📄 License

This project is licensed under the **MIT License**.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

⭐ **Star this repo if you found it helpful!** ⭐

> *"Wine is data, and data is wine — the more you understand it, the better it gets."*
