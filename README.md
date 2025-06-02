# XAI Tutorials for Data Science Africa 2025

**Demystifying the Black Box: Hands-on Explainable AI for Health, Finance, and Agriculture**

This repository contains a suite of interactive notebooks, slides, and supporting materials used in the XAI (Explainable AI) tutorial session facilitated by Dr. Sakinat Folorunso at Data Science Africa 2025.


👩🏾‍💻 **Facilitator**:  
**Dr. Sakinat Oluwabukonla Folorunso**  
Senior Faculty, Research Area: AI Systems and FAIR Data Science
Olabisi Onabanjo University, Ago-Iwoye, Ogun State, Nigeria  
[Google Scholar](https://scholar.google.com/citations?user=ysoR2G0AAAAJ&hl=en) | [GitHub](https://github.com/Sakinat-Folorunso) | [Website](https://sites.google.com/view/sakinatfolorunso/home) | [TRAIL](https://sites.google.com/view/ai-trail-oou/home)

🔍 About Me:
I am a researcher, educator, and AI community leader passionate about leveraging Artificial Intelligence, Machine Learning, and FAIR Data Science for health, culture, equity, and innovation in Africa. My work includes developing explainable AI systems for diagnostics, promoting AI literacy, and preserving indigenous knowledge using data science. 

# 🧠 Explainable AI (XAI) Tutorial with SHAP & LIME

Welcome to the **XAI Tutorial Notebook** repository — a practical, hands-on guide for beginners and intermediate machine learning engineers to learn how to interpret model predictions using explainability techniques like **SHAP** and **LIME**.

## 🚀 About This Tutorial

This tutorial introduces:
- Feature-based explanation techniques for tabular classification tasks
- Hands-on implementation of **SHAP (SHapley Additive exPlanations)**
- Step-by-step demonstration of **LIME (Local Interpretable Model-agnostic Explanations)**
- Visual comparison between SHAP and LIME on the same example
- Real-world classification scenario (breast cancer diagnosis)

📘 The included notebook (`XAI_Tutorial_Notebook_1.ipynb`) walks through:
- Dataset preprocessing
- Training an ML model (XGBoost & RandomForest)
- Applying SHAP & LIME explainers
- Visualizing the output
- Saving and comparing explanations

## 📈 Required Libraries

To run this tutorial, install the following libraries:

```bash
pip install shap lime xgboost lightgbm imbalanced-learn matplotlib pandas scikit-learn
````

If you're running in **Google Colab**, simply execute the following in a cell:

```python
!pip install shap lime xgboost lightgbm imbalanced-learn
```

## 📊 Sample Dataset

This tutorial uses a **breast cancer classification dataset**, available as `data.csv`. It includes numeric features extracted from digitized histopathological images and a binary target variable:

* `B` = Benign
* `M` = Malignant

## 💡 Learning Objectives

* Understand the need for model interpretability in real-world applications
* Apply LIME for local, human-interpretable explanations
* Use SHAP for global and local feature importance analysis
* Compare how both methods interpret the same instance

## 👨‍🏫 Intended Audience

* Students learning AI/ML explainability
* Early-career data scientists and ML engineers
* Educators and facilitators teaching XAI concepts

## 🧪 Try It Now!

👉 Open the notebook in Google Colab in the drive:

https://drive.google.com/drive/folders/1MwhZmN-jYJSMwMHcdCdrBEcW0yrYfjOt?usp=drive_link
> Upload the `XAI_Tutorial_Notebook_1_ColabReady.ipynb` manually if not hosted

## 📜 License

This project is licensed under the MIT License.
TRAIL Initiative | Zindi University Ambassador  
