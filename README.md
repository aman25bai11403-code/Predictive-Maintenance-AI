# 🏭 Industrial IoT Predictive Maintenance System

[](https://colab.research.google.com/drive/1imHAQ4lChJzsE7gajH-ztGGIRC0nInuO?usp=sharing)

## 🛠️ Project Overview

[cite_start]This project addresses the critical industrial challenge of unexpected machine failure[cite: 1, 6]. [cite_start]By leveraging a **Multi-Parametric Predictive Model**, the system analyzes real-time sensor telemetry to predict the **Remaining Useful Life (RUL)** of components[cite: 1, 13]. [cite_start]This transition from reactive to proactive maintenance minimizes unscheduled downtime and enhances operational safety[cite: 1, 7, 34].

## 📊 Dataset & Features

[cite_start]I utilized the **AI4I 2020 Predictive Maintenance Dataset**, consisting of 10,000 instances of high-fidelity industrial sensor readings[cite: 1, 15]. [cite_start]The model focuses on three core feature categories[cite: 1, 10, 13]:

  * [cite_start]**Thermal Dynamics:** Air and Process Temperature [K][cite: 1, 10].
  * [cite_start]**Mechanical Kinematics:** Rotational Speed [rpm] and Torque [Nm][cite: 1, 10].
  * [cite_start]**Degradation Metrics:** Tool Wear [min][cite: 1, 13, 23].

## 🚀 Step-by-Step Execution Guide

To run this project, follow these steps:

1.  **Launch Environment:** Click the **"Open in Colab"** badge at the top of this README to open the notebook directly in your browser.
2.  **Download Dataset:** Ensure you have the `ai4i2020.csv` file available from this repository.
3.  **Upload to Colab:**
      * On the left sidebar in Google Colab, click the **Files** (folder) icon.
      * Click the **Upload** icon and select the `ai4i2020.csv` file.
4.  **Run Training:** Select **Runtime \> Run all** from the top menu. This will:
      * [cite_start]Preprocess the 10,000 sensor records[cite: 1, 17].
      * [cite_start]Train the **Linear Regression** model[cite: 1, 12, 18].
      * [cite_start]Generate visualization graphs (Histograms/Scatter plots)[cite: 1, 16].
5.  **Interactive Inference:** Scroll to the bottom of the notebook to find the **"Industrial Machine Health Checker"**. [cite_start]Manually input sensor values to receive an instant risk assessment[cite: 1, 19].

## 🕹️ Interactive Prediction Feature

[cite_start]A standout highlight of this project is the **Real-Time Inference Loop**[cite: 1, 19]. Unlike static scripts, this allows a user to manually input current machine stats to receive:

1.  [cite_start]**Failure Risk Percentage:** A calculated probability (0-100%) of imminent failure[cite: 1, 21].
2.  **Status Categorization:** Automated classification into **Normal, Caution, or Danger**.
3.  **Actionable Intelligence:** Specific maintenance recommendations based on risk severity.

## 🧠 AI & Engineering Concepts

  * [cite_start]**Supervised Learning:** Implementation of Linear Regression for continuous risk mapping[cite: 1, 12].
  * [cite_start]**Intelligent Agents:** Architecture designed to perceive environment (sensors) and act (alerts)[cite: 1, 10].
  * [cite_start]**Data Visualization:** Correlation analysis using **Matplotlib** and **Seaborn** to identify failure triggers[cite: 1, 16].
  * **Robustness Engineering:** Implementation of **Output Clamping** and **Input Validation** to handle anomalous sensor data.

## 📈 Future Scope

  * [cite_start]**Non-Linear Modeling:** Transitioning to **Random Forest** or **XGBoost** to handle complex stochastic failures[cite: 1, 35].
  * **Explainable AI (XAI):** Integrating tools to explain the "Reasoning" behind high-risk alerts.
  * **Edge Deployment:** Porting the model to IoT hardware (Raspberry Pi) for live factory-floor monitoring.

-----
