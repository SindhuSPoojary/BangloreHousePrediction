# 🏡 Bangalore House Price Prediction

A machine learning web application that predicts house prices in Bangalore based on user inputs such as location, area, number of bedrooms, and bathrooms. The application is built using **Python**, **Streamlit**, and a trained **Random Forest Regressor** model.

---

## 📌 Features

- Predicts house prices in Bangalore.
- User-friendly web interface built with Streamlit.
- Fast and accurate predictions using a trained Random Forest model.
- Interactive animations for a better user experience.
- Simple and responsive design.

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Scikit-learn
- Pandas
- NumPy
- Joblib/Pickle
- Lottie Animations

---

## 📂 Project Structure

```
BangloreHousePrediction/
│── app.py
│── requirements.txt
│── RFmodel.pkl
│── cleaned_df.csv
│── Bengaluru_House_Data.csv
│── home_anime.json
│── loading_anime.json
│── house_price_prediction.ipynb
│── icons/
└── .gitignore
```

---

## 📊 Dataset

The project uses the **Bengaluru House Price Dataset**, which contains information such as:

- Location
- Total Area (sq.ft.)
- Number of Bedrooms (BHK)
- Number of Bathrooms
- Price

The dataset is cleaned and preprocessed before training the model.

---

## 🤖 Machine Learning Model

- Algorithm: **Random Forest Regressor**
- Data preprocessing:
  - Missing value handling
  - Feature selection
  - Data cleaning
  - Model training and evaluation

The trained model is saved as:

```
RFmodel.pkl
```

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/BangloreHousePrediction.git
```

### 2. Navigate to the project

```bash
cd BangloreHousePrediction
```

### 3. Create a virtual environment (Optional)

```bash
python -m venv .venv
```

### 4. Activate the virtual environment

Windows:

```bash
.venv\Scripts\activate
```

Linux/macOS:

```bash
source .venv/bin/activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the application

```bash
streamlit run app.py
```

The application will open in your browser at:

```
http://localhost:8501
```

---

## 📈 Workflow

1. Load the trained Random Forest model.
2. Accept user inputs.
3. Preprocess the inputs.
4. Predict the house price.
5. Display the estimated price.

---

## 📷 Application Preview
```
### Home Page
images/home_page.png

### Prediction Page
images/prediction_page.png
images/predicted_price.png

### Dashboard
images/dashboard_1.png
images/dashboard_2.png

---

## 📌 Future Improvements

- Support more cities.
- Improve prediction accuracy.
- Deploy the application online.
- Integrate maps for location selection.
- Compare prices with nearby properties.

---

## 👨‍💻 Author

**Sindhu S Poojary**

GitHub: https://github.com/SindhuSPoojary

---
