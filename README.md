\# Predictive and Decision-Making Analysis for Beijing Weather



📍 \*MBA Group Project for BUSI 650 — Business Analytics\*  

🏫 \*University Canada West\*  

📅 \*Completed: March 17, 2024\*



\## ✏️ Overview

This project analyzes weather conditions and pollution levels in Beijing using data collected by the US embassy. The goal: build predictive models and provide insights useful for both citizens and businesses to plan activities around weather and pollution forecasts.


> ⚡ **Excel file contains actual formulas** used for outlier detection, quartile calculation, piecewise regression, and forecasting.


\## 👩‍💻 Team

\- Aditya Prashant Arte (\[@AdiArte96](https://github.com/AdiArte96))

\- Abhilasha Rajan

\- Amandeep Kaur

\- Anitha Juturu

\- Fariha Nasrin

\- Mohammed Sameer Khan



\## 🧰 Methodology

The analysis combined:

\- 📊 Descriptive statistics and data cleaning

\- 📈 Regression analysis

\- 📉 Piecewise linear regression

\- 🕒 Time series forecasting:

&nbsp; - Moving Average

&nbsp; - Exponential Smoothing

&nbsp; - Auto-Regression



\## 📈 Results (highlights)

| Method                 | Pollution | Wind Speed | Dew Point | Temperature |

|-----------------------|----------:|-----------:|---------:|-----------:|

| Moving Average        | 79.56%    | 76.23%     | 96.78%   | 91.32%     |

| Exponential Smoothing | 92.56%    | 89.78%     | 98.93%   | 98.32%     |

| Auto Regression       | -         | -          | -        | 92.61%     |



> Note: R² values shown indicate predictive accuracy.



\## 🗂 Files

\- `/data`: Raw dataset used (`.xlsx`)

\- `/report`: Detailed project report (`.docx`)

\- `/notebooks`: Space to replicate or extend analysis

\- `/images`: Visuals used in analysis



\## 🧠 Key Insights

\- Pollution and wind speed data showed horizontal patterns over time.

\- Temperature and dew point showed clear trends.

\- Exponential Smoothing achieved the highest accuracy overall.

\- Piecewise regression revealed relationships based on wind direction.



\## ✨ Novelty \& creativity

\- Used piecewise regression by splitting data based on wind direction.

\- Combined statistical \& machine learning methods for time series forecasting.

\- Addressed seasonality and outliers via visual and statistical techniques.



\## 📌 References

Cited works include:

\- \[Air pollution prediction using machine learning](https://towardsdatascience.com/hyperlocal-air-quality-prediction-using-machine-learning-ed3a661b9a71)

\- Puma-Villanueva et al. (2006): Data partition \& variable selection.



---



\## ⚙️ Future Work

\- Extend analysis with additional ML models (e.g., LSTM)

\- Deploy models as a dashboard

\- Explore more granular seasonal trends



\## 📜 License

This project is academic. Consider adding an open-source license (e.g., MIT).



---



\## 🚀 How to use

Clone this repository:

```bash

git clone https://github.com/AdiArte96/beijing-weather-prediction-analysis.git



\## 🔗 Repository

\[GitHub Repo](https://github.com/AdiArte96/beijing-weather-prediction-analysis)

