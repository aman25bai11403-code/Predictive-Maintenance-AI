# Predictive Maintenance System for Industrial Equipment

[](https://colab.research.google.com/drive/1imHAQ4lChJzsE7gajH-ztGGIRC0nInuO?usp=sharing)

## 🛠️ Project Overview

This project addresses the problem of unexpected machine failure in manufacturing. By using sensor data (Temperature, Torque, Speed), the AI predicts the **Remaining Useful Life (RUL)** of components to prevent expensive downtime.

## 📊 Dataset

I used the **AI4I 2020 Predictive Maintenance Dataset**, which contains 10,000 instances of industrial sensor readings.

## 🚀 How to Run

**Direct Link:** [https://colab.research.google.com/drive/1imHAQ4lChJzsE7gajH-ztGGIRC0nInuO?usp=sharing](https://colab.research.google.com/drive/1imHAQ4lChJzsE7gajH-ztGGIRC0nInuO?usp=sharing)

1.  Open the link above in Google Colab.
2.  Upload the `ai4i2020.csv` file to the Colab runtime.
3.  Run all cells to train the **Linear Regression** model.
4.  Input manual sensor data in the interactive section to get a risk score.

## 🕹️ Interactive Prediction Feature

One of the key highlights of this project is the **Interactive Machine Health Checker**. Unlike standard models, this project includes a real-time inference loop where a user can manually input current sensor readings to immediately:

1.  Calculate the **Failure Risk Percentage**.
2.  Categorize the machine's status as **Normal, Caution, or Danger**.
3.  Provide a recommended action for maintenance teams.

## 🧠 AI Concepts Used

  * **Supervised Learning:** Linear Regression model.
  * **Data Visualization:** Matplotlib and Seaborn for correlation analysis.
  * **Intelligent Agents:** System acts as a diagnostic agent perceiving sensor environments.
  * **Robustness Engineering:** Implemented output clamping and input validation for logically sound predictions.

-----
