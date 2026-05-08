# 📧 Email Spam Classification

A Machine Learning based Spam Email Detection system that classifies emails as **Spam** or **Ham** using multiple ML models with an interactive Streamlit web app.

## 🚀 Features
- Spam/Ham prediction
- Multiple ML models (SVM, Logistic Regression, Random Forest)
- Streamlit web interface
- Batch email processing
- Performance metrics & logging

## 🛠️ Tech Stack
- Python
- Scikit-learn
- Streamlit
- Pandas & NumPy

## ⚡ Installation

```bash
git clone <repository_url>
cd Spam-Email-Detection

python -m venv .venv
.venv\Scripts\activate

pip install -r requirements.txt
```

## ▶️ Run Application

```bash
streamlit run app.py
```

## 🧠 Train Model

```bash
python -m src.pipeline.training_pipeline
```

## 📊 Output
- Spam/Ham Prediction
- Confidence Score
- CSV export for batch processing
