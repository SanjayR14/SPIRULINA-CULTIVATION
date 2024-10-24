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


source venv/bin/activate  


# On Windows, use venv\Scripts\activate


pip install -r requirements.txt



#Install Node dependencies:


cd frontend
npm install


#Run the backend:


python manage.py


#Run the frontend:


cd frontend
npm start





DATASET DESCRIPTION:
The dataset has been build from the refference of article[1].The relationship between the features are taken from various articles[3]-[7].

1. Initial pH: It is the pH value at the beginning of the cultivation and optimal pH ranges are between 8.5-11.
2. Light Intensity (lux): The intensity of light supplied during the culture (range: 2,000-10,000 lux).
3. NaNO3 (g/L): The quantity of sodium nitrate in g/L. Sodium nitrates are a source of nitrogen used in the culture with a range of 1.5-2.5 g/L
4. Inoculum Level (%): The level of initial algae culture supplied into the medium. Range: 5-10%.
5. Culture Time (days): The range of culture time is 7-14 days.
6. Seawater Medium (%): Percentage of seawater supplied with the culture medium. The seawater medium should have a range of 0-100%.
7. Sodium bicarbonate (mg/L):This is one source of carbon, 10-20.
8. Temperature (°C): The temperature of the growth environment, 30-37.
9. K2HPO4 (mg/L): This is a source of phosphorus, 0.5 - 1.0.
10. Salinity(%): This refers to the salt concentration of the medium, 0.5-3.5%.
11. Aeration(1 = yes, 0 = no):Did you provide aeration? If, yes = 1 and No = 0.
12. Light Time(hours): How many hours per day were the microorganisms exposed to light? 12-16 hours.
13. Flask System (1=yes, 0=no): Did you use a flask system? Yes=1 No=0
14. Dark Time (hours): How many hours of darkness were present per day? Must fall between: 8 hours-12 hours
15. BG11 Medium (1=yes, 0=no): Did you use BG11 medium? It's the standard growth medium, but it's not specific. Yes=1 No=0
16. Na2CO3 (g/L): How many grams/liter of sodium carbonate? It's an other carbon source. Use the following range: 0.5 g/L-1.0 g/L
17. Pond System (1=yes, 0=no): Did you use a pond system? It's for control. Example, Yes=1 No=0
18. Urea (g/L): How many grams/liter of urea? It's another nitrogen source. Use the following range: 0.1 g/L-0.5 g/L.
19.Trace Elements (count): Trace elements added to the medium (count: 5-10)
20. Biomass Yield (g/L): The biomass obtained from the algae culture (range: 0.5-1.5 g/L)
21.Protein content: The  class contains the protein  of the algae(low, medium, very high)


Dataset Link:
https://onedrive.live.com/edit?id=2AD6E09B190DB9F7!s1b9287961a3c4bde968e715fb9b46502&resid=2AD6E09B190DB9F7!s1b9287961a3c4bde968e715fb9b46502&cid=2ad6e09b190db9f7&ithint=file%2Cxlsx&redeem=aHR0cHM6Ly8xZHJ2Lm1zL3gvYy8yYWQ2ZTA5YjE5MGRiOWY3L0VaYUhraHM4R3Q1TGxvNXhYN20wWlFJQk5oV2p1b0tqVWphb0ROVk90ME1OVXc_ZT1zUERZSmY&migratedtospo=true&wdo=2



![Alt text](./images/Screenshot%202024-10-24%20125003.png)


![Alt text](./images/Screenshot%202024-10-24%20125033.png)



![Alt text](./images/Screenshot%202024-10-24%20125056.png)


![Alt text](./images/Screenshot%202024-10-24%20125120.png)



![Alt text](./images/Screenshot%202024-10-24%20125145.png)




