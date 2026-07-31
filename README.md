# 📩 Spam SMS Detection using Machine Learning

## 📌 Overview
This project builds a Machine Learning model to classify SMS messages as **Spam** or **Ham (Legitimate)** using **TF-IDF Vectorization** and the **Multinomial Naive Bayes** algorithm.

The model converts text messages into numerical features using TF-IDF and predicts whether an SMS is spam or legitimate.

---

## 🚀 Features

- SMS Text Classification
- Data Cleaning & Preprocessing
- TF-IDF Feature Extraction
- Train-Test Split
- Multinomial Naive Bayes Classifier
- Model Evaluation
- Confusion Matrix
- Spam Prediction on Custom Messages
- Model Saving using Joblib

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib

---

## 📂 Dataset

SMS Spam Collection Dataset

The dataset contains over **5,500 SMS messages** labeled as Spam or Ham.

---

## 📊 Machine Learning Model

- TF-IDF Vectorizer
- Multinomial Naive Bayes

---

## 📈 Results

- Accuracy: **96.86%**

The trained model successfully classifies spam and legitimate SMS messages with high accuracy.

---

## 📁 Project Structure

```
SPAM_SMS_DETECTION/
│── spam_sms_detection.ipynb
│── spam.csv
│── README.md
│── requirements.txt
│── spam_sms_model.pkl
│── tfidf_vectorizer.pkl
```

---

## ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/krishnapal3007/SPAM_SMS_DETECTION.git
```

### Install Requirements

```bash
pip install -r requirements.txt
```

### Run Notebook

```bash
jupyter notebook spam_sms_detection.ipynb
```

---

## 🧪 Sample Predictions

| Message | Prediction |
|---------|------------|
| Congratulations! You won ₹50,000. Click now! | Spam |
| Hi Krishna, are you coming to college today? | Ham |
| Your OTP is 482913. | Ham |
| Limited time offer! Buy one get one free. | Spam |

---

## 👨‍💻 Author

**Krishna**

GitHub:
https://github.com/krishnapal3007