# ✈️ Flight Price Prediction.

This web application predicts the price of a flight ticket based on various input features such as airline, source and destination cities, departure/arrival times, number of stops, travel class, and departure date. The app is built using **HTML (Frontend)** and **Flask (Backend)**, and utilizes a trained machine learning model for the prediction logic.

---

![Image](https://github.com/user-attachments/assets/9189ccb0-2795-4ea7-8c55-231458925252)


## 🔧 Technologies Used

- **Frontend**: HTML, CSS
- **Backend**: Python, Flask
- **Machine Learning**: Scikit-learn / XGBoost / Random Forest (based on model used)
- **Model Deployment**: Flask REST API

---
### 📈 Sample Output
Once the user submits the form, the app sends data to the Flask API and returns the predicted flight price (e.g., ₹4500).

---

## 🚀 How to Run the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/flight-price-prediction.git
cd flight-price-prediction
```
### 2. Create Virtual Environment
```
python -m venv venv
source venv/bin/activate     # For Linux/Mac
venv\Scripts\activate        # For Windows
```
### 3. Install Dependencies
```
pip install -r requirements.txt
```
### 4. Run the Flask App
```
python app.py
```

### 🏁 Future Enhancements

- Add more airlines and cities

- Improve model accuracy using deep learning

- Deploy on cloud (Heroku, Render, or AWS)

- Integrate real-time flight APIs for validation
