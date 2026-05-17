# Machine Learning, Data Science and AI Portfolio

This portfolio represents a comprehensive collection of predictive modeling, statistical analysis, and exploratory data science projects. Each repository focuses on extracting actionable insights from complex datasets.

---

## 🚀 Featured Unsupervised Learning, Reinforcement and Deep Learning Projects

### 🍎 FreshCheck AI: Hierarchical Computer Vision for Food Waste Reduction
* **Overview**: A two-stage intelligent system designed to combat food waste. FreshCheck first identifies the type of produce and then applies a specialized maturity-detection model to predict freshness levels, providing actionable storage advice and environmental impact metrics.
* **Technical Highlights**: Hierarchical Classification using Transfer Learning (MobileNetV2), Human-in-the-Loop integration for texture validation, and a custom environmental converter that translates food waste into CO2e and water footprint data.
* **Index & Deliverables**:
    * [Live Demo: Streamlit App](https://freshcheck-ripeness.streamlit.app/)
    * [Source Repository](https://github.com/rebeca-bc/FreshCheck)

### 🧬 [Classification Endometrial Cancer Molecular Subtypes](https://rebeca-bc.github.io/UnsupervisedGenes/)
* **Overview**: Transitioning from traditional histological grading to precision medicine by identifying molecular signatures in 566 patients using RNA-seq data. This project discovers three robust clusters with distinct survival outcomes, linking transcriptional heterogeneity to clinical prognosis.
* **Technical Highlights**: PCA-based dimensionality reduction (60,660 genes to 25 PCs), K-Means & Hierarchical Clustering, Kaplan-Meier survival modeling, and biomarker discovery using one-vs-rest t-tests with Benjamini-Hochberg FDR correction.
* **Index & Deliverables**:
    * [Interactive HTML Report](https://rebeca-bc.github.io/UnsupervisedGenes/)
    * [Source Repository](https://github.com/rebeca-bc/UnsupervisedGenes)

### 🚀 [Reinforcement Learning: Q-Learning Cliff Walking](https://rebeca-bc.github.io/RenforcementCliffWalking/)
* **Overview**: A real-time demonstration of an agent mastering a discrete environment. The project tracks the evolution of an AI from "stochastic chaos" to an "optimal speedrun" (14 steps) across a cliffside grid, discovering the "cliff-edge" strategy naturally.
* **Technical Highlights**: Q-Table implementation, epsilon-greedy exploration/exploitation scheduling, reward engineering, and automated GIF generation for temporal learning analysis.
* **Index & Deliverables**:
    * [Interactive HTML Report](https://rebeca-bc.github.io/RenforcementCliffWalking/)
    * [Source Repository](https://github.com/rebeca-bc/RenforcementCliffWalking)

### 🔍 [Unsupervised Tutorial and Demo: Clustering & Recommendation Systems]
* **Overview**: A educational suite and web app designed to bridge the gap between machine learning theory and industry practice. Features a deep dive into K-Means/Hierarchical logic and a practical application of PCA for building high-speed recommendation engines.
* **Technical Highlights**: Feature standardization auditing, Elbow/Silhouette optimization, linkage method comparisons (Ward, Single, Complete), and building "MovieMate"—a live engine utilizing Cosine Similarity on MovieLens data.
* **Index & Deliverables**:
    * [Clustering Types Tutorial](https://rebeca-bc.github.io/ClusteringTypesTutorial/)
    * [PCA & Recommendation Project](https://rebeca-bc.github.io/RecommendationPCATutorial/)
    * [Live App: MovieMate Engine](https://recommendationpcatutorial.onrender.com/)

---

## 🚀 Featured Supervised Learning Projects

### 🏆 Deforestation Risk Classifier (Classification Synthesis)
* **Overview**: The culmination of the classification series, synthesizing insights across linear models, tree-based ensembles, and deep learning to establish the most robust, deployment-ready ecological early-warning system.
* **Technical Highlights**: Comprehensive algorithm benchmarking, rigorous independent test-set validation, and translating mathematical metrics (Recall vs. Precision) into actionable environmental policy recommendations.
* **Index & Deliverables**:
    * [Interactive HTML Report](https://rebeca-bc.github.io/Deforestation-Risk-Classifier/)
    * [Source Repository](https://github.com/rebeca-bc/Deforestation-Risk-Classifier)

### 🤖 Deforestation Multi-Model Classification
* **Overview**: Stress-testing diverse machine learning architectures (Random Forest, XGBoost, SVM, and Neural Networks) to uncover the true underlying geometry of global deforestation threats.
* **Technical Highlights**: Model-specific preprocessing pipelines, stratified cross-validation, Neural Network early stopping (val_loss), and minority-sensitive F1-score evaluation.
* **Index & Deliverables**:
    * [Interactive HTML Report](https://rebeca-bc.github.io/DeforestationClassifier-SVMsEnsembleANNs/)
    * [Source Repository](https://github.com/rebeca-bc/DeforestationClassifier-SVMsEnsembleANNs)

### 🌲 LDA & Decision Trees: Deforestation Risk
* **Overview**: A comparative study of Linear Discriminant Analysis (LDA) and Decision Trees to identify deforestation drivers and test if contrasting mathematical algorithms converge on the same ecological signals.
* **Technical Highlights**: LDA assumption auditing (multicollinearity, KDE plots), Discriminant Scaling Analysis, leakage-free scaling, and Gini Feature Importance extraction.
* **Index & Deliverables**:
    * [Interactive HTML Report](https://rebeca-bc.github.io/DeforestationClassifierLDA-Trees/)
    * [Source Repository](https://github.com/rebeca-bc/DeforestationClassifierLDA-Trees)

### 🎯 Deforestation Logistic: Critical Risk Classification
* **Overview**: A binary classification approach using Logistic Regression to predict critical deforestation risk based on socioeconomic indicators and ecologically validated thresholds.
* **Technical Highlights**: Target variable engineering (literature-validated cutoffs), class imbalance handling (class_weight='balanced'), leakage-free pipelines, and operational decision threshold analysis to maximize crisis detection.
* **Index & Deliverables**:
    * [Interactive HTML Report](https://rebeca-bc.github.io/DeforestationLogisticClassifier/)
    * [Source Repository](https://github.com/rebeca-bc/DeforestationLogisticClassifier)

### 🌳 [Deforestation Data Insights](https://rebeca-bc.github.io/deforestation-data-insights/)
* **Overview**: A predictive analysis of global deforestation drivers and forest cover loss trends.
* **Technical Highlights**: Implemented linear regression models and designed a data-driven approach to environmental monitoring.
* **Index & Deliverables**:
    * [Interactive HTML Report](https://rebeca-bc.github.io/deforestation-data-insights/)
    * [Source Repository](https://github.com/rebeca-bc/deforestation-data-insights)

### ⚖️ [Global Happiness Index Analysis](https://rebeca-bc.github.io/happiness-index-linear-regressions/)
* **Overview**: Investigation of socioeconomic factors (GDP, social support, life expectancy) and their impact on national happiness scores.
* **Technical Highlights**: Multi-variable linear regression and statistical significance testing.
* **Index & Deliverables**:
    * [Interactive HTML Report](https://rebeca-bc.github.io/happiness-index-linear-regressions/)
    * [Source Repository](https://github.com/rebeca-bc/happiness-index-linear-regressions)

### 🍎 [Obesity Trends: Exploratory Data Analysis](https://rebeca-bc.github.io/Obesity-Explorer-EDA/)
* **Overview**: A deep dive into health metrics and lifestyle habits to identify patterns in obesity across different demographics.
* **Technical Highlights**: Advanced data cleaning, feature correlation matrices, and multivariate visualization.
* **Index & Deliverables**: 
    * [Interactive HTML Report](https://rebeca-bc.github.io/Obesity-Explorer-EDA/)
    * [Source Repository](https://github.com/rebeca-bc/Obesity-Explorer-EDA)

### 🎓 [Academic Performance Modeling](https://rebeca-bc.github.io/GradesOLS/)
* **Overview**: Utilizing Ordinary Least Squares (OLS) regression to predict student outcomes based on study habits and external variables.
* **Technical Highlights**: Model validation using R-squared metrics and residual analysis.
* **Index & Deliverables**:
    * [Interactive HTML Report](https://rebeca-bc.github.io/GradesOLS/)
    * [Source Repository](https://github.com/rebeca-bc/GradesOLS)


---

## 📫 Contact & Professional Profiles
* **GitHub**: [rebeca-bc](https://github.com/rebeca-bc)
* **University**: Universidad de Monterrey (UDEM)
* **Linkedin**: www.linkedin.com/in/rebecaborregoc
