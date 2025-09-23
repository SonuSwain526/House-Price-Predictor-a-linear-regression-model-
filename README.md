# House-Price-Predictor-a-linear-regression-model-
# 🏠 House Price Prediction Web App

A Machine Learning project that predicts **house prices** based on various input features (like location, rooms, population, median income, etc.).  
The model is trained on the **California Housing dataset** and deployed using **Flask** as a simple web app where users can input values and get predictions instantly.  

---

## 🚀 Features
- Regression model trained with **Random Forest Regressor**  
- Preprocessing pipeline with **Imputation, Scaling, and One-Hot Encoding**  
- Web interface built using **Flask + HTML + CSS**  
- User-friendly form to input features  
- Real-time prediction displayed on the page  

---

## 📂 Project Structure
📁 house-price-prediction
│── app.py # Flask application
│── model.pkl # Trained ML model
│── pipeline.pkl # Preprocessing pipeline
│── housing.csv # Dataset (California Housing)
│── templates/
│ └── index.html # Webpage template
│── static/ # (Optional) for CSS/JS/images
│── requirements.txt # Python dependencies
│── README.md # Project documentation


---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/house-price-prediction.git
   cd house-price-prediction

Create a virtual environment (recommended)
python -m venv venv
source venv/bin/activate    # For Linux/Mac
venv\Scripts\activate       # For Windows

Install dependencies
pip install -r requirements.txt

Run the Flask app
python app.py

Open in your browser
http://127.0.0.1:5000/


🧠 Model Details

Algorithm: Random Forest Regressor

Preprocessing:

Numerical: Imputation (mean) + Standard Scaling

Categorical: Imputation (most frequent) + One-Hot Encoding

Train/Test Split: Stratified by income_cat (80/20)

🎨 Web Interface

Clean and modern form built with HTML + CSS

Input fields for all features:

Longitude, Latitude, Housing Median Age, Total Rooms,
Total Bedrooms, Population, Households, Median Income, Ocean Proximity

Dropdown for categorical feature ocean_proximity

Prediction displayed instantly after submitting the form

📸 Demo Screenshot

(Add a screenshot of your running app here)

📌 Future Improvements

Add support for CSV upload & batch predictions

Deploy on Heroku / Render / PythonAnywhere for public access

Use more advanced models or hyperparameter tuning

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

📜 License

This project is licensed under the MIT License – feel free to use and modify.


---

👉 You just need to:  
1. Save it as **README.md** in your repo.  
2. Replace `your-username` with your GitHub username.  
3. Add a **screenshot** of your web app for extra appeal.  

Do you want me to also create a **requirements.txt** for you so it’s ready to push?
