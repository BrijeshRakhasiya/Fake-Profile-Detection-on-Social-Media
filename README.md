# 🕵️‍♂️ Fake Account Detection using Machine Learning

This project focuses on detecting fake accounts using supervised machine learning techniques. By analyzing key features and patterns in user behavior, the model aims to accurately distinguish between genuine and fake accounts — a critical task in preventing cyber fraud, improving platform integrity, and strengthening trust in digital ecosystems.

---

## 📌 Problem Statement

Social media platforms and digital applications often suffer from fake account proliferation, which leads to spam, misinformation, and fraud. This project tackles this issue by building a classification model that learns to differentiate between real and fake accounts using labeled data.

---

## 🛠️ Project Pipeline

1. **Data Preprocessing**  
   - Handling missing values  
   - Feature scaling & encoding  
   - Splitting data into training and testing sets

2. **Model Training**  
   - Supervised classification model (Logistic Regression / Random Forest / etc.)  
   - Cross-validation to prevent overfitting

3. **Model Evaluation**  
   - Confusion Matrix  
   - Precision, Recall, F1-Score, Accuracy  

---

## 📊 Evaluation Metrics

| Metric         | Class 0 (Fake) | Class 1 (Genuine) | Macro Avg | Weighted Avg |
|----------------|----------------|-------------------|-----------|---------------|
| Precision      | 0.86           | 0.93              | 0.89      | 0.89          |
| Recall         | 0.93           | 0.85              | 0.89      | 0.89          |
| F1-score       | 0.90           | 0.89              | 0.89      | 0.89          |
| **Accuracy**   | **-**          | **-**             | **-**     | **0.89**      |
| **Support**    | 60             | 60                | 120       | 120           |

### 🧮 Confusion Matrix

- **True Positives (TP)**: 51  
- **True Negatives (TN)**: 56  
- **False Positives (FP)**: 4  
- **False Negatives (FN)**: 9  

---

## 🧠 Model Insights

- The model achieves a high F1-score (0.89) and balanced precision/recall, suggesting it performs well on both fake and genuine classes.
- The false positive rate is low, minimizing the chances of misclassifying real users as fake.
- Confusion matrix reveals good separation with only a few misclassifications.

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/BrijeshRakhasiya/Fake-Profile-Detection-on-Social-Media.git
cd Fake-Account-Detection

# Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow 

# Run the notebook
jupyter notebook Fake_Account_Detection.ipynb
```
# 🔐 Use Cases
Fraud detection in social networks and banking apps

Spam account filtering on messaging platforms

Bot detection in online communities

# 🙋‍♂️ Author
Brijesh Rakhasiya
AI/ML Enthusiast | Data Scientist | Problem Solver


## 📄 License

This project is licensed under the MIT License.

---
**Made ❤️ by Brijesh Rakhasiya**e.
