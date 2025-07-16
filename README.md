# 🧠 Diabetes Prediction using Machine Learning

This project predicts the likelihood of diabetes in patients based on clinical health data. It combines a complete machine learning pipeline with an interactive user interface built using Streamlit — all developed inside a Google Colab notebook.

---

## 📌 Features

- Data preprocessing and imputation  
- Feature selection using statistical tests  
- Model training using supervised learning algorithms  
- Evaluation using metrics like:
  - Confusion Matrix
  - ROC Curve
  - Accuracy and Precision Scores
- Streamlit-based interactive form to input medical parameters and generate live predictions

---

## 📊 Technologies Used

- **Python 3**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **Matplotlib**, **Seaborn**
- **Streamlit**
- **Google Colab**

---

## 🚀 How to Use

### ▶️ Option 1: Run in Google Colab
> Recommended for quick testing.

1. Open the notebook in Google Colab  
2. Run all cells sequentially  
3. Enter input parameters in the Streamlit form  
4. View prediction and model evaluation metrics

### ▶️ Option 2: Run Locally (Convert notebook to `.py` if needed)

```bash
pip install -r requirements.txt
streamlit run diabetes_prediction_streamlit.py
