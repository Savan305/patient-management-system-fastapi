# 🚀 Insurance Premium Category Predictor

A full-stack Machine Learning web application that predicts the **insurance premium category** based on user details like age, BMI, income, lifestyle, and city.

---

## 🌐 Live Demo

* 🔗 **Frontend (Streamlit App):**
https://patient-management-system-fastapi-bgmmugfvybxhl5ct7hjyi8.streamlit.app/

* 🔗 **Backend API (FastAPI - Swagger UI):**
  https://patient-management-system-fastapi-awd1.onrender.com/docs

---

## 📌 Features

* ✅ Predict insurance premium category (Low / Medium / High)
* ✅ Real-time API integration (FastAPI + Streamlit)
* ✅ Clean and interactive UI using Streamlit
* ✅ Feature engineering (BMI, lifestyle risk, age group, city tier)
* ✅ Deployed backend on Render
* ✅ Deployed frontend on Streamlit Cloud

---

## 🧠 Machine Learning Details

* 📊 Model: Random Forest Classifier
* 📁 Dataset: Insurance dataset (custom processed)
* 🔧 Features used:

  * Age
  * BMI (calculated)
  * Income (LPA)
  * Smoking status
  * City tier
  * Occupation
  * Lifestyle risk (engineered feature)

---

## 🏗️ Tech Stack

| Layer      | Technology               |
| ---------- | ------------------------ |
| Frontend   | Streamlit                |
| Backend    | FastAPI                  |
| ML Model   | Scikit-learn             |
| Deployment | Render + Streamlit Cloud |
| Language   | Python                   |

---

## ⚙️ Project Structure

```
project/
│
├── app.py              # FastAPI backend
├── model.pkl           # Trained ML model
├── frontend.py         # Streamlit frontend
├── requirements.txt    # Dependencies
```

---

## ▶️ How to Run Locally

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/patient-management-system-fastapi.git
cd patient-management-system-fastapi
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run FastAPI backend

```bash
uvicorn app:app --reload
```

### 4️⃣ Run Streamlit frontend

```bash
streamlit run frontend.py
```

---

## 🔌 API Endpoint

### POST `/predict`

#### Sample Input:

```json
{
  "age": 30,
  "weight": 65,
  "height": 1.7,
  "income_lpa": 10,
  "smoker": true,
  "city": "Mumbai",
  "occupation": "private_job"
}
```

#### Sample Output:

```json
{
  "predicted_category": "medium"
}
```

---

## 📸 Screenshots

> Add your app screenshots here for better presentation

---

## 🚧 Future Improvements

* 🔐 Add user authentication
* 📊 Display prediction confidence & charts
* 🌍 Add more real-world dataset features
* ⚛️ Convert frontend to React for scalability

---

## 🙋‍♂️ Author

**Your Name**

* GitHub: https://github.com/your-username
* LinkedIn: (Add your LinkedIn here)

---

## ⭐ If you like this project

Give it a ⭐ on GitHub — it helps a lot!
