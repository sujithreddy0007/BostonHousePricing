# 🏡 Boston House Price Prediction

A simple end-to-end Machine Learning web application that predicts the price of houses in Boston using Flask. The model is trained on the Boston Housing dataset and deployed live using Render.

## 🔗 Live Demo
👉 [Click here to view the deployed app](https://bostonhousepricing-9u0d.onrender.com)

## 🚀 Features
- Predict Boston house prices based on 13 features
- Clean and user-friendly UI using HTML and Flask templates
- RESTful API support (send JSON input via tools like Postman)
- Live deployment with Render
- Model persistence with Pickle

## 🧠 Technologies Used
- Python 3.9+
- Flask
- Scikit-learn
- Pandas, NumPy
- Gunicorn (for production server)
- HTML/CSS (for the frontend)
- Render (for deployment)

## 📁 Project Structure
END_to-END_MLProject/
│
├── app.py # Flask application
├── regmodel.pkl # Trained ML model
├── scaling.pkl # Scaler for feature normalization
├── requirements.txt # Python dependencies
├── templates/
│ └── home.html # HTML frontend
└── README.md # Project overview

## 🔧 How to Run Locally
1. Clone the repository:
git clone https://github.com/sujithreddy0007/BostonHousePricing.git
cd BostonHousePricing

2. Create and activate virtual environment:
python -m venv venv
venv\Scripts\activate   # For Windows
# or
source venv/bin/activate  # For Mac/Linux

3. Install dependencies:
pip install -r requirements.txt

4. Run the Flask app:
python app.py
Then visit http://localhost:5000 in your browser.

## 🧪 API Usage (Optional)
Send POST request to:
POST https://bostonhousepricing-9u0d.onrender.com/predict_api

Example JSON Payload:
{
  "CRIM": 0.00632,
  "ZN": 18.0,
  "INDUS": 2.31,
  "CHAS": 0.0,
  "NOX": 0.538,
  "RM": 6.575,
  "Age": 65.2,
  "DIS": 4.0900,
  "RAD": 1.0,
  "TAX": 296.0,
  "PTRATIO": 15.3,
  "B": 396.90,
  "LSTAT": 4.98
}

✍️ Author
Sujith Reddy
GitHub: @sujithreddy0007
Email: sujeethreddy0007@gmail.com
