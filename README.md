# Predictive Maintenance System for Industrial Equipment

## 🛠️ Project Overview
This project addresses the problem of unexpected machine failure in manufacturing. By using sensor data (Temperature, Torque, Speed), the AI predicts the **Remaining Useful Life (RUL)** of components to prevent expensive downtime.

## 📊 Dataset
I used the **AI4I 2020 Predictive Maintenance Dataset**, which contains 10,000 instances of industrial sensor readings.

## 🚀 How to Run
1. Open Google Colab.
2. Upload the `ai4i2020.csv` file.
3. Upload and run the `AIMLproject.ipynb` notebook.
4. Input manual sensor data in the interactive section to get a risk score.

## 🕹️ Interactive Prediction Feature
One of the key highlights of this project is the **Interactive Machine Health Checker**. 

Unlike standard models that only process historical data, this project includes a real-time inference loop. A user can manually input current sensor readings (Temperature, Torque, etc.), and the AI will immediately:
1. Calculate the **Failure Risk Percentage**.
2. Categorize the machine's status as **Normal, Caution, or Danger**.
3. Provide a recommended action for maintenance teams.

## 🧠 AI Concepts Used
- **Supervised Learning:** Linear Regression.
- **Data Visualization:** Matplotlib and Seaborn for correlation analysis.
- **Statistical Risk Modeling:** Calculating failure probability percentages.
