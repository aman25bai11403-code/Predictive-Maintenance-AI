# Predictive Maintenance System for Industrial Equipment

[](https://colab.research.google.com/drive/1imHAQ4lChJzsE7gajH-ztGGIRC0nInuO?usp=sharing)

## 🛠️ Project Overview

This project addresses the problem of unexpected machine failure in manufacturing. By using sensor data (Temperature, Torque, Speed), the AI predicts the **Remaining Useful Life (RUL)** of components to prevent expensive downtime. This facilitates a transition from reactive to proactive maintenance, ensuring that interventions are synchronized with the actual physical state of the machinery.

## 📊 Dataset

I used the **AI4I 2020 Predictive Maintenance Dataset**, which contains 10,000 instances of industrial sensor readings. The model focuses on critical operational parameters:

  * **Thermal Dynamics:** Air and Process Temperature [K].
  * **Mechanical Kinematics:** Rotational Speed [rpm] and Torque [Nm].
  * **Degradation Metrics:** Tool Wear [min].

## 🚀 How to Run

To execute this project, follow these steps:

1.  **Launch Notebook:** Click the **"Open in Colab"** badge at the top of this README to launch the environment.
2.  **Prepare Data:** Download the `ai4i2020.csv` file from this repository.
3.  **Upload to Google Colab:**
      * Click the **Files** (folder) icon on the left sidebar in Colab.
      * Click the **Upload** icon and select the `ai4i2020.csv` file.
4.  **Execute Program:** Select **Runtime \> Run all** from the top menu. This will:
      * Clean the dataset and perform an 80/20 train-test split.
      * Train the **Linear Regression** model.
      * Generate visualization graphs for correlation analysis.
5.  **Interactive Prediction:** Scroll to the bottom of the notebook to the **"Industrial Machine Health Checker"** to input manual sensor data and get a risk score.

## 🕹️ Interactive Prediction Feature

One of the key highlights of this project is the **Interactive Machine Health Checker**. Unlike standard models that only process historical data, this project includes a real-time inference loop. A user can manually input current sensor readings (Temperature, Torque, etc.), and the AI will immediately:

1.  Calculate the **Failure Risk Percentage** (0–100%).
2.  Categorize the machine's status as **Normal, Caution, or Danger**.
3.  Provide a recommended action for maintenance teams based on the risk gradient.

## 🧠 AI Concepts Used

  * **Supervised Learning:** Implementation of **Linear Regression** to map continuous sensor inputs to a failure risk score.
  * **Intelligent Agents:** Architecture designed to perceive environment (sensors) and provide a risk-based diagnostic output.
  * **Data Visualization:** Utilization of **Matplotlib** and **Seaborn** for exploratory data analysis and identifying failure correlations.
  * **Robustness Engineering:** Implementation of **Output Clamping** and **Input Validation** to ensure logically sound predictions (0–100%) even when handling anomalous sensor data.

-----
