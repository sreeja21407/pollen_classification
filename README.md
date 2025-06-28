# pollen_classification
🌾 Pollen Profiling - Automated Classification of Pollen Grains
Welcome to Pollen Profiling, a deep learning-based pollen grain classification project using TensorFlow and Keras.

🚀 ## Project Overview
This project focuses on classifying pollen grain species from microscopic images using a Convolutional Neural Network (CNN). It includes:

✅ A custom-trained Keras model (model.h5)

✅ Preprocessed pollen image dataset (excluded from Git)

✅ A simple Flask-based web application

📁 ## Directory Structure
php
Copy
Edit
Pollen-Profiling/
│
├── app.py                         # Flask backend & routing
├── model.h5                       # Trained model (gitignored)
├── label_encoder.pkl              # Label encoder (gitignored)
├── dataset/                       # Pollen image dataset (gitignored)
├── static/                        # CSS & uploaded images
├── templates/                     # HTML templates
├── pollen_grain_classification.ipynb  # Training & model building notebook
├── .gitignore
└── README.md
🚫 Files Ignored via .gitignore
To keep the repository clean and lightweight:

gitignore
Copy
Edit
dataset/
*.h5
*.pkl
*.pyc
_pycache_/
python-*.exe
These files must be downloaded or generated locally before running the project.

📊 Model Details
Type: Convolutional Neural Network (CNN)

Framework: TensorFlow & Keras

Model File: model.h5

Accuracy: 99% 

Encoder File: label_encoder.pkl (used for decoding predictions)

🌐 Web Application (Flask)
The app features:

📤 Upload an image

🔍 Predict pollen species

🧠 Display prediction & confidence level

🔁 Logout navigation

▶ How to Run
🔧 Install dependencies:
bash
Copy
Edit
pip install -r requirements.txt
🚀 Start the Flask server:
bash
Copy
Edit
set FLASK_APP=app.py
set FLASK_ENV=development
flask run
Open your browser at http://127.0.0.1:5000/

📄 Project Notes
GitHub restricts pushing files larger than 100MB, so model.h5 is excluded from version control.

Please generate or request the model and dataset files as needed.

📧 Contact
Manthena Sai Phani Sreeja
Email: sreejamanthena44@gmail.com
