# Online Payment Fraud Detection

This project aims to detect fraudulent online payment transactions using machine learning models. It features a Flask-based backend with a simple HTML/CSS frontend for user interaction.

## 📁 Project Structure

ONLINE_PAYMENT_FRAUD_DETECTION/
│
├── backend/ # Backend logic and model files
│ ├── app.py # Flask application
│ ├── data.csv # Dataset used for model training
│ ├── model_nn.pkl # Trained Neural Network model
│ ├── model_rfc.pkl # Trained Random Forest model
│ ├── NEURAL.ipynb # Notebook for NN training
│ ├── online_fraud.ipynb # Notebook for data exploration and preprocessing
│ └── requirements.txt # Required Python packages
│
├── frontend/ # Frontend HTML templates
│ ├── index.html # Home page
│ ├── predict.html # Prediction results page
│ └── feedback.html # Feedback page
│
├── static/ # Static files (CSS, images)
│ ├── styles.css # Custom stylesheet
│ └── images/ # Image assets
│
└── .gitignore # Files to ignore in Git

bash
Copy
Edit

## 🚀 How to Run the Project

### Prerequisites

- Python 3.7 or higher
- pip


1. Create and Activate a Virtual Environment (Optional but Recommended)
2. Enusre proper directory before running the project (i.e. inside backend)

python -m venv venv
# Activate:
# On Windows:
venv\Scripts\activate
# On Unix or MacOS:
source venv/bin/activate
3. Install Required Packages
bash
Copy
Edit
pip install -r backend/requirements.txt
4. Run the Application
bash
Copy
Edit
cd backend
python app.py
The app should now be running at http://127.0.0.1:5000.

🖥️ Usage
Go to the home page (index.html)

Submit transaction details to predict fraud using trained models

View results on predict.html

Provide feedback via feedback.html

🧠 Models Used
Neural Network (model_nn.pkl)

Random Forest Classifier (model_rfc.pkl)

📊 Dataset
The dataset (data.csv) is located in the backend/ folder and contains transaction records for training/testing the models.

🛠 Future Enhancements
Add database support for logging transactions

Integrate user authentication

Deploy to cloud (Heroku, AWS, etc.)

📄 License
This project is licensed under the MIT License.