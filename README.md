##Heart Disease Prediction Web Application

* This is a simple web application built with Flask, where users can input health data, and it predicts the likelihood of heart disease using a pre-trained machine learning model.

##Features:

* Web Interface: The app provides a user-friendly web interface where users can enter various health parameters.
* Prediction: Once the user submits the form, the application uses a pre-trained machine learning model to predict the likelihood of heart disease.
* Result Display: After the prediction, the result is displayed on a separate page.
  
##Project Structure

*******************************************************************************************
/heart-disease-prediction/

│
├── app.py                     # Flask application code
├── /templates/

│   ├── home.html              # HTML file for input form
│   └── predict.html           # HTML file to display the prediction result

├── heart2.pkl                 # Pre-trained machine learning model

└── requirements.txt           # List of required dependencies
*******************************************************************************************

##Requirements:

Before running this application, make sure you have Python 3.6+ installed. Then, install the required dependencies.

##Install Dependencies

Clone the repository:

*******************************************************************************************
git clone https://github.com/yourusername/heart-disease-prediction.git
cd heart-disease-prediction
*******************************************************************************************
Create a virtual environment and activate it:
*******************************************************************************************
python -m venv venv
# Windows
venv\Scripts\activate
# Linux/Mac
source venv/bin/activate
Install the required Python packages:
*******************************************************************************************
pip install -r requirements.txt

##Dependencies:

This project uses the following Python packages:

Flask
NumPy
scikit-learn
These dependencies are listed in requirements.txt for easy installation.

##Model
The machine learning model used in this application is a pre-trained model saved as heart2.pkl. This model was trained to predict the likelihood of heart disease based on various health features such as age, blood pressure, cholesterol levels, etc.

##Running the Application
To start the Flask application, run the following command in the project directory:

*******************************************************************************************
python app.py
*******************************************************************************************
This will start the server locally, and you can access the application at http://127.0.0.1:5000/ in your browser.

##Usage
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

##Output
The model will predict whether the individual has heart disease or not based on the provided health parameters.

##Project Pages
home.html
This is the main page of the application. It contains the form where users enter their health data.

##predict.html
This page displays the predicted result after the user submits the form. It shows whether the person has heart disease or not based on the model's prediction.

License
This project is open source and available under the MIT License.

Author
Romdhani Amina
GitHub | LinkedIn







