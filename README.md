# Molecular Binding Data Challenge 
This repository contains a cleaned and anonymized version of a machine learning and data preprocessing pipeline originally developed for a technical data science exercise. All proprietary data has been removed, and synthetic examples are used for illustrative purposes.

## Background

The original task was based on a synthetic dataset simulating fluorescence intensity data generated from a high-throughput molecular screening platform. The challenge involved:

- Correcting for background fluorescence and noise.
- Identifying statistically significant molecular hits.
- Analyzing the contributions of building blocks (BB1, BB2, BB3) to binding affinity.
- Training a regression model to predict molecular binding intensity using one-hot encoded building block combinations.

Due to confidentiality, no real data is included in this repository. All visualizations and modeling steps were rebuilt using synthetic inputs that mimic the format and complexity of the original data.

---

## Contents

- **`hit_identification_public.ipynb`**  
  A notebook demonstrating the preprocessing and statistical hit identification pipeline using synthetic fluorescence data. Includes:
  - Background correction
  - Hit classification
  - Summary visualizations

- **`ML-onehot_public.ipynb`**  
  A notebook showcasing a regression pipeline using one-hot encoded features (BB1, BB2, BB3) to predict synthetic fluorescence intensity. Includes:
  - Model training (e.g., Ridge, Random Forest, XGBoost)
  - Evaluation and predictions
  - Synthetic top hit ranking

---

## Disclaimer

This repository does not include any proprietary data or sensitive insights. All datasets have been replaced with synthetically generated inputs that preserve the general structure of the original exercise.

These notebooks are for **demonstration purposes only** and reflect the author’s own implementation and reasoning in response to a technical challenge prompt.
