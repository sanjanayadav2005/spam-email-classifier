# Spam Email Classifier 📩

This project is a machine learning model that classifies SMS messages as **Spam** or **Not Spam** using the SMS Spam Collection dataset.

## 💡 Technologies Used
- Python
- Scikit-learn
- Pandas, Matplotlib, Seaborn
- Naive Bayes Classifier
- TF-IDF Vectorization

## 📊 Dataset
The dataset contains SMS messages labeled as "ham" (not spam) or "spam".

- Dataset source: [UCI SMS Spam Collection](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)

## 🚀 How It Works
1. Load and clean the dataset
2. Convert text to numerical data using TF-IDF
3. Train a Naive Bayes model
4. Evaluate the model with accuracy, confusion matrix, and sample predictions

## ✅ Sample Output
- Accuracy: ~95%
- Sample message: _"Free entry in 2 a wkly comp to win FA Cup final tkts"_  
  → Prediction: **Spam**

## 📁 Files Included
- `spam_email_classifier.ipynb`: Main notebook with code and output

## ✍️ Author
Project by Jupalli Sanjana during the Summer Internship at CodEc Technologies.
