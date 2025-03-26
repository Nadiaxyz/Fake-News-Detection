# Fake News Detection

This repository contains a **Fake News Detection** web application built using **Flask**, **Python**, and **Machine Learning**. The project uses a trained model to classify news articles as either **Fake** or **Real**.

---

## 📁 Project Structure

```
fake-news-detection/
│── app.py                # Flask web application
│── fakenews.py           # Jupyter Notebook (Dataset & Model Training)
│── fake_news_model.pkl   # Trained machine learning model
│── templates/            # HTML templates
│   ├── fake.html         # Frontend UI for news input & prediction
│── static/               # (Optional) CSS, JS, images
│── README.md             # Project documentation
```

---

## 🚀 How to Run the Flask App

### **1️⃣ Install Required Dependencies**
Make sure you have **Python 3.x** installed. Then, install Flask and Scikit-Learn:
```sh
pip install flask scikit-learn
```

### **2️⃣ Run the Flask Server**
```sh
python app.py
```
After running the command, you should see:
```
 * Running on http://127.0.0.1:5000/
```

### **3️⃣ Open in Browser**
Go to **http://127.0.0.1:5000/** to access the web app.

---

## 📜 Description of Files

- **`app.py`** → The main Flask application that loads the trained model and serves the web UI.
- **`fake.html`** → Frontend UI where users can input news articles for prediction.
- **`fakenews.py`** → Jupyter Notebook used for data processing, training the model, and saving `fake_news_model.pkl`.
- **`fake_news_model.pkl`** → Pre-trained model for detecting fake news.

---

## 📌 How It Works
1. **User enters a news article** into the web app.
2. The app **vectorizes the text** using the stored model.
3. The machine learning model **predicts** whether the news is **Fake** or **Real**.
4. The result is displayed on the webpage.

---

## 🛠️ Future Improvements
✅ Improve model accuracy with better datasets.  
✅ Enhance frontend with Bootstrap or React.  
✅ Deploy on **Heroku** or **Render**.

---

## 💡 Credits
Developed by [Your Name] as part of an AI project on **Fake News Detection**.

