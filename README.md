# Machine Learning (Group 36)

# Claim Injury Type Prediction for NY Workers' Compensation Board

This project focuses on building a multiclass classification model to predict the **Claim Injury Type** within the New York Workers' Compensation Board (WCB) system. The goal is to automate and improve the consistency of claim evaluations, thereby enhancing efficiency and reducing processing time.

## Overview

Millions of compensation claims are filed and evaluated by the WCB. While reforms have improved processes, the growing volume and complexity of cases continue to pose challenges. By applying machine learning, this project aims to support faster and more consistent decision-making.

## Key Features

- Built using **XGBoost**, selected after benchmarking multiple algorithms.
- Achieved a **macro F1-score of 0.514** on a highly imbalanced dataset (~80% accuracy).
- Designed with simple preprocessing; missing values and feature selection were intentionally minimal for optimal results.
- Deployed as a lightweight **web application** for interactive use.

## Tech Stack

- Python (Pandas, NumPy, Scikit-learn, XGBoost)
- Django (for the web interface)
- Matplotlib & Seaborn (for visualization)

## Limitations

- Model tends to overpredict the most represented class.
- Some missing values left unprocessed based on validation performance.
- Macro F1-score affected by class imbalance.

## Future Work

- Explore advanced resampling techniques to address imbalance.
- Incorporate more domain-specific features to improve model accuracy.
- Monitor prediction performance on real usage via the deployed app.

## Open-Ended Section
- Django website that integrates the model to give predictions after form submission
👉 **[Open-Ended Section Repository]([https://github.com/your-username/open-ended-section](https://github.com/isabella-fc/to-grant-or-not-to-grant))**

---

