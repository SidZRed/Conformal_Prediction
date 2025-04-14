# Conformal_Prediction

Repository for project on **Conformal Prediction**

Conformal Prediction is a powerful statistical framework for uncertainty quantification in machine learning. It produces *prediction sets* instead of point estimates, offering formal guarantees on coverage with minimal assumptions. These guarantees hold regardless of the underlying model's accuracy or the data distribution, making the approach model-agnostic and distribution-free—even in finite-sample settings.

This repository contains experiments and implementations aimed at evaluating and extending conformal prediction methods in both classification and regression contexts. We investigate different score functions, model backbones, and calibration strategies. Special emphasis is given to RAPS (Risk Adaptive Prediction Sets), adaptive set formation, and empirical analysis of marginal coverage under varying calibration set sizes.

---

## 📁 Repository Structure

```
Conformal_Prediction/
├── Images/                            # Visualizations and prediction set illustrations
├── Reports and Papers/                # Project reports and paper drafts
├── all_notebooks/                     # External reference notebooks (e.g., Angelopoulos)
├── .gitignore                         # Ignore dataset, environment files, etc.
├── Compare Two Models.ipynb           # Compare prediction sets from two models
├── Compare_Model_RAPS_IN_V2.ipynb     # Exp4: Compare model (IN_V2) in RAPS setting
├── Compare_Model_RAPS_IN_VAL.ipynb    # Compare RAPS outputs with different models
├── DEPRECATED_Classification_conformal.ipynb  # Early classification implementation (archived)
├── Image_Classifier_RAPS.ipynb        # Core RAPS implementation
├── RESNET101_INVAL_RAPS.ipynb         # RAPS on ResNet101 with INVAL data
├── Regression_conformal.ipynb         # Conformal prediction for regression tasks
├── Resnet152_inval_RAPS.ipynb         # Exp2 & 3: RAPS with ResNet152
├── VGG16_RAPS.ipynb                   # VGG16 model with RAPS
├── adaptive_raps.ipynb                # Adaptive set formation experiments
├── calibration_sets.ipynb             # Analysis of calibration set size and variance
├── score_function.ipynb               # Final implementation of score functions
├── README.md                          # Project README
```

---

## 🧪 Key Features and Experiments

-  **Model-Agnostic Conformal Prediction** on classification and regression datasets  
-  **Multiple Score Functions**: softmax confidence, entropy, negative log-likelihood, etc.  
-  **Backbones**: ResNet101, ResNet152, VGG16, and others tested on ImageNet variants  
-  **RAPS Implementation**: Risk Adaptive Prediction Sets with adaptive size control  
-  **Coverage Analysis**: Empirical study on marginal coverage across varying calibration set sizes  
-  **Regression and Classification Notebooks** with visualization and logging

---

## 📄 Reports and Papers

All formal analysis, plots, and explanations are located in the `Reports and Papers/` folder. This includes figures, abstract, theoretical explanations, and comparisons with previous work.

---


## Project owners :

- Siddharth Reddy
- Adithya K Anil
- Nikhil Jamuda
- P Dhruv Shivkant
