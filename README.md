# 📧 Spam Email Classifier


A simple **Machine Learning** project to detect **spam messages** using Natural Language Processing (NLP) and a Naive Bayes classifier. 🚀

---
## 📌 **Overview**

This project uses the classic **SMS Spam Collection Dataset** to train a model that classifies text messages as **spam** or **ham** (not spam).

---
## ✅ **Key Features**

- Uses **CountVectorizer** and **n-grams** to convert text into numeric features.
- Implements **Naive Bayes (MultinomialNB)** for classification.
- Achieves **~97% accuracy** on the test set.
- Shows how to preprocess, vectorize, train, and test a simple spam detection model.
- Runs fully in **Google Colab** or any Python environment.
  
---
## 📂 **Dataset**

- **Dataset:** [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)  
- **Format:** CSV file (`spam.csv`) with two columns:
  - `label` → `ham` or `spam`
  - `message` → text of the message
---
## ⚙️ **How It Works**

1️⃣ **Load the dataset**  
2️⃣ **Clean and preprocess the data**  
3️⃣ **Convert text to numeric vectors** using `CountVectorizer` with bigrams  
4️⃣ **Train** a **Multinomial Naive Bayes** classifier  
5️⃣ **Predict** whether new messages are spam or not

---
## ✅ **Example Output**
Accuracy: ~97%

## Classification Report:

  - macro avg 0.96 0.95 0.96 1115
  - weighted avg 0.97 0.97 0.97 1115


Test Message: "Congratulations! You've won a free ticket! Call now."

Prediction: SPAM 🚫

---
## 📥 **How to Run**

1️⃣ Clone this repo or upload the notebook to Colab.  
2️⃣ Download the dataset (`spam.csv`) from Kaggle or use the included link.  
3️⃣ Run the notebook step-by-step  
Test the model with your own messages!

---
## 📜 License

This project is open-source under the MIT License — feel free to use, share, and improve it!

---

## ✨ Author

Dhanushya M
🔗 GitHub

---

## ⭐️ Show Some Love

If you found this helpful, please ⭐️ star this repo and share it with your friends! 😊

---

##💡 Future Improvements
          > Add more training data for better real-world performance.
          > Use advanced NLP models (e.g., LSTM, BERT).
          > Deploy as an API or web app.
Happy Learning! 🚀✨

---

## ✅ **Just copy this into `README.md`**  

  - Put it in your GitHub repo → it’ll look clear and polished!  
  - If you want, I can also generate a simple **`.gitignore`** for Python + Colab. 
  - Just say **“yes, gitignore too!”** — and I’ll make it ready. 🚀✨




