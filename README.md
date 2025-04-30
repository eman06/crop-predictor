# crop-predictor
🚜 A simple web application built using Flask and a trained machine learning model to predict the most suitable crop based on soil and climate conditions. Users input values like nitrogen, phosphorus, rainfall, and temperature to get real-time crop suggestions.  💡 Powered by Python, Flask, HTML/CSS, and a scikit-learn model serialized with Pickle.


---

## 🚀 Features

- User-friendly HTML form for input
- Real-time crop prediction using a trained ML model
- Lightweight and easy to deploy locally or online
- Built with Flask and Pickle for backend model handling


---

## 📁 Files to Include

- `app.py` – Main Flask application
- `templates/myhtml.html` – Frontend form (Jinja2 templating)
- `model.pkl` – Pre-trained machine learning model
- `requirements.txt` – List of required Python libraries
- `README.md` – Project documentation

---

## ⚙️ How to Run Locally

1. **Clone this repo**
   ```bash
   git clone https://github.com/yourusername/crop-predictor.git
   cd crop-predictor
Install dependencies

pip install -r requirements.txt

Run the app
python app.py
Open your browser and go to http://127.0.0.1:5000/

🧠 Model Input Format
The model expects the following numerical inputs:

-Nitrogen (N)
-Phosphorus (P)
-Potassium (K)
-Temperature (°C)
-Humidity (%)
-pH level
-Rainfall (mm)

📦 Requirements
Python 3.x
Flask
scikit-learn
numpy
pickle

You can install all dependencies using:

pip install -r requirements.txt


🌐 Deployment
To make the app publicly available, consider deploying it using:

-Render
-Replit
-PythonAnywhere

🙌 Acknowledgements
-Dataset from Kaggle’s crop recommendation dataset
-Model trained using scikit-learn
-Flask documentation and tutorials


👤 Author
Eman Ihsan

GitHub: @eman06
