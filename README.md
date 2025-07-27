# 🧠 Multiple Disease Prediction

**Multiple Disease Prediction** is a machine learning-powered web application that allows users to predict the likelihood of multiple diseases— Diabetes and Heart Disease based on inputted clinical data. The models are trained using standard datasets and the app is deployed using Streamlit for an interactive user experience.

---

## 🚀 Features

- **Disease Prediction**: Predicts the likelihood of  
  - 🩸 **Diabetes**  
  - ❤️ **Heart Disease**  

- **Streamlit Interface**: Simple, interactive UI for inputting parameters and viewing results.

- **Google Colab Training**: ML models trained in Colab and exported as `.sav` files.

- **Preprocessing with Scaler**: Ensures consistent input handling using a saved `scaler.pkl`.

- **Modular Structure**: Clean folder layout for models, notebooks, and app logic.

---

## 🧰 Getting Started

To get the **Multiple Disease Prediction** app running locally, follow the instructions below to set up the application on your local machine.

### ✅ Prerequisites

Ensure you have the following installed:

- [Python](https://www.python.org/downloads/) 3.8+
- pip (Python package manager)
- Git (optional, for cloning)

---

## 1. Clone the Repository

```bash
git clone https://github.com/tanmay-srivastav4/multiple-disease-prediction.git
cd multiple-disease-prediction
```

## 2. Create Virtual Environment (Optional)

# For Windows
```bash
python -m venv venv
venv\Scripts\activate
```

# For Mac/Linux
```bash
python3 -m venv venv
source venv/bin/activate
```

## 3. Install Dependencies
```bash
pip install -r requirements.txt
```

## 4. Run the Application
```bash
streamlit run app.py
```
---

📁 Project Structure
multiple-disease-prediction/
│
├── app.py                  # Main Streamlit app file
├── requirements.txt        # Python package dependencies
├── scaler.pkl              # Preprocessing scaler for consistent input
│
├── saved_models/           # Directory containing .sav model files
├── colab_notebooks/        # Notebooks used for initial training
└── training_notebooks/     # Refined and modular notebooks

---

🧰 Technologies Used
  1. Frontend: Streamlit
  2. Backend: Python
  3. ML Libraries: scikit-learn, pandas, numpy
  4. Model Training: Google Colab
  5. Model Serialization: joblib (.sav format)


