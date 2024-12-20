<h1 style="color: #FF5733;">❤️ Heart Disease Prediction Web Application</h1>
🚀 This web application is built with Flask, allowing users to input health data and predict the likelihood of heart disease using a pre-trained machine learning model.

<h2 style="color: #28A745;">🌟 Features</h2>
🖥️ Web Interface:
Provides a user-friendly interface to input various health parameters.

🔍 Prediction:
Utilizes a pre-trained machine learning model to predict heart disease likelihood.

📊 Result Display:
Shows results on a separate page with clear and concise information.

<h2 style="color: #007BFF;">📁 Project Structure</h2>
plaintext
Copier le code
/heart-disease-prediction/
│
├── app.py                     # Flask application code
├── /templates/                
│   ├── home.html              # HTML for input form
│   └── predict.html           # HTML to display prediction results
├── heart2.pkl                 # Pre-trained machine learning model
└── requirements.txt           # Dependencies list
<h2 style="color: #FFC107;">⚙️ Requirements</h2>
Before running this application, ensure Python 3.6+ is installed.

<h2 style="color: #17A2B8;">📥 Install Dependencies</h2>
Clone the Repository
bash
Copier le code
git clone https://github.com/yourusername/heart-disease-prediction.git
cd heart-disease-prediction
Create and Activate a Virtual Environment
bash
Copier le code
# Create a virtual environment
python -m venv venv

# Activate the environment
# On Windows:
venv\Scripts\activate
# On Linux/Mac:
source venv/bin/activate
Install the Required Packages
bash
Copier le code
pip install -r requirements.txt
<h2 style="color: #6F42C1;">📦 Dependencies</h2>
This project uses the following Python packages:

Flask
NumPy
scikit-learn
<h2 style="color: #E83E8C;">🧠 Model</h2>
The application uses a pre-trained machine learning model (heart2.pkl) trained to predict heart disease based on features like:

🧓 Age
🩸 Blood Pressure
🩺 Cholesterol Levels
🧪 Fasting Blood Sugar, etc.
<h2 style="color: #20C997;">▶️ Running the Application</h2>
Start the Flask app:

bash
Copier le code
python app.py
Open your browser and visit:
http://127.0.0.1:5000/

<h2 style="color: #DC3545;">📝 Usage</h2>
Open the app in your browser.
Fill in the health parameters in the form.
Submit the form to get the prediction result.
Input Fields
a: Age
b: Blood Pressure
c: Cholesterol Level
d: Fasting Blood Sugar
e: Resting ECG
f: Maximum Heart Rate Achieved
g: Exercise Induced Angina
h: Oldpeak Depression
i: Slope of the Peak Exercise ST Segment
j: Number of Major Vessels Colored by Fluoroscopy
k: Thalassemia
<h2 style="color: #FD7E14;">📊 Output</h2>
The model predicts whether the individual has heart disease or not based on the provided health parameters.

<h2 style="color: #6610F2;">🌐 Project Pages</h2>
🏠 home.html
The main page of the application.
Contains the form where users can enter their health data.
📈 predict.html
Displays the prediction results.
Clearly indicates whether the person has heart disease or not.
<h2 style="color: #17A2B8;">📜 License</h2>
This project is open source and available under the MIT License.



