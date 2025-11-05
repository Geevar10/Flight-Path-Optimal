# ✈️ Flight Path Optimization using Machine Learning Final 

## 📖 Overview
Flight path optimization is essential for reducing fuel consumption, travel time, and operational costs. Traditional approaches rely on fixed routes and static weather forecasts, which often lead to inefficiencies.  

This project applies **clustering techniques** on historical flight and weather data, and then matches real-time weather conditions to the nearest cluster. The system selects the **optimal flight path** with the least travel time, ensuring better efficiency, lower emissions, and enhanced safety.

This is my College Mini Project and is done by:
Geevar P Kocheril,JR Gopika,GauthamKrishna Benoy,Ephraim Abraham

Link of original repo: https://github.com/Gopika011/Fligh_Patht_Optimal

---

## 🚀 Features
- Uses **clustering** on past flight data for pattern recognition.  
- Matches **real-time weather conditions** to the closest flight cluster.  
- Selects the **best path with minimum travel time**.  
- Reduces **fuel usage, CO₂ emissions, and costs**.  
- Demonstrates practical use of **AI in aviation planning**.  

---

## 🛠️ Implementation
1. **Data Collection** – Historical flight records and weather data are gathered.  
2. **Clustering Model** – Apply machine learning (e.g., K-Means) to group similar flight paths.  
3. **Real-Time Matching** – Fetch live weather conditions via an API.  
4. **Path Selection** – Identify the cluster matching the real-time conditions and choose the route with the least travel time.  
5. **Execution** – A Python app integrates these steps for easy execution.  

---

## ▶️ How to Run
To run this project on your local machine:

```bash
# Clone the repository
git clone https://github.com/username/flight-path-optimization.git

# Navigate into the project folder
cd HTM

# Install required dependencies
pip install -r requirements.txt

# Run the application
python app.py
#
