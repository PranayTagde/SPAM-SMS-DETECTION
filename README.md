# 📩 SMS Spam Detection

This project performs SMS spam classification using Natural Language Processing (NLP) and Machine Learning. It uses the SMS Spam Collection Dataset to train a model that can distinguish between spam and ham messages.

---

## 📁 Dataset

- The dataset contains SMS messages labeled as either "spam" or "ham" (not spam).
- Loaded from a CSV file with text preprocessing applied.

---

## 🧰 Features

- Text cleaning and preprocessing (lowercasing, tokenizing, stopword removal)
- Feature extraction using TF-IDF
- Data visualization (class distribution, word frequency)
- Model training using Multinomial Naive Bayes
- Evaluation using accuracy, precision, recall, and F1-score

---

## 🧪 Machine Learning Model Used

- **Multinomial Naive Bayes** (best suited for text classification)

---

## 🚀 How to Run

### Clone the repository

```bash
git clone https://github.com/PranayTagde/SPAM-SMS-DETECTION.git
cd your-repo-name
```

1. Install the required dependencies:

```bash
pip install -r requirements.txt
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook SMS Spam Collection Dataset.ipynb
```
3. Execute each cell step-by-step to perform preprocessing, training, and evaluation.

## 📦 Requirements

All dependencies are listed in the `requirements.txt` file. Key libraries include:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `nltk`

📊 Sample Output

## ✅ Accuracy and Classification Report

Accuracy & classification report showing performance of the spam detector

```bash
Accuracy: 0.98  
Precision: 0.97  
Recall: 0.96  
F1-score: 0.96
```

## 📁 Project Structure

```bash
📂 SMS Spam Detection
.
├── SMS Spam Collection Dataset.ipynb
├── requirements.txt
└── README.md

```
