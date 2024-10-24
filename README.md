# ML Project
Spirulina Yield Prediction is an interactive tool that predicts the protein content of Spirulina based on input parameters such as pH, light intensity, temperature, and other cultivation factors. Users can easily enter their cultivation conditions, and the site provides real-time predictions of protein levels (Low, Medium, or High) using machine learning models. This helps Spirulina producers and researchers optimize cultivation processes for higher yields and better resource efficiency. The platform offers a simple and intuitive interface, making it accessible for both experts and non-experts in the field.


#This project analyzes Spirulina cultivation data to predict protein content using machine learning models like Decision Tree and k-NN.




#Prerequisites


Python 3.x
Node.js
MongoDB
#Required Python libraries (see requirements.txt)



How to Download and Run



#Clone the repository:



git clone https://github.com/SanjayR14/SPIRULINA-CULTIVATION.git


cd SPIRULINA-CULTIVATION



#Set up the environment:



python -m venv venv
source venv/bin/activate  # On Windows, use venv\Scripts\activate
pip install -r requirements.txt



#Install Node dependencies:


cd frontend
npm install


#Run the backend:


python backend/app.py


#Run the frontend:


cd frontend
npm start
