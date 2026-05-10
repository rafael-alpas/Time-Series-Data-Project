# 📈 Deep Learning for Time Series Forecasting: LSTM Network
Developed a robust predictive model utilizing Long Short-Term Memory (LSTM) networks to forecast seasonal environmental patterns based on historical time-series data.

## 📌 Project Overview
This project implements an end-to-end machine learning pipeline for time-series analysis and forecasting. It utilizes synthetic data generation to simulate complex seasonal environmental patterns, processes the data through recursive deep learning architectures, and visualizes 30-day future forecasts with high accuracy.

***Note:*** *This repository serves as a technical showcase and documentation. This project was developed as a academic requirement at Mapúa University.*

[📄 Download Documentation](./Time%20Series%20Data%20Project.pdf)

## 🎯 Result
![Project Results](./time%20result.png)

## 🏗️ Architecture & Pipeline
The system follows a structured data science lifecycle optimized for temporal data:

1.  **Synthetic Data Generation:** Engineered a custom data generator using `NumPy` and `Pandas` that incorporates **Yearly Seasonality** (Sine-wave patterns), **Linear Trends**, and **Gaussian Noise** to simulate days of environmental readings.
2.  **Data Preprocessing:** Implemented feature scaling using the `MinMaxScaler` from **Scikit-Learn** to normalize data between [0, 1], ensuring stable gradient descent during training.
3.  **Recurrent Neural Network (RNN):** Built a deep learning model using **TensorFlow/Keras** featuring:
    * **LSTM Layers:** To capture long-term temporal dependencies and solve the vanishing gradient problem.
    * **Dropout Layers:** Integrated for regularization to prevent overfitting.
    * **Dense Output Layer:** To produce the final scalar prediction.
4.  **Recursive Forecasting Engine:** Developed a prediction loop that takes model outputs and feeds them back as inputs to generate a multi-step **30-day future forecast**.



## 🚀 Key Learning Outcomes
- **Temporal Modeling:** Application of **Long Short-Term Memory (LSTM)** units to model data where the sequence and timing are critical.
- **Feature Engineering:** Gained proficiency in simulating and normalizing datasets with multi-layered seasonal and trend components.
- **Predictive Visualization:** Utilized **Matplotlib** to create comparative plots between historical data and future forecasts, facilitating the interpretation of seasonal arcs.
- **Deep Learning Frameworks:** Advanced skills in **TensorFlow and Keras** for sequential model building, utilizing Adam optimizers and Mean Squared Error (MSE) loss.
- **Recursive Logic Implementation:** Successfully built a forecasting algorithm that maintains a sliding window of data to predict multiple future time steps.

## 🛠️ Tech Stack
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

---
*Posted as a showcase of Deep Learning and Predictive Analytics.*
