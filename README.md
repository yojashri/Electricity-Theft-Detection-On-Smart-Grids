````markdown
#  Electricity Theft Detection on Smart Grids

An intelligent machine learning-based web application that detects fraudulent electricity consumption using **Artificial Neural Network (ANN)** and smart meter consumption data. The system helps utility providers reduce revenue loss, improve monitoring, and automate theft detection.

---

##  Project Overview

Electricity theft is a major challenge for power distribution companies and leads to:

- Revenue loss for utility providers  
- Increased electricity cost for honest consumers  
- Unsafe illegal connections  
- Reduced grid efficiency  

This project uses **Artificial Neural Networks (ANN)** to analyze electricity consumption patterns and classify usage as:

- Normal / Faithful Usage  
-  Fraudulent / Unfaithful Usage  

The trained model is deployed using **Flask** with a user-friendly web interface.

---

##  Features

- Detects electricity theft using ANN model  
- Uses smart grid / smart meter consumption data  
- Web-based prediction system using Flask  
- Upload and preview CSV datasets  
- Real-time prediction through UI  
- High prediction accuracy  
- Scalable for smart grid applications  

---

##  Tech Stack

### Programming Language
- Python

### Machine Learning / Deep Learning
- TensorFlow  
- Keras  
- Scikit-learn  

### Data Processing
- NumPy  
- Pandas  

### Web Framework
- Flask  

### Frontend
- HTML  
- CSS  
- Bootstrap  

### Model Files
- `theft.h5` → Trained ANN model  
- `StandardScaler.pk` → Saved preprocessing scaler  

---

##  Project Structure

```bash
Electricity-Theft-Detection-On-Smart-Grids/
│── model/                  # Training notebooks / model files
│── static/                 # CSS / JS / assets
│── templates/              # HTML templates
│── test_data/              # Sample test data
│── app.py                  # Flask application
│── theft.h5                # Trained ANN model
│── StandardScaler.pk       # Saved scaler
│── upload.csv              # Sample input file
│── requirements.txt        # Dependencies
│── README.md               # Documentation
````

---

## How It Works

1. User enters electricity consumption feature values
2. Input data is preprocessed using saved scaler
3. ANN model predicts the result
4. Output displayed as:

* **Faithfull** → Normal Usage
* **Unfaithfull** → Theft Detected

---

##  Input Features Used

* Energy Mean
* Energy Median
* Energy Max
* Energy Min
* Energy Sum
* Energy Count
* Energy Standard Deviation

These statistical features are extracted from smart meter readings.

---

## 🧠 Machine Learning Workflow

```text
Dataset Collection
      ↓
Data Preprocessing
      ↓
Feature Extraction
      ↓
Train ANN Model
      ↓
Save Model (.h5)
      ↓
Deploy using Flask
      ↓
Real-time Prediction
```

---

## Performance

* Training Accuracy: **99%**
* Validation Accuracy: **99%**

Evaluation Metrics:

* Accuracy
* Precision
* Recall
* F1-score

---

##  Installation & Setup

### 1️ Clone Repository

```bash
git clone https://github.com/yojashri/Electricity-Theft-Detection-On-Smart-Grids.git
cd Electricity-Theft-Detection-On-Smart-Grids
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

###  Run Application

```bash
python app.py
```

###  Open Browser

```bash
http://127.0.0.1:5000/
```

---

##  Future Enhancements

* Automatic feature extraction from raw smart meter data
* Real-time smart grid integration
* Advanced models like LSTM / CNN
* Cloud deployment
* Dashboard analytics


