# RATING RED VINHO VERDE – A Data-Driven Guide for Restaurant Managers
This project analyzes the chemical properties of Portuguese red Vinho Verde wines and their impact on perceived wine quality. Using a combination of statistical and machine learning techniques, the goal was to identify key predictors of wine quality and build models that allow restaurant managers to select high-quality wines without relying solely on sensory tests.

The analysis focuses on 1,599 wine samples and evaluates models that can predict Low, Medium, and High quality classes based on chemical composition, providing actionable insights for business decisions.

---

## 📊 Dataset
The dataset contains **1,599 observations** with the following variables:  
**Physicochemical data**  
- `Fixed acidity`  
- `Volatile acidity`  
- `Citric acid`  
- `Residual sugar`  
- `Chlorides`  
- `Free sulfur dioxide`  
- `Total sulfur dioxide`  
- `Density`  
- `pH`  
- `Sulphates`  
- `Alcohol`  
**Sensory data output**  
- `Quality`  

---

## 🔎 Key Highlights
**Significant Chemical Properties:**
- Sulphates & Alcohol → Strong predictors of higher wine quality
- Chlorides & pH → Important in distinguishing medium and high-quality wines
- Volatile Acidity → Helps differentiate medium-quality wines

**Model Performance:**
- Multinomial Logistic Regression → Most accurate for classifying Low, Medium, High quality
- Polynomial Regression → Predicted continuous numeric quality with high accuracy but struggled at extreme values
- Segmented & Logistic Models → Useful for understanding class-specific chemical thresholds

**Business Impact:**
- Provides restaurant managers with actionable, data-driven guidance for wine selection
- Reduces reliance on costly sensory evaluations
- Offers clear benchmarks for supplier negotiation and quality control

---

## 🧪 Methodology
**1. Data Cleaning & Preprocessing:** Outlier removal, normalization, and feature selection  

**2. Exploratory Analysis:** Correlation matrices, chemical property distributions, and class-specific insights  

**3. Modeling Approaches:**
- Polynomial Regression for numeric quality prediction
- Segmented Regression to capture class-specific chemical effects
- Logistic Regression & OvR for binary classification
- Multinomial Logistic Regression for simultaneous three-class classification

**4. Evaluation & Insights:** Accuracy metrics, confusion matrices, Chi-Square tests  

**5. Actionable Recommendations:** Translating results into clear guidelines for restaurant managers

---

## 📌 conclusions
- Multinomial Logistic Regression proved most effective in classifying wines into quality categories  
- Chemical composition, especially alcohol, sulphates, and pH, strongly drives perceived quality  
- Managers can leverage these models to select high-quality wines, ensure customer satisfaction, and optimize costs without depending on subjective tasting

---
