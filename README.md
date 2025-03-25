# 📝 Sentiment Analysis Web App

A Flask-based web application that analyzes text sentiment using **Naïve Bayes** and **Support Vector Machine (SVM)** models. It features a **dynamic pH-like sentiment scale** to visualize the positivity, neutrality, or negativity of the input text.

---

## 🚀 Features
- 📊 **Sentiment Analysis** using Naïve Bayes & SVM
- 🎨 **Dynamic Sentiment Scale** (Negative → Mixed → Neutral → Positive)
- ⚡ **Fast Processing** with real-time predictions
- 🔧 **Pre-trained Models** for accurate results

---

## 📂 Project Structure
```
💃 SENTIMENTAL_ANALYSIS
│── 📃 models
│   ├── nb_model.pkl
│   ├── svm_model.pkl
│   └── vectorizer.pkl
│── 📃 static
│   └── style.css
│── 📃 templates
│   └── index.html
│── app.py
│── README.md
│── LICENSE
```

---

## 🛠️ Setup Instructions

### 1⃣ Clone the Repository
```bash
git clone https://github.com/YOUR-USERNAME/sentiment-analysis.git
cd sentiment-analysis
```

### 2⃣ Create & Activate Virtual Environment
```bash
python -m venv venv
# Activate (Windows)
venv\Scripts\activate
# Activate (Mac/Linux)
source venv/bin/activate
```

### 3⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4⃣ Run the Application
```bash
python app.py
```
Access it at: **`http://127.0.0.1:5000/`**

---

## 🗄 Demo
![Sentiment Scale Example](https://your-image-link.com/demo.png)  
*Example of the sentiment scale transitioning from red (negative) to green (positive).*

---

## 💜 License
This project is licensed under the **MIT License** – see the [`LICENSE`](LICENSE) file for details.

---

## ⭐ Contributing
Feel free to fork and improve the project! PRs are welcome. 😊

---

## 👨‍💻 Author
- **Your Name** – [GitHub Profile](https://github.com/theadhithyankr)

