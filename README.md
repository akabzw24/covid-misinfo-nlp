# Detecting COVID-19 Health Misinformation Targeting Older Adults
Detecting COVID-19 health misinformation targeting older adults using TF-IDF, logistic regression, and BERT

## Author 
**Bozhao Wang** & **Zirui Chen**, University of Calgary

---

## Overview

Canada’s population aged 85 and older reached **861 000** in 2021 which is a 12 % increase since 2016. Now accounting for 2.3 % of all Canadians. Many of these seniors rely on social media for health advice but lack easy access to verified expertise, leaving them vulnerable to misleading COVID-19 claims. This project develops and compares two automated NLP classifiers:

- **TF–IDF + Logistic Regression**  
- **Fine‐tuned BERT**

Both models excel on a labeled Twitter dataset but suffer dramatic performance drops on senior‐focused Reddit posts. We also employ SHAP for interpretability and LDA topic modeling to uncover key misinformation themes.

---


## Data

1. **Raw tweets**  
   Constraint COVID-19 Fake News dataset (6 420 tweets)  

2. **Cleaned & split tweets**  
   Place preprocessed CSV in `data/constraint_train_clean.csv`

3. **Senior‐focused Reddit**  
   Collected via PRAW from r/AskDocs & r/seniors  
   High-confidence pseudo-labels (≥ 90 %) saved as `data/reddit_pseudo_labels.csv`

---

## License ##
MIT © 2025 Bozhao Wang & Zirui Chen


