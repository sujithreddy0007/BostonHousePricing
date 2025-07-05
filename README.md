# 🏡 Boston House Price Prediction

A simple end-to-end Machine Learning web application that predicts the price of houses in Boston using Flask. The model is trained on the Boston Housing dataset and deployed live using Render.

---

## 🔗 Live Demo

👉 [Click here to view the deployed app](https://bostonhousepricing-9u0d.onrender.com)

---

## 🚀 Features

- Predict Boston house prices based on 13 features
- Clean and user-friendly UI using HTML and Flask templates
- RESTful API support (send JSON input via tools like Postman)
- Live deployment with Render
- Model persistence with Pickle

---

## 🧠 Technologies Used

- Python 3.9+
- Flask
- Scikit-learn
- Pandas, NumPy
- Gunicorn (for production server)
- HTML/CSS (for the frontend)
- Render (for deployment)

---

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

yaml
Copy
Edit

---

## 🔧 How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/sujithreddy0007/BostonHousePricing.git
cd BostonHousePricing
Create and activate a virtual environment:

bash
Copy
Edit
python -m venv venv
venv\Scripts\activate   # Windows
# or
source venv/bin/activate  # Linux/Mac
Install the dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the application:

bash
Copy
Edit
python app.py
Visit http://localhost:5000 in your browser.

🧪 API Usage (Optional)
You can also send data via POST request using Postman or curl.

Example JSON:
json
Copy
Edit
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
Send it to:

bash
Copy
Edit
POST https://bostonhousepricing-9u0d.onrender.com/predict_api
✍️ Author
Sujith Reddy
GitHub: @sujeethreddy0007@gmail.com
