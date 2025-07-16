# 🎯 ML TikTok Content Moderation

This project was developed as part of the **Google Advanced Data Analytics Certificate – Course 6 Final Project**.  
It uses machine learning to classify TikTok videos as **claims** or **opinions**, supporting content moderation and helping detect potentially misleading content.


## 📘 Project Overview

With the rapid growth of short-form video platforms like TikTok, distinguishing between personal opinions and misleading claims has become crucial. Manual moderation is limited in scale, so we designed a machine learning solution to automate this task and improve content review efficiency.


## 🔍 Objectives

- Classify TikTok videos based on metadata and transcript data.
- Automate the detection of videos containing claims.
- Improve efficiency and accuracy in the initial stages of content moderation.


## 🧠 Models

Two tree-based models were built and evaluated:

- **Random Forest** (Champion model)
- **XGBoost**

The Random Forest model slightly outperformed XGBoost in detecting the "claim" class with **~99.5% recall** and **no false positives**. It was selected as the final model due to its robustness and reliability.


## 📊 Key Insights

- Engagement metrics such as views, likes, and shares were the most predictive features.
- Profile-related variables like verification status had little influence.
- The model correctly classified **1,918 out of 1,928 claims**, showing strong potential for real-world deployment.


## 🧪 Project Structure

- **Part 1: Ethical Considerations**
  - Evaluate ethical risks and implications of automating content moderation.
  - Discuss whether the objective should be adjusted.

- **Part 2: Feature Engineering**
  - Select, extract, and transform relevant variables to prepare the dataset.

- **Part 3: Modeling**
  - Build and compare models.
  - Evaluate their performance and recommend next steps.


## 📂 Files
- `ml-tiktok-content-moderation.ipynb`: Complete notebook with model training and evaluation.
- `tiktok_dataset.csv`: TikTok dataset used for analysis.
- `Activity-TikTok-6-executive-summary(SA).pdf`: 1-page executive summary with findings.

## 📌 Next Steps

- Validate the model on additional user groups.
- Monitor changes in video engagement patterns to maintain performance.
- Extend the model with text-based features (e.g., sentiment, source verification).
- Conduct regular bias and fairness audits.


## 👩‍💻 Author

**Suzana Alípio**  
Data Analyst | Cosmoscenery Analytics  


## 🏷️ Tags

`machine-learning` · `random-forest` · `xgboost` · `tiktok` · `binary-classification` · `content-moderation` · `ethics` · `google-data-analytics`
