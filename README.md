
# ❤️ Heart Disease Prediction using Machine Learning

This project is a simple yet powerful **Heart Disease Prediction System** built using **Python, Streamlit, and Machine Learning**. It allows users to input basic health-related metrics and receive a prediction about the presence of heart disease.

---

## 🧠 Machine Learning Model

We use a **Logistic Regression** model trained on a publicly available dataset (Cleveland dataset from UCI) to predict whether a person has heart disease or not.

---

## 🛠️ Tech Stack

- **Frontend**: Streamlit  
- **Backend**: Scikit-learn, Pandas, NumPy  
- **Language**: Python  
- **Model**: Logistic Regression  

---

## 🖼️ App Features

- Clean UI built with Streamlit  
- Takes in multiple user inputs:  
  - Age, Sex, Chest Pain Type, Resting BP, Cholesterol, Fasting Blood Sugar, etc.  
- Predicts if the user is likely to have heart disease  
- Displays result instantly on the screen  

---

## 📁 Project Structure

```
heart-disease-prediction/
├── app.py                  # Streamlit web app
├── model.py                # Model training and prediction logic
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## 📊 Input Parameters

| Parameter              | Description                              |
|------------------------|------------------------------------------|
| Age                    | Age of the person                        |
| Sex                    | 1 = Male, 0 = Female                     |
| Chest Pain Type        | 0–3 numeric value                        |
| Resting BP             | Resting blood pressure (mm Hg)          |
| Cholesterol            | Serum cholesterol in mg/dl              |
| Fasting Blood Sugar    | >120 mg/dl (1 = True, 0 = False)        |
| Resting ECG            | 0–2 (electrocardiographic results)      |
| Max Heart Rate         | Achieved max heart rate                 |
| Exercise Induced Angina| 1 = Yes, 0 = No                          |
| ST Depression          | Depression induced by exercise          |
| ST Slope               | Slope of the peak exercise ST segment   |

---

## 🤖 Model Accuracy

- Logistic Regression Accuracy: **~86%**  
- Trained using **train_test_split** with **stratified sampling**

