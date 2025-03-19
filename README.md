# 🛡️ Phishing URL Detection using PhiUSIIL Dataset

This repository contains a **Jupyter Notebook** that explores the **PhiUSIIL Phishing URL Dataset**, a large-scale collection of both legitimate and phishing URLs. The dataset consists of:

- **134,850 legitimate URLs**  
- **100,945 phishing URLs**  
- Most of the URLs are **recently gathered** to ensure up-to-date phishing patterns.

## 📊 Dataset Overview

To facilitate phishing detection, we extracted **various features** directly from each URL and its corresponding webpage **source code**. In addition to basic features, we engineered **advanced metrics**, including:

- **CharContinuationRate**  
- **URLTitleMatchScore**  
- **URLCharProb**  
- **TLDLegitimateProb**  

These features help capture **subtle patterns** in URL structures and webpage content, making it easier to distinguish between **legitimate and phishing websites**.

## 🔍 What’s Inside?

The notebook includes the following steps:

✅ **Exploratory Data Analysis (EDA)** – Understand feature distributions and correlations.  
✅ **Feature Engineering** – Selecting, encoding, and scaling features for optimal performance.  
✅ **Model Training & Evaluation** – Applying machine learning models like **LightGBM, XGBoost, Random Forest**, and **Logistic Regression**.  
✅ **Performance Analysis** – Evaluating model accuracy and ensuring robustness with **cross-validation**.  

## 🚀 Results & Key Findings

- **LightGBM (LGBMClassifier) achieved 100% accuracy on the test set.**  
- Given the **balanced dataset**, **accuracy** is a valid metric to evaluate model performance.  
- The results indicate that **machine learning is highly effective in phishing detection**, leveraging extracted URL and webpage-based features.  

## 📌 Next Steps

To further validate the model’s performance, future improvements could include:  

🔹 **More rigorous cross-validation** to ensure generalization across unseen data.  
🔹 **Feature importance analysis** to identify the key phishing indicators.  
🔹 **Testing on external datasets** to assess real-world applicability.  

## 📂 Usage

To run the notebook locally:  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/phishing-url-detection.git
   cd phishing-url-detection
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:  
   ```bash
   jupyter notebook phishing_detection.ipynb
   ```

## 📜 License

This project is released under the **MIT License**. Feel free to use and modify the code.
