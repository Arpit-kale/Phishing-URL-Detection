# 🔐 Phishing URL Detection System

A Machine Learning–based web application that detects whether a given URL is **safe or phishing** using feature extraction and a trained classification model.
The system provides a simple web interface where users can paste a URL and instantly get a prediction.

---

## 📌 Project Overview

Phishing attacks are one of the most common cybersecurity threats.
This project aims to automatically identify malicious URLs using:

* URL feature extraction
* Machine Learning classification
* Flask web deployment
* Real dataset training

The model analyzes structural, domain-based, and HTML features of a URL to determine whether it is **safe or unsafe**.

---

## 🚀 Features

✔ Detects phishing URLs in real time
✔ Extracts 30 security-related URL features
✔ Uses trained ML model for prediction
✔ Simple web interface using Flask
✔ Dataset included for retraining
✔ Jupyter notebook included for model building

---

## 🧠 Machine Learning Workflow

1. Dataset collection (`phishing.csv`)
2. Feature extraction from URLs
3. Model training (CatBoost / ML classifier)
4. Model saved as pickle file
5. Flask app loads model
6. User enters URL → features extracted → prediction shown

---

## 🏗️ Tech Stack

**Frontend**

* HTML
* CSS

**Backend**

* Python
* Flask

**Machine Learning**

* Scikit-learn
* CatBoost
* Pandas
* NumPy

**Other Libraries**

* BeautifulSoup
* Requests
* Whois
* Dateutil

---

## 📂 Project Structure

```
PROJECT_URL_DETECTION/
│
├── app.py                  # Flask application
├── feature.py              # URL feature extraction logic
├── phishing.csv            # Dataset used for training
├── Phishing_URL_Detection.ipynb  # Model training notebook
│
├── pickle/
│   └── model.pkl           # Saved trained model
│
├── templates/
│   ├── home.html
│   └── index.html
│
├── static/
│   ├── styles.css
│   ├── my.css
│   └── img 1.jpg
│
├── catboost_info/          # Training logs
├── requirement.txt         # Dependencies
└── output.png              # Result screenshot
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/phishing-url-detection.git
cd phishing-url-detection
```

### 2️⃣ Create Virtual Environment (Recommended)

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\\Scripts\\activate
```

**Linux/Mac**

```bash
source venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirement.txt
```

---

### 4️⃣ Run the Application

```bash
python app.py
```

---

### 5️⃣ Open in Browser

```
http://127.0.0.1:5000
```

Enter a URL and check whether it is safe.

---

## 📊 Dataset

The dataset used:

```
phishing.csv
```

It contains labeled URLs with extracted features used for training the model.

---

## 🧪 Model Training

To retrain the model:

1. Open the notebook:

```
Phishing_URL_Detection.ipynb
```

2. Run all cells
3. Save trained model as:

```
pickle/model.pkl
```

---

## 📸 Output Example

The system shows:

* URL entered
* Safety probability
* Prediction result

---

## 🔮 Future Improvements

* Add deep learning–based detection
* Deploy on cloud (Render / AWS / Heroku)
* Add browser extension integration
* Add API endpoint for external apps
* Improve UI with modern dashboard
* Add blacklist + real-time threat intelligence

---

## 👨‍💻 Author

**Arpit Kale**
